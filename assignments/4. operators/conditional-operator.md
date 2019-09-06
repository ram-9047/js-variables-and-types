## If Statement
1.  🎖Make a simple calculator with these functions. Using prompt, type conversion, if else statement. Use prompt to take the input from user i.e two numbers and an operation (Add, Sub, Mul, Div).

  ⛑ Rule
    * [ ] While substracting and dividing keep in mind the number one should be greater then number two. If not show alert saying `Number Two is larger then Number one`.
  ⚡️ Operations
    * [ ] Add
    * [ ] Sub
    * [ ] Mul
    * [ ] Div

	let finalResult;
	let firstNumber = prompt("enter first value");
	let secondNumber = prompt("enter second value");
	let operator = prompt("what do you want to do");
	if (operator == "add"){
		finalResult = (+firstNumber) + (+secondNumber) ;
		alert(finalResult)
	}
	if (operator == "subtract") {
		if (firstNumber > secondNumber) {
			finalResult = firstNumber - secondNumber ;
			alert(finalResult)
		}
		else{
			alert("firstNumber is smaller than secondNumber")
		}
	}
	if (operator == "multiply") {
		finalResult = firstNumber * secondNumber ;
		alert(finalResult)
	}
	if (operator == "division") {
		if (firstNumber > secondNumber) {
			finalResult = firstNumber/secondNumber ;
			alert(finalResult)
		}
		else{
			alert("numerator is smaller than denominator")
		}
	}


2. 🎖Write a if else statement which checks if the status is single `console.log` the message `John is single` or else `John is married`
```js
var firstName = 'John';
var status = 'single';
// Your code goes here
if (status == 'single'){
	alert("john is single")
}
	else{
		alert("john is married")
	}
```

3. 🎖Write a JavaScript program that takes two `integers` from user (using prompt) and alerts the larger number.
```js
// your code goes here
let firstInteger = prompt("enter any number")
let secondInteger = prompt("enter another number")
if(firstInteger > secondInteger){
	alert(firstInteger)
}
	else{
		alert(secondInteger)
	}
```

4. 🎖Write a JavaScript conditional statement to find the sign (+, -) of product of three numbers. Take those three numbers from user using `prompt`. Display an alert box with the specified sign.

```js
// Your code goes here
var firstNumber = +prompt("first number")
var secondNumber = +prompt("second number")
var thirdNumber = +prompt("third number")
var result = firstNumber * secondNumber * thirdNumber;
if (d>0){
	alert(`+`+ d)
}
else{
	alert(d)
}
```

## Switch Statement

1. 🎖Using switch statement do the following

Take a number value from user and alert the message if it matches the conditions.
* [ ] ONE, if `number` is equal to 1.
* [ ] TWO, if `number` is equal to 2.
* [ ] THREE, if `number` is equal to 3.
* [ ] FOUR, if `number` is equal to 4.
* [ ] FIVE, if `number` is equal to 5.
* [ ] SIX, if `number` is equal to 6.
* [ ] SEVEN, if `number` is equal to 7.
* [ ] EIGHT, if `number` is equal to 8.
* [ ] NINE, if `number` is equal to 9.
* [ ] PLEASE TRY AGAIN, if  is none of the above.
```js
// Your code goes here
let a = +prompt("enter any number")
switch (a){
	case 1:
	alert("ONE")
	break
	case 2:
	alert("TWO")
	break
	case 3:
	alert("THREE")
	break
	case 4:
	alert("FOUR")
	break
	case 5:
	alert("FIVE")
	break
	case 6:
	alert("SIX")
	break
	case 7:
	alert("SEVEN")
	break
	case 8:
	alert("EIGHT")
	break
	case 9:
	alert("NINE")
	break
	default:
	alert("Input number is out of range")
}
```

2. 🎖Using switch statement do the following

Take the value of `marks` (0-100) from user using `prompt` and `alert` the message (Your Grade is AA) as giver below.
* [ ] `AA` if `marks` is greater than 90.
* [ ] `AB` if `marks` is greater than 80 and less than or equal to 90
* [ ] `BB` if `marks` is greater than 70 and less than or equal to 80
* [ ] `BC` if `marks` is greater than 60 and less than or equal to 70
* [ ] `CC` if `marks` is greater than 50 and less than or equal to 60
* [ ] `CD` if `marks` is greater than 40 and less than or equal to 50
* [ ] `DD` if `marks` is greater than 30 and less than or equal to 40
* [ ] `FF` if `marks` is less than or equal to 30
```js
// Your code goes here
let a = prompt("enter any number")
switch (true){
	case (a > 90):
	alert("AA")
	break
	case (90 >= a , a > 80):
	alert("AB")
	break
	case (80 >= a , a > 70):
	alert("BB")
	break
	case (70 >= a , a > 60):
	alert("BC")
	break
	case (60 >= a , a > 50):
	alert("CC")
	break
	case(50 >= a , a > 40):
	alert("CD")
	break
	case(40 >= a , a > 30):
	alert("DD")
	break
	case(a <= 30):
	alert("Fail")
	break
}
```
