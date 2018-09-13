Hi, I'm Jon.

In this repository (the first of many), I will only have 1 file - this README file. 

Here, I will summarize the basics of how to use git/bash/commandline/github. As I learn more, I will update this file. 

Setting Up (The Basics):

- Download Git
- Open up Terminal (Mac user)

- To find the folder that you have chosen to store your work in, use "cd" and "ls". 
  - "cd" stands for "change directory'. Use "cd" to locate your file. 
  - EX: cd Desktop (then cd Github, then cd hello-world to get into the REPO)
  - "ls" stands for list. Use "ls" to list the files in the directory you are currently in.
  - Remember, "cd" INTO the REPO you are WORKING ON. 

- Cloning (Clone and Status) 
  - To clone a repository from GitHub to your local storage (personal computer), use the clone command.
  - EX: git clone https://github.com/jonho7800/hello-world.git (the command to clone this very repo).
  - Make sure when you clone, you clone in the folder you want the REPO to be placed in. 
  - To CHECK on the status of the contents within the repo, use "git status". 
  
- Uploading (Add, Commitand, and Push) 
  - Let's say you made a new file in your repo. Now you have to inform git/github of its presence. 
  - To do so, "git add <file name>".
  - EX: git add newfile.html
  - Now, you must commit this change. To do so, use "git commit -m 'comments'" (use quotation marks around the comment you have made). 
  - EX: git commit -m "popping the cherry" 
  - To make these changes to GitHub, use "git push". 
  - You'll have to enter your GitHub username and password. 
  
- Removing Items
  - To remove an item, use "git rm <file name>".
  - EX: git rm haters.html
  - Now, commit and push. 
  
- Downloading (Pulling)
  - It's as simple as "git pull". 

- Misc.
  - If you need a quick refresher on the git commands, just "git help". 
  - Good tutorial on the basics: https://www.youtube.com/watch?v=0fKg7e37bQE 


