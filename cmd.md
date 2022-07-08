C:\xampp\htdocs\test>git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.php

no changes added to commit (use "git add" and/or "git commit -a")

C:\xampp\htdocs\test>git add index.php

C:\xampp\htdocs\test>git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   index.php


C:\xampp\htdocs\test>git commit -m "change in index"
[main 4d4c44b] change in index
 1 file changed, 1 insertion(+), 1 deletion(-)

C:\xampp\htdocs\test>git push origin main
info: please complete authentication in your browser...
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 314 bytes | 314.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/radheymishra/test.git
   87cadf0..4d4c44b  main -> main