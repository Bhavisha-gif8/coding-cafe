## Question 1
--global means the Git configuration applies to the user on the whole computer, rather than only the current repository. If it is omitted, the setting applies only to the current repository.

## Question 2
ls -a showed the .git directory, which does not normally appear with ls. It contains Git's repository information, including its history and configuration.

## Question 3
Git was offering to track many files and folders, especially the files inside .venv/. The .venv/ files were created by the Python virtual environment, not written as part of my lab work.

## Question 4
After creating .gitignore, the files inside .venv/ no longer appeared in git status. Git now ignores the files and folders listed in .gitignore.

## Question 5
.gitignore should be committed because it is a file containing rules for the repository. It tells Git which files and folders should not be tracked.

## Question 6
README.md moved from the untracked-files section to the changes-to-be-committed section after git add README.md. This means the file was staged and is ready to be included in the commit.

## Question 7
After the commit, Git printed a message showing that 2 files changed, with 1 insertion and the deletion of symbol. This confirms that the staged changes were saved in the commit.

## Question 8
The first seven characters are the short form of the commit hash. They identify that particular commit so Git can refer to it easily.

## Question 9
The four steps were checking the status, staging the file with git add, saving the changes with git commit, and checking the history with git log --oneline. This is the basic edit-stage-commit-check cycle.

## Question 10
README.md gets a special name and location because GitHub automatically displays it on the repository's front page. This lets visitors immediately see information about the project.

## Question 11
gh auth login authenticates the GitHub CLI with my GitHub account. After authentication, GitHub can remember the login credentials so I do not have to enter a password every time I use the CLI.

## Question 12
GitHub shows the contents of README.md on the repository's front page. It does this because GitHub automatically renders a file named README.md as the repository description.

## Question 13
No, pushing did not change my local history. git push copied my existing local commits to GitHub.

## Question 14
A private repository exists on GitHub but only people with permission can access it. If there is no repository at all, there is nothing on GitHub to access or collaborate on.#Coding Cafe
