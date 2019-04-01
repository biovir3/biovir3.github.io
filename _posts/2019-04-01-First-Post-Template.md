---
layout: post
title: For Loops to List Comprehensions in Python
subtitle: Part 1
tags: [python for list]
comments: true
---

## Last week I had a problem that involved for loops, I wanted to shorten the code.

  The problem was I had this long code, that I felt like shortening.

  So I won't go through the whole issue, I will just shorten it down to a few key points.
  
Here is a simple for loops

~~~
for x in example_list:
  print(x)
~~~

This can be rewritten as

~~~
[print(x) for x in example_list ]
~~~

If you have more than one line of code in the for loop, we might want to look at putting that code into a function in order to simplify the 
problem.

ex.
~~~
[myFunc(x) for x in example_list]
~~~

This will execute the myFunc function for every value in the example_list.

We can also have list comprehensions in list comprehensions.


But to sum up my point for this.

  - First write the for loop
  - Second put the square brackets [] on a new line.
  - Third put what is inside the for loop at the beginning of the list comprehension as shown above.
  - Third write your for loop statement with out the Colon at the end, but inside the brackets..
  - Fourth comment out your for loop and test it out.

As always things may get buggy, and if it doesn't work properly, comment out the list comprehension, and uncomment your for loop until 
you debug the issue.

I will be adding more on this subject later.

