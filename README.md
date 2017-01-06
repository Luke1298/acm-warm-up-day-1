# ACM Warm Up Day One
## What is a Warm up?
We will use warm ups in this class to review algorithm(s) that should already be familiar to us. Depending on the day Warm ups can take anywhere from 5 to 30 minutes and may include one to many different algorithms to implement.
Each day if anything important needs to be conveyed (specifically about the warm up) that information can be found in this file (README.md) and will likely be discussed in class as well.

## Rule's of the Warm up
**Warm up's are closed notes, closed friend, and closed internet (unless a link is provided for you)**

**You may not use awesome packages (like Numpy or Scipy) in Warmups. (Use math: eg. "import math as m")**

**Please at very least attempt the warm-ups. They will be the medium for feedback in this Class**


#Newton's Method
If you aren't already familiar with newtons method you can find an overview of the algorithm here: https://en.wikipedia.org/wiki/Newton's\_method

In the file: "sol.py" You will find the following function:
```python
def Newtons_Method(func, func_prime, x_0, iters=100):
  """A direct implementation of Newton's Method
     (For sanity assume that func and func_prime define there own division correctly,
     that is, don't cast anything to a float)
     params: a function, its derivative and an initial guess (required)
             number of iterations to cap too (optional, default 100)
     returns: a root(int) if found
              None(none-type) else
  """
  pass
```

Your job is to simply fill in "pass" with the appropriate iterative solution (which stops after 100 iterations and returns `None` is the solution is not found).
