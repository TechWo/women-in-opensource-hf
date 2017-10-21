# Best practices

## Adding an existing project to Git Remote Repository using the command line

* Initialize git repository
```
git init
```

* Add all changes
```
git add .
```

* Create the commit
```
git commit -m "First commit"
```

* Add the remote url of the repo that already exists
```
git remote add origin [remote repository URL]
```

* Check the remote origin
```
git remote -v
```

* Push local changes to origin (remote repository)
```
git push origin master
```