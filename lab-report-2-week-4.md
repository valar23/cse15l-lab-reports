# Lab report for week 3-4
---
## First Code Change
* screenshot of the first code change
![Image1](1c.PNG)
* Here's [A Link to the test file](https://2680991462.github.io/cse15l-lab-reports/test-file9.md)
![Image1](1s.PNG)

* The code didn't consider the situation where the writer just want to use [] and () separately (Like the line in the test file).
* Therefore, From the screenshot above, we can see that it prints an output that are not supposed to be recognized as a Link ( there are words between "](" ).
* The bug that caused this symptom is not checking if there's extra space between "](" that could cause them not to be a link.

---

## Second Code Change
* screenshot of the second code change
![Image2](2c.PNG)
* Here's a [A Link to the test file](https://2680991462.github.io/cse15l-lab-reports/test-file10.md)
![Image2](2s.PNG)

* The code didn't consider the situation where the writer just want insert a image instead of a link (Like the line in the test file).
* Therefore, From the screenshot above, we can see that it prints an output that is a reference to an image, which should not be recognized as a Link.
* The bug that caused this symptom is not checking if there's a "!" in front of the first "[" that could change the line into a image instead of a link.

---
## Third code Change
* screenshot of the third code change
![Image3](3c.PNG)
* Here's a [A Link to the test file](https://2680991462.github.io/cse15l-lab-reports/test-file11.md)
![Image2](3s.PNG)

* The code didn't consider the situation when there's no link in this file at all (Like the line in the test file).
* Threfore, From the screenshot above, we can see that it caused a 'out of memory error'.
* The bug that caused this symptom is not checking if if the code can find the first OpenBracket
* when there's no Open Bracket, 'nextOpenBracket' will just be -1 and cause the while loop to run infinitely.

