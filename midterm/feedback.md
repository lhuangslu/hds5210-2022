# Notes on the Midterm

* _Correctness    (out of 40):_ 40
* _Good Practices (out of 10):_ 9
* _Docs / Testing (out of 10):_ 10

_Details on the grading criteria for the midterm can be found on [Canvas](https://canvas.slu.edu/courses/28045/rubrics/23671)._

For the total of all the small comments below, I deducted 1 point from _Good Practices_.

Nice job overall!


## Step 1
* Python **will** nicely close open files when the function exists successfully, but it's better to use the `with` syntax or explicitly close files that you open.

## Step 2
* Please use variable names that describe what the variables are. `a`, `b`, `c` aren't very descriptive.
* Instead of reading the entire file into a list, you could just do the the billing/service code comparisons while you're reading the file.

## Step 3
* Nicely done. No additional comments.

## Step 4
* You had to repeat things like `line[6][:7]` several times. Better to put those into a variable and then use the variable names. It will make your code easier to read and understand.
