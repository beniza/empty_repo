# Create a new repo and add this repo as a remote
…or create a new repository on the command line
```shell
echo "# empty_repo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/beniza/empty_repo.git
git push -u origin main
```
# Push an existing repo here
…or push an existing repository from the command line
```shell
git remote add origin https://github.com/beniza/empty_repo.git
git branch -M main
git push -u origin main
```
# Import code from another repo
…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

