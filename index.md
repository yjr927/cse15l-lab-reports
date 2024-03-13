# Lab report 5
---
##Student's Post##
---
*Hi, I was looking back at the code from Wednesday's lecture and trying to 
run it myself. I ran with `bash grade.sh https://github.com/ucsd-cse15l-f22/list-methods-compile-error`,
but the output was not what I expected. The output looks like this:*
![image](00.jpg)
*Is there any reason for this?*




---
##Reply##
---
*Hi! This issue arises because your condition checks if the file`student/ListExamples.java`does not exist, instead of verifying its existence. The operator `!` introduces a logical error, resulting in incorrect output.*



---
##Student's Reply##
---
* Hi! Thank you! i have updated my code and it is working right now.*





