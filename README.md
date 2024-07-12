# Git Command

&nbsp;

#### Git Config Settings

```bash
git config --global user.email "your-email@example.com"
```

```bash
git config --global user.name "Your Name"
```

```bash 
git config --list
```

#### Default Editor
```bash 
git config --global core.editor "code --wait"
```

#### Check git status
```bash
git status
```

#### Initializing
```bash
git init
```

#### Add to Stagging
```bash
git add <File-Name>
git add .
```

#### Commit
```bash
git commit
git commit -m "Commit Message"
```

#### Check git Log
```bash
git log
```

#### List all Branchs
```bash
git branch
```

#### Create New Branch
```bash
git branch <Branch-Name>
```

#### Switch Branch
```bash
git switch <Branch-Name>
```

#### Create & Switch to New Branch
```bash
git switch -c <Branch-Name>
```

#### Change Branch
```bash
git checkout <Branch-Name>
```

#### Merge Branch
Always merge from main/master branch
```bash
git merge <Branch-Name>
```

#### Rename Branch
```bash
git branch -m <old-branch-name> <new-branch-name>
```

#### Delete Branch
```bash
git branch -d <branch-name>
```

#### Compare
```bash
git diff
```

#### Compare stagged area
```bash
git diff --staged
```

#### Compare Branches
```bash
git diff <branch-name-one> <branch-name-two>
```

#### Compare Commits
```bash
git diff <commit-hash-one> <commit-hash-two>
```

#### Stash(Temperory Commit)
```bash
git stash
```

#### Stash with naming
```bash
git stash save "work in progress on X feature"
```

#### Stash list
```bash
git stash list
```

#### Apply top stash
```bash
git stash apply
```

#### Apply Specific Stash
```bash
git stash apply stash@{0}
```

#### Apply top stash and delete it
```bash
git stash pop
```

#### Drop Stash
```bash
git stash drop
```

#### Clear all Stash
```bash
git stash clear
```

#### Create Tag
```bash
git tag <tag-name>
```

#### Create annotated Tag
```bash
git tag -a <tag-name> -m "Release 1.0"
```

#### List all Tag
```bash
git tag
```

#### Tag a Commit
```bash
git tag <tag-name> <commit-hash>
```

#### Push Tag
```bash
git push origin <tag-name>
```

#### Delete Tag
```bash
git tag -d <tag-name>
```

#### Delete Tag on Repo
```bash
git push origin :<tag-name>
```

#### Rebase(Most case from side branch)
```bash
git rebase main
```

#### Reflog(Detailed Log)
```bash
git reflog
```

#### Reflog specific Commit
```bash
git reflog <commit-hash>
```

#### Recover lost commits or changes
```bash
git reflog <commit-hash>
git reset --hard <commit-hash>
```

#### Add Remote Repo
```bash
git remote add origin <remote-url>
```

#### Check Remote Repo
```bash
git remote -v
```

#### Push
```bash
git push origin main
```

#### Fetch
```bash
git fetch <remote-name>
```

#### Pull
```bash
git pull origin main
```

#### Push Forcelly
```bash
git push origin --force-with-lease <branch-name>
```
