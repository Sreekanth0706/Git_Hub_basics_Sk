Git Undoing


If we did git add by mistake, we can do git reset to undo the changes

Git log are way to track all the commits. Each commit come with a hash value (or commit ID)

git reset fd2d2be142cb9447936bcb2a723d24cbe67c6a62(demo hash value) to unstage the previous changes

git reset --hard fd2d2be142cb9447936bcb2a723d24cbe67c6a62(demo hash value) to undo the changes before one commit and the previous changes will be completely removed (use the right hash value)