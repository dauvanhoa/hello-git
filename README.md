# hello-git
beginer git
git --version
git config --global user.name "your_username"
git config --global user.email "your_email_address@example.com"
git config --global --list

git clone git@gitlab.com:gitlab-tests/sample-project.git
cd sample-project

git init
git remote add origin git@gitlab.com:username/projectpath.git
git remote -v

git pull <REMOTE> <name-of-branch>
git checkout -b <name-of-branch>
git checkout main
git diff
git add <file-name OR folder-name>
git status
git commit -m "COMMENT TO DESCRIBE THE INTENTION OF THE COMMIT"
git commit -a -m "COMMENT TO DESCRIBE THE INTENTION OF THE COMMIT"
git push <remote> <name-of-branch>
git push origin main

git reset
git reset HEAD~1
git checkout <default-branch>
git merge <feature-branch>

