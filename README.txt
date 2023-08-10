git command CLI

1) Create gitHub and connect a local .git to the gitHub repository
 $ git init
 => On gitHub, create a new git repository with the same name
 $ git remote add origin https://github.com/psean21c/shirt.git
 $ git remote -v
 $ git push -u origin master

2) Make a change on local and sync (using push command) with he gitHub repository

 $ git add file.txt
 $ git commit -m "blah~"
 $ git push -u origin master

3) Resolve the delta (the difference between a local and remote repository) and Sync

4) Make a branch and Sync with the remote(gitHub) repository
 $ git branch <new branch name>
 $ git checkout <new branch name>
 $ git branch # to see which branch it is currently pointing to
 $ git push -u origin <new branch name> # Sync with gitHub

5) Other command
 $ git status
 $ git log --oneline -all # see HEAD change & changed branch

6) PR (Pull Request) & rebase (재배치)
  PR : 
  https://docs.github.com/pull-requests (official site)
  https://blog.naver.com/islove8587/223179197496 (good diagram)
  rebase : Reapply commits on top of another base tip
