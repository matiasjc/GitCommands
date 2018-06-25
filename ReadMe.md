# **GIT COMMANDS**

## **HELP**

**git COMMAND --help**

**git help COMMAND**

## **CONFIG**

**git config --global user.email "EMAIL"** (email)

**git config --global user.name "USERNAME"** (name)

**git config color.ui "true"** (colored lines)

**git config format.pretty "fuller"** (display format)

## **REPOSITORY**

**git init** (create empty repository)

**git init "PROYECT-NAME"** (create new local repository with specified name)

**git status** (show working tree status)

## **CLONE**

**git clone URL** (clone a repository into a new directory)

## **REMOTE**

**git remote** (show remote origins)

**git remote add origin URL** (add remote origin)

## **ADD**

**git add FILENAME** (add file)

**git add DIRECTORY** (add directory)

**git add .** (add all)

**git add --all** (add all)

**git add '\*.EXTENSION'** (add files by wildcard)

## **REMOVE**

**git rm -f FILENAME** (remove file)

**git rm -r DIRECTORY** (remove directory)

## **COMMIT**

**git commit -m "MESSAGE"** (commit with message)

**git commit -a -m "MESSAGE"** (add and commit with message)

## **RESET**

**git reset HEAD filename** (rollback file)

**git reset HEAD~1** (rollback one commit)

**git reset HEAD~2** (rollback two commits)

**git reset HEAD~1 --soft** (rollback one commit and keep files)

**git reset HEAD~1 --hard** (rollback one commit and delete files)

**git reset --hard origin/master** (rollback all changes)

## **FETCH**

**git fetch origin** (show changes from origin)

## **PULL**

**git pull** (get all changes)

**git pull origin master** (get all changes)

## **PUSH**

**git push** (send changes to origin)

**git push -u origin master** (send changes to origin)

**git push origin BRANCH_NAME** (send branch to origin)

**git push origin master --tags** (send tags to origin)

**git push origin :refs/tags/VERSION** (remove tag from origin)

## **CHECKOUT**

**git checkout -b BRANCH_NAME** (create and select branch)

**git checkout master** (select master branch)

**git checkout -- FILENAME** (undo file changes)

## **BRANCH**

**git branch** (show local branches)

**git branch -a** (show origin branches)

**git branch BRANCH_NAME** (create branch)

**git branch -d BRANCH_NAME** (delete branch)

## **DIFF**

**git diff ORIGIN_BRANCH DESTINY_BRANCH** (diff branches)

## **MERGE**

**git merge BRANCH_NAME** (merge branch)

**git mergetool** (merge tool)

## **MERGE ONE COMMIT**

**git cherry-pick** SHA1

## **TAG**

**git tag -l** (show tags)

**git tag VERSION** (create tag)

**git tag -d VERSION** (remove tag)

## **LOG**

**git log** (show commit logs)

## **PROXY**

**git config --global http.proxy http://USER:PASSWORD@PROXY:PORT**

**git config --global --unset http.proxy**

## **RESET COMMIT HISTORY**

**rmdir /s /q .git**

**git init**

**git remote add origin URL**

**git add --all**

**git commit -am "MESSAGE"**

**git push -f origin master**

## **SAVE FRAGMENTS**

**git stash** (create temp branch)

**git stash list** (show temp branches)

**git stash pop** (Restores the most recently stashed ﬁles)

**git stash drop** (Discards the most recently stashed changeset)

**git stash apply** (apply last temp branch)
