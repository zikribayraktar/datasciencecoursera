datasciencecoursera
===================

### Coursera Data Science Project Git Instructions:

#### Git is on your own computer and GitHub is the online server.

#### To configure your local Git:

$ git config --global user.name "FirstName LastName"

$ git config --global user.email yourname@email.com

$ git config --list

$ git --help


#### Assuming that you have already created the GitHUB repo online, here is how
#### to initialize an empty repo to that online repo.  Lets call your sample repo 'testrepo'.

$ cd ~/testrepo/

$ git init

$ git remote add origin https://github.com/yourusername/testrepo.git


#### To CLONE a repo from online repo:

$ cd ~/testrepo2/

$ git clone https://github.com/username/reponame.git

Above line will clone the 'reponame.git' from the <username> into your
current folder on your local computer.



#### Git keeps track of your files by adding them to a local index.
To add NEW files to your local Git index, you need to change directory into the
repo you want to work, and to add all files to the repo, do this:

## to add NEW files to the index:

$ git add .

## to update:

$ git add -u

## to do both add NEW files and update:

$ git add -A



#### After indexing, you need to commit the changes to the LOCAL Git repo:

$ git commit -m "enter your message here"


#### To update your remote GitHub repo:

$ git push

#### To create a branch:

$ git checkout -b branchname


#### To see what branch you are on:

$ git branch

#### To switch back to the master branch:

$ git checkout master



end-of-file
