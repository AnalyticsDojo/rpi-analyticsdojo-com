+++
title = "Assignment 1"
description = ""
weight = 1
+++

#### Assignment:
- More details on the homework assignment process can be found [here](/mgmt6560-fa18/assignments/). The button to accept the assignment is below.
- You must include the initial lab as a pdf in the directory we did in class (lab01.ipynb). You can view the original [here](https://github.com/rpi-techfundamentals/fall2018-materials/blob/master/01-overview/03-exercise1/lab01.ipynb).

{{< button href="https://classroom.github.com/a/xYfj191e" >}} Accept the Assignment {{< /button >}}

Grading:
Grading will be done via the github repository.  Always ensure your changes have been pushed to the GitHub repository.

- 10 Points Complete HM01

- 10 Points lab01 PDF in repository.
_______________
20 Points Total

NOTE:  I've updated the original starter code to include a bit more of a walk through and fixed an error:
[https://github.com/rpi-techfundamentals/hm-01-starter/blob/master/hm01.ipynb](https://github.com/rpi-techfundamentals/hm-01-starter/blob/master/hm01.ipynb)

You are fine to do the original version. There is one small errror:

The code:
```
dfcsv = dfcsv.to_csv('out/nameiloc.csv')
```
Should be:
```
dfcsv.to_csv('out/nameiloc.csv')
```
(We aren't assigning or updating the value. We are just running a method.)
