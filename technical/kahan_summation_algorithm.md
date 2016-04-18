-----------------------------------------------------
Kahan Summation Algorithm

Date: 2016-04-13

-----------------------------------------------------

In numerical analysis, the **Kahan summation algorithm** (Also **compensate summation**) significantly reduces the 
_**numerical error**_ in the total obtained by adding a sequence of finite precision floating point numbers, compared to 
the obvious approach.

This is done by keeping a separate _**running compensation**_ (A variable to accumulate small errors).

* The default, numeric aggregate functions in PostgreSQL are insufficient for handling a large number of data points 
  due to floating point error.
