      git version
      
- Inititialize git

      git init
      
- Status

      git status -s
      
      
- Add files to the staging area

      git add name
      git add .
      
 - Creat a new commit:
      
       git commit -m 'version 1'
       git commit -m .
       
 - Check commits:

       git log --oneline
       
 - to navigate between commits:
 
       git reset --hard xxxxxx
       
- to connect and update a repository online:

       git remote add origin https://github.com/xxx xxxx
       git push -u origin master
