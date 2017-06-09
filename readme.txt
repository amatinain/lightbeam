github.com (gittyup)

$ git add -A
$ git commit -m "Initial commit"
$ git status
----- stage files for commit
$ git add new-page.html index.html css/*
$ git rm error.html  (removal of error.html)
$ git log -p

connect local to remote
no data exchanged
$ git remote add crash-course-remote
may have multiple remotes to a local

$ git remote -v

$ git fetch crash-course-remote

$ git checkout --track crash-course-remote/faq-content

$ git checkout contact-form     (branch)

$ git push -u origin contact-form
$ git push crash-course-remote faq-content

see tracking relationships
$ git branch -vva

---------------------------
$ git remote add origin remote repository URL
# Sets the new remote

$ git remote -v
# Verifies the new remote URL

$ git push origin master
# Pushes the changes in your local repository up to the remote repository you specified as the origin




