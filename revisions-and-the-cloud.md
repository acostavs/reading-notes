# Read: 03 - Revisions and the Cloud

![github logo](https://bit.ly/3QvqjwZ)

Git is important because because it gives us a way to work in teams to collaborate on projects and solves past issues.
Distributed Version Control Systems (DVCS) like Git lets us:

* track changes detecting file corruption or loss of information in transit.

* revert changes.

* see different snapshots our files over all our commits.

This lets us fix mistakes easily. Before Git there was Centralized Version Control System (CVCS).
While CVCS addressed the need for collaboration within a developer team, it had a major vulnerability. It had a single point of failure. This could lead to a catastrophic loss of data.

Git prevents this type of loss by letting us create mirrored repositories as data backups. The 3 main states a file could be are committed, modified and staged. You can create a copy of an existing Git repository by running using git clone with a repository’s URL `git clone [Path]`. By cloning a file we get the newest version and full history of that file.

## Some More Git Commands

* `git status` : lets us see the files state

* `git add .` : adds all changes to the staging area

* `git commit -m "meaningful message"` : saves our changes

* `git push origin main` : pushes our changes to our github
