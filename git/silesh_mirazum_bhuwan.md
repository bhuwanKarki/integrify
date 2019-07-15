# Assessment of  another student's GIT submission.
 ## Assessment of *Sileshi Adal*

 * Sileshi has done the good job with the basic git commands.
 * His document was well managed with the explaination followed by the snipping picture which showed the working commands.
 * He has used lots of commands only missing  commands  was
 ```bash
 $ Git stash
 ```

 * His document was well organized which I like
 * His file can be taken as a reference which show the execution of the commands if he forget anything he can just go through it to quickly recall.

* other command that he has used:
```bash
  git log --all --decorate --oneline --graph
```









# GIT tutorial and Javascript based web tool


# Online learning  [Github](https://learngitbranching.js.org/)
# info
"Learn Git Branching" is the most visual and interactive way to learn Git on the web. you'll be challenged with exciting levels, given step-by-step demonstrations of powerful features, and maybe even have a bit of fun along the way.



# learned

  - visual git tutorial was more interactive
  - show the step by step how it work on the basis of graph


You can also:
  - learn to do a various git command with lots of challanges
  - learn a new git command other than just a basic one

## feature not liked
 - you have to restart again if any mistake you do
 - you cannot go back to previous state
 -At some point you dont get a clear picture of what you need to do


### learned Commands

some of the learned commands on Git are:

* git-init - Create an empty Git repository or reinitialize an existing one
* Git clone : getting an existing project to local filesystem
* Git commit: commit a change to a file.
* Git push: Updates remote refs using local refs, while sending objects necessary to complete the given refs.
* Git merge: Join two or more development histories together
* Git log: To see a list of what happened in the repo,
*  Git Rebase : the advantage of rebasing is that it can be used to make a nice linear sequence of commits.
* HEAD always points to the most recent commit which is reflected in the working tree.

* Relative Refs
Moving around in Git by specifying commit hashes can get a bit tedious. In the real world you won't have a nice commit tree visualization next to your terminal, so you'll have to use git log to see hashes.
* Cherry-picking
When cherry-picking a commit in Git, we're taking an older commit, and rerunning it at a defined location. Git copies the changes from the original commit, and then adds them to the current location.


### some used command


 configure Git to use our name and email address.

```bash
$ Git config --global user.name "My Name"
$ Git config --global user.email myname@example.com
```
clone a repo
```bash
$ Git clone repo_url
```

 Branches

```bash
$ git checkout -b branch_name
```

To navigate between existing branches we simply need to type

```bash
$ git checkout <branchname>
```

A list of branches can be viewed with

```bash
$ git branch -a
```
### these are just a few example how you can use a Git . if you want to learn more you can get a lot more insight from the web tutorial.
