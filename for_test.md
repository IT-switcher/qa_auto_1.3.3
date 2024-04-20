## Some info about git commands

first of all, I'd like to share this useful log command, which can help you see the log graphically:

`git log --pretty=format:"%h - %an : %s" --graph`

where "h" is hash of the commit, "an" - autor of this commit and "s" is commit text

*and modification, if you need only recent changes:*

`git log --pretty=format:"%h - %an : %s" --graph --since="2024-04-04"`

---

and second one - if you merging new branch to main and there is no edits in the main branch, this command will safe the main branch from future collaps with new changes:

`git merge --no-ff`

![picture of difference](https://nvie.com/img/merge-without-ff@2x.png)