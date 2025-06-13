# How we did via local system

- get into the project folder
    git init
    git status
    git add .
    git commit -m "hey hey added stuff/files"

- Push to github
    Create repo on github wherein you want your project  to be in github adnd you'll see the link copy
        git remote add origin link      in terminal
        git remote -v                   Verify remote

# Branches
- main branch where all the branches are there 1 , 2, 3,4  
- branches for more ppl each one work in different branch and merge
        git branch  (default master but we'll ahve to bring it into main)
        git branch -M main
        git branch  (main done)

        git push origin main        (push done, origin we set was main so yeah)
- master

# But wait
    Always anytime you modify or do anything even after adding and commiting you'll have to push into github as well
        git push origin main

                if youw wrote once git pus -u origin main
                    then from nexxt time you can just write as git push and yeay