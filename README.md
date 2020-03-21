$ git show v1.0
intial commit
<html>
<head>
<title>hi everyone</title>
<body>
<h6><b><i> HEY GUYS</h6><b></i>
</body>
</html>

 -----------------------------------------------------
$ git show v1.1

  hi guys changed to newBranch guys

 <head>
 <title>hi everyone</title>
 <body>
-<h6><b><i> HEY GUYS</h6><b></i>
+<h6><b><i> newBranch GUYS</h6><b></i>
 </body>
 </html>
     No newline at end of file
---------------------------------------------------------
 git show v1.2

  final merge
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
