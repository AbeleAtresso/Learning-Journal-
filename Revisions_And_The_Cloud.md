# Revisions And The Cloud

## What is Git? 

Git is a Distributed Version Control systems (DVS) that stores data in a file system made up of snapshots. Where programmers working in teams can collaborate with each other and all changes or commits made by them will be saved. Git was developed in 2005 by the chief architect of the Linux Kernel, Linus Torvalds.

## Downloading Git. 

Git can be installed in three ways:

1. Install as a package
1. Install via another installer
1. Download and compile the source code.

## Important Commands

#### Cloning 
You can also create a copy of am existing Git reposutory from a particular server by using the clone command with a repository's URL: 
      
   $ git clone URL
or you can clone a repository into a directory with another name of your choosing, 
  
   $ git clone URL filename
 
#### Check file Status 
   $ git status - use to see what chages are made to your repostory. 
<<<<<<< HEAD
   
   git add - adds a change in the working sirectory to the satging area.
  
=======
 
   git add - adds a chamge in the working sirectory to the satging area.
 
>>>>>>> 93030d6c9d88907c4d6cec7c60bac180e1f00be6
   git push - sends changes from local repostory to global repostory or GitHub. 


#### Commiutting all changes
This command commits a snapshot of all modifications to tracked files in the working directory, 
    
   $ git commit -a

### Site Navigation
- [Home](/README.md)
- [Growth Mindset](/GrowthMindset.md)
- [Read and Discussion](/Discussion.md)
- [Coder's Computer](/Coder'sComputer.md) 
- [Stretch Goal Class 03](/StretchGoalClass03.md) 
- [Revisons and the Cloud](/Revisions_And_The_Cloud.md)