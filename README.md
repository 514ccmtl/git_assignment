# Git Assignment - 514ccmtl


# QUESTION 6
# a. What is an issue?
An issue in Git is a way to communicate, manage, and track the progress of code/work in a coding project. Issues are tracked in a particular repository in which comments and notations can be entered so that relevant users can provide commentary, feedback, resolve bugs or provide input on code or issues for a project. 

# b. What is a pull request?
A pull request is a way to merge changes from one branch into another branch. A PR enables the integration of new or revised code, which then faciliates collaboration, feedback, review, and testing.

# c. Describe steps to open a pull request?
The following are the steps to open a pull request:
First, fork the repository from the main branch - On Github.com --> Select Create a new fork in the Code tab 

Second, clone the repository locally to your computer --> In Github.com, copy the URL for the new fork --> Then go to Git Bash, enter git clone https://github.com/your_specific_username/repository.git --> Enter

Third, create a new branch --> In Bash, enter git checkout -b feature/github_branch_name
Fourth, write the code

Fifth, Stage the changes, commit the changes, and write a descriptive commit message --> git -a -m "These are the new changes for the code"

Sixth, push the branch to repository --> git push origin main 

# d. Describe steps to add a collaborator to a repository (share write permissions)
The following are the steps to add a collaborator to a repository:
First, Got to Github.com, log in, and go to the repository where the collaborator should be added

Second, click on the Settings tab of the repository

Third, click the Collaborators button in the Access section

Fourth, click Invite a collaborator in the Collaborators section --> Type the collaborator's Github username --> Click Add username to send an invitation to the user

Fifth, an email is sent to the collaborator --> Collaborator accepts the invitation to access the repo

# e. What is the difference between git and GitHub?
Git is the system (distributed version control system) that operates local to your computer/machine, which enables multiple users to enter code, track the multiple components that make up this code along with its many versions. Git allows an unlimited number of users to collaborate on a common project. In contrast, GitHub is the web platform that is built on top of Git that allows for better UX, easier functionality, enhanced features and improved collaboration when developing code for projects.

# f. What does git diff do?
Git diff is the tool in Git that is used to compare changes that is in our working directory versus the code in our staging area and displays the differences. Git diff is used to resolve merge conflicts.

# g. What is the main branch?
The main branch is the primary default area in a Git repository that holds the consolidated, revised, and maintained code for a project. It is the branch where all other branches are eventually merged and generally houses the current version of the code. 

# h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?
No, we should not directly push our changes into the main branch. Instead, a more appropriate approach is to create a new branch from the main branch, commit and push changes, initiate a pull request, review and merge the code into the main branch then verify that your changes are indeed reflected in the code of the main branch.