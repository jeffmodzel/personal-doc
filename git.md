# Git

How to store credentials:

```bash
 git config --global credential.helper store
```
Updates `~/.gitconfig` like:
```
[user]
    email = person@email.com
    name = some person
[credential]
   helper = store

or use:

git config -l
```

create git md file and link it

Stores plaintext credentials in `~/.git-credentials`

Details here: https://git-scm.com/book/en/v2/Git-Tools-Credential-Storage


https://rogerdudler.github.io/git-guide/


git checkout -b feature_x
git push origin <branch>


```script
// create new branch and check it out
git checkout -b feature_x

// push branch to new remote branch
git push origin feature_x


// delete branch locally
git branch -d localBranchName

// delete branch remotely
git push origin --delete remoteBranchName
```