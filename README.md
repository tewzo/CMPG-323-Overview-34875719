# CMPG-323-Overview-34875719
###Repositories

I have five projects over the course of the semester, along with a portfolio of evidence, hereon in POE, which all combine to a final mark. Each project will use the base repository “CMPG-323-Overview-34875719” as well as the POE. These will be divided into sub folders within the repository. If I feel as though I require a separate repository during the semester this readme will be updated accordingly.

###Project and Repository Context

![Project Context](https://www.icloud.com/iclouddrive/079isrrHwM5V-h26Ty6usT2zA#repo-project-context)

###Branching Strategy

In order to merge one will have to branch off of dev following the standard:

feature/TICKET/summary-with-dashes-as-spaces

A branch must be approved and should pass a build before it may be merged.

###Explanation of .gitignore within project

The .gitignore allows for certain files to be ignored on commits. This is useful, for example we do not require the “built” application in many cases or databases to be persisted to git. There may also be sensitive information such as documentation provided by the North West University which should be ignored.

###Storing Sensitive Information

Sensitive information should not be persisted. The use of git-secret will be employed to break builds if sensitive information is found.

