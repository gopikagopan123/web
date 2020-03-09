# PROJECT-SD-LAB
## Project Report

Firstly  now I started understanding and exploring github desktop platform which was my IDE for git.The veryfirst thing I have 
done with github was creating a public repository.My project repository was named asPROJECT_SD_LAB. It quite interested to me
because in my project works using commands and terminal to access git hub and my repository, Here steps are follows:

**1. Installing git**
I need to install git on my system ,while installing time I had'nt face any problem so successfully install it.

**2. Initialize**
In initialize step I have to create a folder in linux .So I named that folder as Project_123.After creating the folder,I have 
to redirect the prompt to newly created folder as Project_123.So I 'm using the command as*git init*,This command in my 
repository was initialized in corresponding folder.

**3. Create and setting git configuration**
 Firstly we want to create a git repository in github after creating git repository invite our team members.Then,
   
   git config --global user.name "gopikagopu"
   git config --global user.email"gopikagopanply2@gmail.com"
   
 **4. Cloning the github repository**
 To clone use the command git clone https://github.com/Project123jrg/PROJECT-SD-LAB.git
 
 **5. Adding files on the repository**
 Using git add file1.txt command for adding files to the staging area.Then we can use git status command for display both
 tracked and untracked files.
 
 **6. Commit the changes**
 This will commit the staged snapshot and will launch a text editor prompting you for a message.You can commit using
  
   git commit -m "message"
   
 **7. Git Pull and Push**
 This command fetches changes from a remote repository to local repository.It merges upstream changes in your local repository,
 which is a common task in git based collaberation before you affect changes to the central repository.Then in the case of push 
 commands used for push to publish your local repository.After that several local commits are ready to share them with the rest
 of the team
   
   git pull origin<branch_name>
   git push origin master
 **8. Branching**
 We can check what your current branch by using the command:git branch.To create new branch use the command:git branch<branch_name>
     git branch
     git branch -a
     git pull
     
 **9. Merging**
 To combine the work of different branches together, let us merge the two branches with the command :git merge branch_name.
 Checkout the master branch with the command: git checkout master and merge the command
     git checkout master
     git merge gopu
 
 **10. Rebasing**
 A way of combining  the work between different branches.Rebasing takes a set of commits for copying and storing them outside the
 local repository.To rebase using following commands like:
     git checkout -b gopika
     git commit -a -m "1st commit"
     git rebase gopika
     git rebase --interactive gopika
     
     so at last a message will come like : successfully rebased and updated refs/heads/gopika
   
 
 
 
 
 



