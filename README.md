# gitdemo
-- Create a new repository on the command line
echo "#gitdemo" >>README.md
git init
git add README.md
git commit -m "first
git remote add origin https://github.com/codemobiles/gitdemo.git
git push -u origin master
-- push an existing repository from the command line
git remote add origin https://github.cofm/codemobile/gitdemo.git
git push -u origin master

---------------Command git----------------

touch readme.txt
git add readme.txt
git reset HEAD readme.txt
git commit -m "first"

$ git init //intialize Local Repository
$ git add [file] //Add Files to Repository
$ git status  //Check Status of Working Tree
$ git commit   // Commit Change to Index
$ git push  // Push To Remote Repository
$ git pull //Pull Latest from Remote Repository
$ git clone  //Clone Latest from Remote Repository
$ git log
$ git commit -a -m "Commit"
$ git Checkout id // id ที่ต้องการ rollback
git config --global --list
git config --list #Show configuration of current Repository

git config --global user.name "prizziemz"
git config --global user.email "prissana.pw@gmail.com"
git config --global --lists

-------------Step------------
Add/commit/push/pull

----delete file gitignore
git clean -dfx

git remote add origin  https::
git push -u origin master

git pull origin // origin standing for remoote serve
git pull // short form


Related Commands
 git add - add file to the list of files that can commit to repository
 git commit - save the basic unit of modified records -add , delete update
 git log - view histort andd use hash id to revert the previous code
 git pull - dowload all modification from others
 git push - send all modifications to server
 git clean -df - remove untracked (but not listed .gitignore file)

---------------------------
 Git Branch

 git branch    //List all branches
 git branch [branch-name]  //Create branch
 git checkout [branch-name] //Switch branch
 git checkout -b [branch-name] //Create and Switch branch
 git branch -d [branch-name]  //Delete branch

-----------------------------

Git Merge Branch

git merge [branch]
git merge --no--ff
git branch
git checkout [branch]
git diff[hash id]
git diff[branch]

Review -Tag Version
git tag  //show all tag
git tag v1.0 //create tag named
git tag -d v1.0 //delete tag v1.0
git checkout v1.0 //load file of tag v1.0
git push origin v1.0 // push tag v1.0 to origin server
git push -d origin v1.0 //deldete tag v1.0 in origin server

