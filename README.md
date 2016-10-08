# stat159-2016fall-lab5

a. User A; Lingjie Qiao
b. User B: Minsu Kim

This repository holds the information regarding lab 5. This lab was done by Lingjie Qiao and Minsu Kim. 

## Task 1: Working on the master branch
This task went pretty smoothly because the users make changes and push the changes after pulling from the master branch. Therefore, there is no merging conflict or errors occurrred in the process. Even though the files are modified and created by different users, there would not be a systemic problem regarding the collaboration.

## Task 2: Resolving Conflicts
User B encountered a merging problem as shown below.
 
! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/lingjieqiao/stat159-2016fall-lab5-version2.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

The reason why we have this conflict is because user B didn’t pull before modifying and pushing the same file.
In order to resolve this conflict, we have to manually merge the file or pull from the master before modifying the file.

## Task 3: Working on multiple branches
I got a merge conflict. So, I solved the file by manually merging the conflicting files

## Task4: Both the users are on different branches
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

There is a merging conflict as shown above. The reason is User B hasn’t pulled from remote master after User A modified file1.txt on branch task4A

## Task 5: Both the users are on different branches w/ conflicts
Here user A encountered a merging conflict, with the error message shown in bellow:
error: failed to push some refs to 'https://github.com/lingjieqiao/stat159-2016fall-lab5-version2.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
The reason there is a conflict is because user B pushes something new to the remote branches, making user A's local repository inconsistent with the remote master. Therefore, we should fix the problem by manually changing the files. 

