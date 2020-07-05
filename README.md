# tree

## my workflow 

### usual case: just continue where I left off previously
- open Gramps, select correct Family Tree
- update data
- Export -> Gramps XML (Family Tree), unselect "Use Compression"
- overwrite my git-managed .gramps file
- git add, git commit, git push

### "start from scratch" eg. if I've edited a Family Tree on another machine
- (git clone,) git pull
- open Gramps, Delete the Family Tree
- create a new empty Family tree and import the git-managed .gramps file
- update data
- Export -> Gramps XML (Family Tree), unselect "Use Compression"
- overwrite my git-managed .gramps file
- git add, git commit, git push

### web site
- generate "Narrated Web Site" report into /docs
- git add, git commit, git push
- github copies it to https://dgm9704.github.io/tree/
