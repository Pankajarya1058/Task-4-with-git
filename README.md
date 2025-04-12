## In this repository i have perform following steps.

### Create directory in local
```
mkdir devops-project
cd devops-project
```
### initialize directory
```
git init
```
### configure user name and email
```
git config user.name pankaj
git config user.email pankajarya1058@gmail.com
```

### create repo in github and add its url in local
```
git remote add origin https://github.com/Pankajarya1058/Task-4-with-git.git
```

### create empty index.html file in local and push in this repo
```
touch index.html
git add index.html
git commit -m "initial commit"
git tag -a v1.0 -m "initial release"
git push origin v1.0 main
# provide github account username and PAT(personal access Token)
# for PAT, Go to github settings > Developer settings > personal access tokens
```
### Create dev and feature branch in local
```
git checkout dev
git checkout feature
```

### Go to dev branch and and create index.html file and mention content in it
```
git switch dev
vim index.html
git add index.html
git commit -m "edit index.html in dev"
git push origin dev
```

### Go to feature branch and create style.css and mention content in it
```
git switch feature
vim style.css
git add style.css
git commit -m "adding css in feature"
git push origin feature
```

#### Now, go to github repo and create pull request from feature branch to dev branch and merge.
#### then, create pull request from dev branch to main and merge them 










