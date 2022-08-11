# CMPG-323-Overview---34412883

## Repositories to be done:

The idea is as follows:
To create an individual repository for each project for ease of acess.

    Project name - Linked_Repository
1.) Project 1 - CMPG-323-Overview---34412883
2.) Project 2 - CMPG-323-Project2_Repo
3.) Project 3 - CMPG-323-Project3_Repo
4.) Project 4 - CMPG-323-Project4_Repo
5.) Project 5 - CMPG-323-Project5_Repo
6.) EXAM(POE) - CMPG-323-POE_Repo

### Projects and Repository Integration Diagram:

![Repo_Integration](https://user-images.githubusercontent.com/91745236/184120379-c9cee858-00ff-4380-bdc8-9039decfbfb3.png)

#### Branching Strategy For Each Project:
Project 1 to Project 5: 
Implementation of neat branching strategy, will consist of the following branches:
-MAIN
All content of current project to be merged in the main branch.

-Develop
Content in progress not yet ready for release to be kept under Develop branch.

-Release
Once content is ready to be released it will be placed under the release branch.

EXAM(POE) - Will only consist of a main branch.

##### Use of .gitignore file:
Will be used to make sure no sensitive or unnecessary information gets pushed into the existing content.
Each Project will contain its own .gitignore file("IgnoreThis") where previous planning and progress on projects will be kept, just to make sure previous versions of projects do not get pushed in to current versions.

###### Storage of Credentials and Sensitive Information:
To implement measures of security and encryption of sensitive information I will make use of the "libsodium sealed box" feature that github provides.
