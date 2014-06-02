datasciencecoursera
===================

Coursera Data Science Project Repo

0. Git is on your own computer and GitHub is the online server.

1. To configure your Git:

$ git configure --global user.name "FirstName LastName"

$ git confiture --glboal user.email <youremail>

$ git configure --list

$ git --help


2. Assuming that you have already created the GitHUB repo online, here is how
to initialize an empty repo to that online repo.  Lets call your sample repo 'testrepo'.

$ cd ~/testrepo/

$ git init

$ git remote add origin https://github.com/yourusername/testrepo.git


3. To CLONE a repo from online repo:

$ cd ~/testrepo2/

$ git clone https://github.com/username/reponame.git

Above line will clone the 'reponame.git' from the <username> into your
current folder on your local computer.



4. Git keeps track of your files by adding them to a local index.
To add NEW files to your local Git index, you need to change directory into the
repo you want to work, and to add all files to the repo, do this:

to add NEW files to the index:

$ git add .

to update:

$ git add -u

to do both add NEW files and update:

$ git add -A



5. After indexing, you need to commit the changes to the LOCAL Git repo:

$ git commit -m "enter your message here"


### To update your remote GitHub repo:

$ git push



end-of-file
