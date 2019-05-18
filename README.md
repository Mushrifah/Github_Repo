# Make a github repository using command line 
Learn to make a github repository using cmd by using [Hub](https://github.com/github/hub)

1.Installing Hub

Linux:
```
$ wget https://github.com/github/hub/releases/download/v2.11.2/hub-linux-amd64-2.11.2.tgz
$ tar zvxvf hub-linux-amd64-2.11.2.tgz
$ sudo ./hub-linux-amd64-2.11.2/install
```

2.Create repo using hub
```
$ mkdir GitHub_Repo
$ cd GitHub_Repo
$ git init
$ hub create
$ touch test.txt
$ git add .
$ git commit -m "Initial Commit"
$ git push --set-upstream origin master
```