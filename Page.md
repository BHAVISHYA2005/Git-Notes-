git init (Initializing git)
" git add <File_Path> " or " git add . "(To include all files)
git diff (To check changes)


git commit -m 'Commit message'
git log(To check commit history)
git log --oneline (Shortens the info and commit id)
git show <Commit id> ( visualizes the changes)
git blame <File_name> (which line , WHich user haas added or commited on which date )
[TIP: Dont push every changes in one commit only , Stages main commit karo , Keep your commits clean , if you change a file , create a commit, It brings clarity ]

git status (tells us which files are in staging area and ready to be committed and which ones are in local area)

Important (Revert back)
[Git revert back system is completely based on Linked list concepts, where we have nodes(commits) and we can revert to previous commit whenever there is a  faulty code commit (head)]

git reset --hard <commit id>( So all your commits after this id gets deleted and your head gets selected of the id which has been mentioned)

git revert <commit id>( reverts the code changes )

CODE PUSHING 
--> git remote add origin <Remote_server name(github repo name you created)>
--> git remote -v (Check all remote servers push and fetch allowed )
--> git push -u origin main (-u means upstream , origin means remote server &  main means branch)
--> git push -f (force push - If server has an upstream head and on local you have another head, and you want to change the head of upstream)

BRANCHING 
--> 
