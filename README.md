Step-by-step instruction on how to initializa the Git repository for this project.
mkdir new-project
cd new-project
echo "# new-project" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git status
git remote add origin git@github.com:srudyka/new-project.git
git push -u origin main
git checkout main
git pull
git checkout -b development
vi README.md
git add README.md
git commit -m "PROM-42164 #comment update README.md"
git push -u origin development
create a pull request on GitHub from development to main in Github UI
merge the pull request in Github UI
