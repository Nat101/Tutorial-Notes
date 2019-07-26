# Tutorial-Notes
 1. In computer terminal: <git help>

# Definitions:
 1. Repository = Project
 2. Readme = Instructions/ notes for users
 3. Clone = allows you to download repository to home computer


# Getting Started:
 1. In repositories select <New>
 2. Name and describe repository
 3. Choose whether to make your project public or private
 4. Check the box: <Initialize this repository with a README>
 
 # Cloning repository and downloading to home computer
  1. Select repository
  2. Select <clone or download> upper right corner, green button
  3. Select clipboard icon to copy URL
  4. Open terminal on computer
  5. Navigate to desired directory
  6. Type <git clone > then paste copied URL
  
 # Upload modified repository
  1. Open terminal on computer
  2. Navitgate to directory
  3. Type <git status> (this shows all difference between git repository and local files)
  4. Type <git add > then local file name to add
      or type <git add .> (all local files)
      or type <git add -A> (all local files)
  5. Type <git commit> (locks it into repository)
      or type <git commit -m "type note/message here in quotes">
  6. Type <git push> (this syncs the commit to repository)
  
 # Download modified repository
  1. Type <git pull>
  
 # Create Branch
  1. <git branch -a> (lists all branches, *is current working branch)
  2. <git branch > Branch name (creates new working branch)
  3. <git checkout > Branch name (switches current working branch)
  4. <git checkout -b > Branch name (creates and switches working branch)
  
 # Merge Branch with Master
  1. <git checkout master>
  2. <git merge > Branch name
  
  
  

