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
       
- to connect and update a repository online, just the first time:

       git remote add origin https://github.com/xxx xxxx
       git push -u origin master
       
- To pudate (afer making changes and creating a commit):

       git push

- To create a branch:
       git branch xxxxx

- To know wich branch we are:

       git branch

- To go to a specific branch:
       git checkout main
