Q1. Question 1: Meaning of --global in git config and omitting it
--global means the Git username and email are saved as the default settings for my user account on this computer, so they apply to all my Git repositories. If I leave it out, the settings apply only to the current repository.

Q2.Question 2: Contents of .git revealed by ls -a
---- The .git directory appeared in ls -a but not in the normal ls output because it is a hidden directory. It contains Git's internal files and information, such as the repository's history, configuration, and references.

Q3.  Question 3: Approximate untracked file count and identifying untracked code
----Git was offering to track roughly the files and folders in my coding-cafe directory, including the .venv folder and its many files. The .venv folder contains Python environment files that I did not write, so it should not be tracked by Git.

Q4. Question 4: Difference in git status after creating .gitignore
----After adding .gitignore, the .venv/ folder and its files disappeared from git status because Git is now ignoring them. The .gitignore file itself appears as an untracked file.

Q5.Question 5: Why .gitignore itself should be committed rather than ignored
----- .gitignore should be committed, not ignored. It tells Git which files and folders to ignore, so keeping it in the repository makes sure the same rules apply to everyone working on the project.

Q6.Question 6: Movement of README.md across sections in git status (three-places model)
---- README.md moved from “Untracked files” to “Changes to be committed.” In the three-places model, it moved from the working directory to the staging area because git add README.md staged it.

Q7.  Question 7: Output produced by git commit and count of changed files
[master 491a8de] Write README
 1 file changed, 2 insertions(+), 2 deletions(-)

Q8.Question 8: Name and purpose of the first seven characters of a commit hash
---- Name: Short commit hash (or short SHA-1 checksum).

Purpose: It serves as a unique, abbreviated identifier for a specific commit in the repository, making it easier to reference in commands (such as git checkout, git log, or git show) without needing to type the full 40-character SHA-1 hash.

Q9. Question 9: The 4 steps of the repetitive Git loop
-----The four steps are edit → check git status → stage with git add → commit with git commit. This loop is repeated whenever I make changes that I want to save in Git history.

Q10. Question 10: Special purpose and placement of README.md
-----README.md has a special name and place because GitHub automatically displays it on the repository’s main page. It acts as an introduction and documentation for the project, so visitors can understand the repository without opening another file.

Q11. Question 11: How gh auth login eliminates future password prompts
----gh auth login authenticated my GitHub account and configured Git to use my GitHub credentials for HTTPS operations. This means Git can authenticate my pushes without asking me for my GitHub password each time.

Q12.uestion 12: File rendered on GitHub's front page and the reason why
---- The README.md file is showing on the front page of the GitHub repository. GitHub automatically displays a root README.md as the repository’s introduction and documentation.

Q13.Question 13: Effect of git push on local history
----- No, pushing did not change my local history. It only copied my existing local commits to the GitHub repository; the commits and their history remained the same locally.

Q14. Question 14: Distinction between a private repository vs. no repository on GitHub
----a private repository exists on GitHub, but only the owner and people who have been given access can view or work with it. If a repository does not exist on GitHub, there is no online copy of the project or its Git history to access.
