# CSS Float Layout Bug

This repository demonstrates a common CSS bug related to unexpected parent container collapse when using floats.  The `bug.css` file contains the problematic code, and `bugSolution.css` offers a solution.

**Problem:**
The use of `float: left;` on divs can cause the parent container to collapse if not properly handled. This leads to unexpected layout behavior, particularly in terms of height.

**Solution:**
The solution involves using clearfix or flexbox to ensure the parent container correctly wraps around the floated elements.  See `bugSolution.css` for an example using clearfix.