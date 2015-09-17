# Git Steps
### CSCI 5828 – Fall 2015
### Homework 2
### Team: Matt Bubernak

1. git init 
2. git add file1.txt
3. git commit -m “initial commit” [COMMIT 0, MASTER]
4. git add file1.py
5. git commit -m “updated file 1” [COMMIT 1, MASTER]
6. git add file1.txt
7. git commit -m “updated file 1 second time” [COMMIT 2, MASTER]
8. git log (listed all the branch id’s
9. git checkout 66e46ba36b48cb7d07daaa755053455246e61d27
10. git checkout -b “bug-fix” (created a new branch)
11. git add file1.txt
12. git commit -m “3rd commit” [COMMIT 3, BUG-FIX]
13. git add file1.txt
14. git commit -m “4th commit” [COMMIT 4, BUG-FIX]
15. git merge master
16. git add file1.txt
17. git commit -m “commit #5, merged with master and added line” [COMMIT 5, BUG-FIX]
18. git add file1.txt
19. git commit -m “commit #6” [COMMIT 6, BUG-FIX]
20. git checkout 0f9fcf2e693b98f45ba2d3103b4ea760484cc583
21. git checkout -b "bug-fix-experimental"
22. git add file1.txt
23. git commit -m “commit #7 from bug-fix-experimental” [COMMIT 7, BUG-FIX-EXP]
24. git add file1.txt
25. git commit -m “commit #8” [COMMIT 8, BUG-FIX-EXP]
26. git add file1.txt
27. git commit -m “commit #9” [COMMIT 9, BUG-FIX-EXP]
28. git checkout master
29. git add file1.txt
30. git commit -m “commit #10” [COMMIT 7, MASTER]
31. git checkout bug-fix
32. git merge bug-fix-experimental
33. git add file1.txt
34. git commit -m “commit 11 merged with bug-fix-experimental” [COMMIT 11, BUG-FIX]
35. git add file1.txt
36. git commit -m “commit #12” [COMMIT 12, BUG-FIX]
37. git checkout master
38. git merge bug-fix
39. git add file1.txt
40. git commit -m “commit #13 merged the files” [COMMIT 13, MASTER]
41. git add README.md
42. git commit -m “commit #14” [COMMIT 14, MASTER]