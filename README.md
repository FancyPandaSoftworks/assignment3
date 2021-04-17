# assignment3

Hello ladies and gentlemen, this is a short tutorial about Github. 

## So why Github? 
Github is mostly used to maintain code. Whether it is a solo project or a collaboration, it ensures a good version control of your code. Reached a checkpoint 
and it is working properly? Push it to Github. In case your code fails and you want to recover the previous version you can simply pull it from Github 

I am not going to give you a complete tutorial, but just some basics that you may need. However, as the whole world is using Github it would be nice if you 
are able to master it. 

So open command anywhere you want, preferably the file you want to download the Github project.

## How to download 
You have two ways: One is clicking on the green button (code) and click download zip. But what people mostly do is to use the following command: 

git clone 'the link url of the repository'

## What if you want to modify something? 
Well here is the interesting part. It would be easy to push it to the master branch. But more often that not, you don't want that. So what you rather wanna do is to create a
branch with the following command: 

git checkout -b your_branch_name

This creates a branch and immediately puts you in the branch. 

To check your branches: 

git branch -a

To switch brances: 

git checkout branch_name 

## Send modified files 
To push a file to Github, you do the following: 

1) git add . for every file, or git add file_name
2) git commit -m 'your message here, please be concise and clear, not something like fixed some bugs, that is useless'
3) git push 

And voila it is push to the branch or master (Or main what we call in this project)

## Merge branch with master
If you want to merge it to the master, then you should go to the master branch first. Then: 

git merge branch_name 

Then delete the branch:

git branch -d branch_name

## Extra notes
Oh btw, to do all this I need to add you to the project, so don't forget that xd
