**git --version**                  ===> check for version installed

if not installed : 
 - sudo apt update
 - sudo apt install git  => verify again

**git config --global user.name "Your Name"**
**git config --global user.email "your.email@example.com"**

git init
git add .
git commit -m "feat: Initial commit with Vite setup for saas-admin-dashboard"


create a repo in github and generate its url: https://github.com/YourName/saas-admin-dashboard.git

git remote add origin https://github.com/YourName/saas-admin-dashboard.git

git push -u origin main


git checkout -b dev

git branch


git push -u origin dev


git add .
git commit -m "feat: [brief description of your feature/fix]"
git push

git checkout main
git merge dev
git push
git checkout dev