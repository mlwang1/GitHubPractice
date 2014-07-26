# Git Notes

### Creating repo
``` sh
$ touch README.md
$ git init # initialize git repo
$ git add REAME.md
$ git commit -m "first commit"
$ git remote add origin [url]
$ git push -u origin master
# enter username and password
```

### Adding repo with changes
``` sh
$ git add . # add everything that has changed
$ git add -u # when you have deleted a local file you want to remove from your repo
$ git commit -m "changes"
$ git push
# enter username and password
```

### No more username and password input for every push
``` sh
$ git remote set-url origin git@github.com:yourUsername/yourReponame.git
```