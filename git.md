**GIT LFS(Git Large File Storage)**

Git Large File Storage (LFS) replaces large files such as audio samples, videos, datasets, and graphics with text pointers inside Git, while storing the file contents on a remote server like GitHub.com or GitHub Enterprise.


```
git init
```
```
git lfs track '*psd(file name )'

````

```
git add .

```
```
git commit -m "final file"
```
```
git remote add origin...........
```
```
git push -u origin master
```

**GIT PUSH**(Normal github push)

```
git init
```
```
git add . or git add --all
```
```
git commit -m "final file"
```
then create repo/repository in Github
copy 
```
git remote add origin........
```
```
git push -u add origin
```
***tips***
Github username
```
git config --global user.name
```
Github  mail
```
git config --global user.mail
```

