*A cheat sheet for using Git from Mac Terminal, for C4Q students & alumni, and anyone else who is either a beginner or forgetful,*

Note: When dealing with Git, you have a *local* version of the project on your
machine, and *remote* versions that you can see on the Github website. The remote
versions will not automatically update -- you need to commit any changes!

* **Check the name of the current folder:** pwd
* **Put the Github project in the current folder:** git clone *insert url of repo*
* **View a list of files in the current folder:** ls
* **Go into the project folder:** cd *insert name of project*
* **Exit a folder:**  cd ..
* **Save your latest changes to the remote repo:** *Make sure you're in the project 
folder, then run* git commit origin master -a -m *sample message for your commit*
* **If you get stuck in the message text editor (it's called Vim):** *Hit colon,
then q, then press enter*
* **Check that your local version is up to date with the remote, or see if there are any problems:** git status
* **Get the latest changes in the master branch:** git pull origin master
* **View a list of previous commits:** git log
* **Exit the list of previous commits:** *Hit colon, then q, then press enter*
* **View the names of remote versions:** git remote -v
* **Add a remote:** git remote add *insert url from github, or name you want the remote to go by*
* **Wtf is going on?!:** *Ask for help or copy and paste the error message into Google* 
* **Nuke your local project:** *Exit the project folder, then type* rm -rf *insert name of project*
