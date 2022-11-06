## Research Questions

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a language or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
	Git is a version control system, so basically it keeps all the versions of a file so that it's possible to access previous versions before certain changes were made.

2. What is the difference between Git and GitHub?
	Git is the version control system itself, but GitHub is a hosting site for the repositories that someone creates on their computer. GitHub keeps the repositories in the cloud so that it is possible to collaborate with others on a project.
	
3. Why do we create a branch?
	Branches are useful to make edits to a piece of code without altering the original piece of code itself. It allows a full set of changes to be made and then for those changes to be reviewed before they are integrated into the parent branch.
	
4. What is the purpose of a Pull Request?
	A Pull Request allows the person who maintains a git repository to have control over what branches of code can be merged with the main code before they are merged.

	
5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.
	git checkout main


6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
	"git fetch" gets (fetches) code from a repository to edit; "git merge" combines code from that repository into main code; "git pull" both fetches the code and then merges it.


7. What is a merge conflict?
	A merge conflict happens when two people worked on the same code in their branches and there are differences that conflict with each other, for example if one person made changes in a file in their repository and another person deleted that file and then they both tried to make a pull request, then both changes couldn't be made at the same time and something would have to be done manually to resolve the conflict.

8. How do you resolve a merge conflict?
		Git will indicate where the conflict is occurring in the code (where edits by separate people were made on the same piece of code), and then someone will have to go through the code and manually decide which of the changes should be kept or discarded. 