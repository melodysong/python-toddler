# python-toddler

When you type in Python in search engines, we get too many links to click on. Hence, I’ve decided to share my steps studying Python with the public. This study guide is intended for people who have experience with other programming language. I, myself, have Native-C experience, and I was struggling to bring my Python skill up to speed. Please feel free to share if you have any suggestions on better ways to help others fall in love with Python. Giving all credits to @htkim for providing guidance. 

If you’re a person who always wonders “why?” and “philosophy” behind Python, http://www.python-course.eu/python3_history_and_philosophy.php

---

## [Steps to Study for Python Toddlers] ##


1. [HackerRank](https://www.hackerrank.com/domains/python/py-introduction):

   Get used to the built-in libraries from HackerRank.
   Yes, I know. These look too easy, but hey, let’s not forget to get back to the basics.


2. [LeetCode](https://leetcode.com/problemset/algorithms/):

   Solving few algorithm problems using Python allowed me to notice my Native-C coding-style existing in my Python code. Reviewing other users’ Python code drastically helped me accept I suck at Python. So, let’s keep studying and practicing more.
   From my experience, the best impact was from comparing your code with your Python study-mate. Gosh, it does feel horrible to get kicked my ass by my friends, but it’s very fun. 
   Please feel free to pay to get access to locked problems. 


3. DeepDive into Demystifying…

    As a Native-C person, I wonder how Python compiles. Maybe I shouldn’t have taken “Compiler” class. I started wondering on the outputs of below:

```python
    In [1]: x = [1, 2, 1]

    In [2]: x == x[::-1]

    Out[2]: True

    In [3]: x == reversed(x)

    Out[3]: False

    In [4]: x == list(reversed(x))

    Out[4]: True
```

    Of course, knowing generator helps the difference between `reversed(x)` and `list(reversed(x))`. However, I'll upload what we played around with to practice. 



