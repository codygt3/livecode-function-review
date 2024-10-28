# livecode-function-review

Create a function named daysInMonth that is given an whole number (int) argument called month and returns a whole number (int) that represents the amount of days in that month.

```
var test1 = daysInMonth(1);
console.log(test1);   // should print 31. January has 31 days

var test2 = daysInMonth(2);
console.log(test2);   // should print 28. February has 28 days

var test3 = daysInMonth(9);
console.log(test3);   // should print 30. September has 30 days
```

Hint:

April, June, September, and November are the months with 30 days. For this function, February will have 28 days. All other months have 31.