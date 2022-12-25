# help
help upload projects


https://gist.github.com/sharbel93/ebcf0b18782573f4d95f80caa3c84acb

First Do this ...

git fetch origin master
git merge  master

Then, do this ...

git fetch origin master:tmp
git rebase tmp
git push origin HEAD:master
git branch -D tmp

Now everything works well.
