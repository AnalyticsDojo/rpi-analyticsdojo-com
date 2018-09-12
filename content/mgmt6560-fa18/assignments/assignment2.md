+++
title = "Assignment 2"
description = ""
weight = 2

+++


#### Assignment:
- More details on the homework assignment process can be found [here](/mgmt6560-sp18/assignments/). The button to accept the assignment is below.

{{< button href="https://classroom.github.com/a/nX3XBEEQ" >}} Accept the Assignment {{< /button >}}

Please turn in Lab02 as a pdf in the base directory of the repository.


## ISSUES

I mentioned this was my first time changing over to OKpy for these types of homework.

Two issues where identified thus far:

### You may get a conflict with matplotlib and gradememaybe

For lab.analyticsdojo.com you can temporarily uninstall matplotlib with:
```
!conda uninstall -y matplotlib
```

### You may get an error on HM02 q24.

The test is looking for 4.6 but you may get 4.5999999999999996. Reasons are here:
https://stackoverflow.com/questions/5997027/python-rounding-error-with-float-numbers
https://docs.oracle.com/cd/E19957-01/806-3568/ncg_goldberg.html
https://docs.python.org/3/tutorial/floatingpoint.html

I've updated the test for q24 to address this issue. You can replace the content of tests/q24.py with the value in this file:
[https://raw.githubusercontent.com/rpi-techfundamentals/hm-02-starter/master/tests/q24.py](https://raw.githubusercontent.com/rpi-techfundamentals/hm-02-starter/master/tests/q24.py)
