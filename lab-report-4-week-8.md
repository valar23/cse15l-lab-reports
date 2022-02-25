# Lab report for week 7-8

---
## Link to index
[Link to other lab report](https://2680991462.github.io/cse15l-lab-reports/index)

---
## Link to the method
[My markdown-parse repository](https://github.com/2680991462/markdown-parse-old)
[reviewed markdown-parse repository](https://github.com/m1ma0314/markdown-parse)

---
## Preview of the Snippet
![Image1](p1.PNG)
* The screenshot above is the preview of snippet 1. 
* Based on the result, it should produce the link "`google.com"
![Image1](p2.PNG)
* The screenshot above is the preview of snippet 2. 
* Based on the result, it should produce links "a.com", "a.com(())", "example.com".
![Image1](p3.PNG)
* The screenshot above is the preview of snippet 3. 
* Based on the result, it should produce the link "https://ucsd-cse15l-w22.github.io/"

---
## Test code
![Image1](t1.jpg)
![Image1](t2.jpg)
* The screenshot above is the code I used to test the three snippet.
* I created 3 tests and 1 make file to use on my markdownparse and the reviewed ones.

---
## My implementation
![Image1](o1.jpg)
![Image1](o2.jpg)
* The screenshot above is the output after I typed `make Test` using my own markdownparse
* The output shows that all three tests failed 
* The line `expected:<['google.com> but was:<[url].com>` shows that my test case 1 failed
* The line `expected:<[a.com(([))]))> but was:<a.com(([]))>` shows that my test case 2 failed`
* The line `expected:<[http://ucsd-cse15l-w22.github.io/]> but was:<[https://twitter.com]` shows that my test case 3 failed


---
## reviewed implementation
![Image1](o3.jpg)
![Image1](o4.jpg)
* The screenshot above is the output after I typed `make Test` using the reviewed markdownparse
* The output shows that all three tests failed 
* The line `expected:<['google.com> but was:<[url].com>` shows that my test case 1 failed
* The line `expected:<[a.com(([))]))> but was:<a.com(([]))>` shows that my test case 2 failed`
* The line `expected:<[http://ucsd-cse15l-w22.github.io/]> but was:<end of array>` shows that my test case 3 failed

---
## Answer to the Question
1. Yes, I believe there's way to ignore the inline code with backticks. I can write to check if there's a 



