This is only a test

Create a linux vm
run the following commands
$sudo apt-get update
$sudo apt-get install git
git --version
mkdir edyoda
cd edyoda/
ls
vim file1.c
cat file1.c
vim file2.c
cat file2.c
ls 
vim readme.md
cat readme.md
ls


git init
ls -a
cd .git/
ls
cd ..
git add file1.c
git add file2.c
git add .  (This is for the whole entire directory)
git commit -m "Initial Commit"
git config --global "email@example.com"
git config --global username "username"
git commit -m "Initial Commit"
git remote add origin https://github/marcsamuel/edyoda.git
git push origin master
