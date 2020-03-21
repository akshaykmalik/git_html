$ git show v1.0

commit 303c71e49ebadbaa4907be7a870583b3131618c9 (tag: v1.0)
Author: akshaykmalik <akshaymalik2411@gmail.com>
Date:   Sat Mar 21 11:39:33 2020 +0530

    initial commit

diff --git a/index.html b/index.html
new file mode 100644
index 0000000..c658748
--- /dev/null
+++ b/index.html
@@ -0,0 +1,7 @@
+<html>
+<head>
+<title>hi everyone</title>
+<body>
+<h6><b><i> HEY GUYS</h6><b></i>
+</body>
+</html>
\ No newline at end of file
 -----------------------------------------------------
$ git show v1.1

commit b84b4d447dd0ca4c4fffe3faa068813e3fac7b98 (tag: v1.1, origin/newBranch, newBranch)
Author: akshaykmalik <akshaymalik2411@gmail.com>
Date:   Sat Mar 21 11:42:41 2020 +0530

    hi guys changed to newBranch guys

diff --git a/index.html b/index.html
index c658748..e83a527 100644
--- a/index.html
+++ b/index.html
@@ -2,6 +2,6 @@
 <head>
 <title>hi everyone</title>
 <body>
-<h6><b><i> HEY GUYS</h6><b></i>
+<h6><b><i> newBranch GUYS</h6><b></i>
 </body>
 </html>
\ No newline at end of file
---------------------------------------------------------
 git show v1.2
commit e24439789823d20e16da3cc3c9ac2b283396e14f (HEAD -> master, tag: v1.2, origin/master)
Merge: fbfbfd4 b84b4d4
Author: akshaykmalik <akshaymalik2411@gmail.com>
Date:   Sat Mar 21 12:09:43 2020 +0530

    final merge

diff --cc index.html
index 28cd76c,e83a527..65b1b69
--- a/index.html
+++ b/index.html
@@@ -2,6 -2,6 +2,8 @@@
  <head>
  <title>hi everyone</title>
  <body>
- <h6><b><i> MASTER CHANGED GUYS</h6><b></i>
 -<h6><b><i> newBranch GUYS</h6><b></i>
++
++<h6><b><i> mixed MASTER CHANGED GUYS &&  newBranch GUYS</h6><b></i>
++
  </body>
  </html>
