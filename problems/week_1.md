#Week 1 Warmups

##Problem 1: Swapping varialbles
Write a program that will swap the values of two variables. That is, if we start with
```js
x == "a"; //=> true
y == "b"; //=> true
```
once the program has finished running we will have
```js
x == "b"; //=> true
y == "a"; //=> true
```
*Note:* Think about why we cant just do something like `x=y` followed by `y=x`. What goes wrong when we try to do this?

####Example Solution

```
var a = "a";
var b = "b";

var swapAandB = function() {
  c = a;
  a = b;
  b = c;
}
```

##Problem 2: Reverse a String
Write a function `reverse` that takes in a string, and returns the reverse of the string. For example:
```js
reverse('Hello'); //=> returns "olleH"
```
*Note:* You cannot use any built-in array or string methods!

####Example Solution

```
var reverse = function(input) {
  var reversedString =  "";
  for (var i = 1; i < input.length + 1; i++) {
    reversedString += input[input.length - i];
  }
  return reversedString;
}
```

##Problem 3: Stacks and Queues
How would you store a List of people who were waiting in line?

####Example Solution

```
A Queue! 
```
