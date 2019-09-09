1. In code below "Mark" is a string.  What is name?
```js
var name = "Mark"; // name is Mark
```

2. Find the error if any
```js
  var product cost = 3.45; // yes. it should be like this - productCost
```

3. Write `Right or Wrong` next to the code below.

```js
  "Hello World" // Right
  'Hello World" // Wrong
  "Hello World'	//Wrong
  'Hello World' //Right
```

## Write `VALID` and `INVALID` infront of the variable name defined below
```js
var man; //valid
var 1girl; // invalid
var woman3; //invalid
var -girl; //invalid
var blackDog; //valid
var 42; //invalid
var $42; //invalid
var userName; //valid
var x, y, z; //valid
var x = 5, y = 6, z = 7; //valid
var x = 5 + 10 + 2; //valid
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, *, / , etc)

```js
var amount = 2080;
// Define a new variable and store the value that is 80 less then the value of amount.
var lessAmount = 2080 - 80;
// Define a new variable and store the value that is 200 more then the value of amount.
var moreAmount = 200 + amount;
// Define a new variable and store the value that is 4 times the value of amount.
var fourTimesAmount = 4*amount
// Define a new variable and store the reminder when the value of amount is  divided by 21.
var remainderAmount = 2080%21;
````

Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js
var johnAge = 45;
var markAge = 35;

// Check who is older eithe John or Mark
(johnAge < markAge) && alert("mark is older") || (johnAge > markAge) && alert(`john is older`)

// Check who is younger
(johnAge < markAge) && alert("john is youner") || (johnAge > markAge) && alert(`mark is younger`)

// Check if their age is equal
(johnAge == markAge) && alert("both age are same") || (johnAge !== markAge) alert("both have diff. age")

// Create a new variable and assign the age of john to new variable.
var newJohnAge = johnAge

// Check if john is equal to or greater then mark.
(johnAge > markAge) && alert("johnAge is greater") || (johnAge == markAge) && alert("johnAge = markAge")

// Check if john is less then or equal to mark.
(johnAge < markAge) && alert ("johnAge is less") || (johnAge == markAge) && alert("johnAge = markAge")

// Calculate the average age of john and mark and assign to a new variable.
```
var averageAge = (johnAge + markAge)/2;