# Installing Git with Anaconda

Git is a free and open-source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. It lets you track who made changes to what and when, and it has options for easily updating a shared or public version of your code on GitHub.

* Step 1: Search for ‘Anaconda Prompt’ using cmd+space (on Mac) or Wind+S (Windows) and launch it.
* Step 2: Run command `conda install -c anaconda git`
* Step 3: Run command `git --version` to confirm the git version

Now that you have git installed, it’s time to create a git repo

* Step 4: Go to https://github.com/ and sign up to create your GitHub account.
* Step 5: Go to the GitHub home page. You can find the “New repository” option under the “+” sign next to your profile picture, in the top right corner of the navbar. After clicking the button, GitHub will ask you to name your repo and provide a brief description
* Step 6: In the repository name field enter `tech_fundamentals_tictactoe`
* Step 7: When you're done filling out the information, press the 'Create repository' button to make your new repo.
* Step 8: Copy the clone URL of the GitHub repo that you created in the above step. Clone operation creates an instance of the remote repository.


* Step 9: In the anaconda prompt browse to the directory where you want your code to reside and run the command to clone your repository
`git clone <clone_url>`
* Step 10: Change the directory to the new local repository and list its directory contents.
`cd tech_fundamentals_tictactoe`
* Step 11: Add your tictactoe notebook to this folder and run the command
`git status`
* Step 12: Stage this file for commit by running the command:
`git add <jupyter_notebook_name>`
* Step 13: Commit the file with an appropriate commit message using the command
`git commit -m “my first git commit”`
* Step 14: Now that the changes are committed push them to the appropriate branch in your repository
`git push origin master`
