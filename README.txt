 _____ _  _____    _  ____           
/  __// \/__ __\  / \/ ___\          
| |  _| |  / \    | ||    \          
| |_//| |  | |    | |\___ |          
\____\\_/  \_/    \_/\____/          
___  _ ____  _     ____              
\  \///  _ \/ \ /\/  __\             
 \  / | / \|| | |||  \/|             
 / /  | \_/|| \_/||    /             
/_/   \____/\____/\_/\_\             
 _____ ____  _  _____ _      ____  _ 
/    //  __\/ \/  __// \  /|/  _ \/ \
|  __\|  \/|| ||  \  | |\ ||| | \|| |
| |   |    /| ||  /_ | | \||| |_/|\_/
\_/   \_/\_\\_/\____\\_/  \|\____/(_)
                                     

To initialize a new repository, first go to http://www.github.com/your_git_name in your web browser and create a repo from your account.

then at the command line type:

git init

then: 

git commit -m "first commit"

then: 
git remote add origin https://github.com/your_github_name/your_repo_name.git

then:
git push -u origin master

This will set up a repo for your code where you can save things you don't want to lose if your laptop gets stolen, or...

You will make many new repos over your time at WDI. It will be fun to look back on all of it later!

.__                                       __    
|  |__   ____   _______  _  _____________|  | __
|  |  \ /  _ \ /     \ \/ \/ /  _ \_  __ \  |/ /
|   Y  (  <_> )  Y Y  \     (  <_> )  | \/    < 
|___|  /\____/|__|_|  /\/\_/ \____/|__|  |__|_ \
     \/             \/                        \/

The homework you do will be submitted to a repo where all your instructors can look at it. It is located here:
https://github.com/ga-students/WDI_SF_4_Work

Please follow instructions in the README.md file to submit your work.

Some other useful git commands
-------------------------------

to copy code down to your machine:

git clone https://github.com/project_name.git

to see which branch you're on:

git branch

to merge with another branch:

git merge branch_name

to see what has been checked in:

git status


A fun command-line tutorial on Github can be had by typing the following at the command line: 

gem install githug

A bunch of stuff will spew out while it's installing, magic! Then you can type "githug" at the command line and follow the instructions!

