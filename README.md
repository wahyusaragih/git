# GIT Basic Command

> Download gitbash to improve productivity

### Fundamental
```php
$ git --version // check git version
$ touch // create file
$ git init  //Iniatialize Local Git Repository
$ git add <files> //add files to index
$ git status // Check status of working tree
$ git commit // Commit Changes in Index
$ git log // check folder log
$ git push // update file to remote repository
```

### Remote Respository
```php
$ git push // Push to remote Repository
$ git pull // Pull latest from remote Repository
$ git clone // Clone repository into a new repository
```

### Using GIT IGNORE
```php
1. create file .gitignore
2. add file to ignore inside .gitignore by typing file name // index.html
3. add folder to ignore inside .gitignore by typing folder name // /dir2
```
___

### Pushing file to github for Beginner (no branch)
```php
1. $ git init
2. $ git config --global user.name 'Wahyu Saragih' // add name to git
3. $ git config --global user.email 'wahyusaragih@yahoo.com' // add email to git
4. $ git add <file and ext> // add file to staging area
5. $ git status // check git status
6. $ git rm --cache <file> // remove file from staging area
7. $ git add *.html // add all html file
8. $ git add . // add all files
9. $ git commit
    result: vim editor window
        press "i" to go to insert mode
        remove comment "#" from inital commit
        press "esc"
        type ":wq"
        press enter
10. $ git status
11. $ git commit -m 'type a comment here'
12. create new repository on github
13. copy $ git remote line //$ git remote add origin url
14. copy $ git push origin //$ git push -u origin master
15. login to github
16. touch README.md // add readme file
17. $ git add
18. $ git commit -m 'Added rename'
19. $ git push
```

### Updating files to github
```php
1. $ git commit -m 'type a comment here' //update file to staging area
2. $ git push //push file to github
```

### Clone repository from github
```php
1. copy repo url to clone
2. create new folder 
3. open git bash
4. $ git clone url
```