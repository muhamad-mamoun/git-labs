1- How to remove the branches locally:
    - git branch -d "branch-name" #if the branch is fully merged#
    - git branch -D "branch-name" #if the branch is NOT fully merged#
<br/>
2- How to remove the branches remotely:
    - git push origin :branch-name
<br/>
3- How to checkout to another branch without commit changes:
    - Stash the current changes using: git stash
    - Switch to the other branch
    - After you return to the main branch you can stash pop these changes: git stash pop
<br/>
4- How to list tags:
    - git tag
<br/>
5- How to remove the tag locally:
    - git tag -d "tag-name"
<br/>
6- How to remove the tag remotely:
    - git push origin :tag-name
<br/>
<img src="GIT.jpg"/>