# Git Command Line Cheat Sheet

*A cheat sheet for using Git from Mac Terminal, for C4Q students & alumni, and anyone else who is either a beginner or forgetful.*

## Vocabulary
* **Repo:** A special copy of your project that includes a list of changes (commits) you've made over time
* **Local:** The copy of the repo you have on your machine
* **Remote:** A copy of the repo on a website, such as Github
* **Staging**: Placing changes in the repo, so you can save them later
* **Commit:** Saved changes to the repo
* **Commiting:** Saving the changes you've made to a local repo
* **Pushing:** Uploading the changes to a remote repo
* **Pulling:** Downloading changes in the remote to your local repo

## Commands
* **Check the name of the current folder:** pwd
* **Put the Github project in the current folder:** git clone *insert url of repo*
* **View a list of files in the current folder:** ls
* **Go into the project folder:** cd *insert name of project*
* **Add a remote repo:** git remote add *insert url from github, or name you want the remote to go by*
* **Exit a folder:**  cd ..
* **Stage your changes in the repo:** git add -A
* **Save your latest changes to the local repo:** *Make sure you're in the project 
folder, then run* git commit origin master -a -m *sample message for your commit -- make sure your message is contained in between quote marks!*
* **Get your latest changes into the remote repo:** git push origin master
* **If you get stuck in the default text editor (it's called Vim) when writing your commit message:** *Hit colon,
then q, then press enter*
* **Check that your local version is up to date with the remote, or see if there are any problems:** git status
* **Get the latest changes in the remote:** git pull origin master
* **View a list of previous commits:** git log
* **Exit the list of previous commits:** *Hit colon, then q, then press enter*
* **View the names of remote repos:** git remote -v
* **Wtf is going on?!:** *Ask for help or copy and paste the error message into Google* 
* **Nuke your local project:** *Exit the project folder, then type* rm -rf *insert name of project*
