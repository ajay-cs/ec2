
How to delete the commit history in github

rm -rf .git
git init
git remote add origin https://github.com/ajay-cs/ec2
git remote -v
git add --all
git commit -am 'initial commit'
git push -f origin master
