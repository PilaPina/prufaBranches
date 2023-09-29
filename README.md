# prufaBranches

Notes on how to make a branch and push the changes
<br>
- git branch (to check at what branch you are)
- git checkout -b nameofbranch (this makes a new branch  - It´s good practice to keep the naming descriptive of the work you´re doing or where in the code you´re working on, f.ex. 'header')
- make changes to the code -  (if you create a new folder though please let everyone know and push it when you've created it. If instances of the same folder is being created on two different branches with different files in them it will result in a conflict.)
- git add .
- git commit -m "I added something to something"
- git push origin nameofbranch
- Github will show a pull request that you have to click on, comment on the work you've done (f.ex. take a look at what awesome work I've done in the header) and then submit the pull request. Make sure not to merge it.
- Then another programmer takes a look at that pull request, reviews the code, comments on it and askes for changes or just approves it and merges it with main. 
<br>
<br>
- branches can be deleted when they've served their purpose
<br>
<br>
- to switch to another branch: git checkout nameofbranch
