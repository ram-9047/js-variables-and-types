# Logical Operator

1. 🥇What's the output of the following, write the output next to the code as comment.

* [ ] Logical AND operation

```js
true  && true; //true
true  && false;// false
false && true;// false
false && false;//false
"foo" && "bar";//"bar"
"bar" && "foo";// "foo"
"foo" && "";//""
""    && "foo";//"foo"
" "   && "John" && "" && false//""
false && "Hey" && undefined// false
"undefined" && false && 42// false
```

* [ ] Logical OR operation
```js
true  || true;// true
true  || false;//true
false || true;//true
false || false;//false
"foo" || "bar";//"foo"
"bar" || "foo";//"bar"
"foo" || "";//"foo"
""    || "foo";//""
" "   || "John" || "" || false//""
false || "Hey" || undefined//"hey"
"undefined" || false || 42//"undefined"
```

2. 🥈You have two variables i.e `isGuestOneVeg` and  `isGuestTwoVeg` according to the value using logical && and || opeartor do the following.

* [ ] If both are veg "Only offer up vegan dishes."
* [ ] At least one veg  "Make sure to offer up some vegan options."
* [ ] Else, "Offer up anything on the menu"
```js
let isGuestOneVeg = false;
let isGuestTwoVeg = false;
(isGuestOneVeg && isGuestTwoVeg && alert ("offer up anything on menu"))

let isGuestOneVeg = true;
let isGuestTwoVeg = true;
(isGuestOneVeg && isGuestTwoVeg && alert("only offer up vegan dishes"))

let isGuestOneVeg = false;
let isGuestTwoVeg = true;
(isguestOneVeg || isGuestTwoVeg && alert("make sure to offer up some vegan options."))

// Your code goes here
```


3. 🎖Using the variable `temperature` and logical operators do the following
* [ ] If temperature is less then 32 alert "It is freezing outside"
* [ ] If the temperature is greater then 110 alert "It is hot outside"
* [ ] else 'Go for it. It is pretty nice out'
```js
let temperature = 4;
// Your code goes here
let temp = +prompt("enter temp. ")
switch (true){
	case (temp < 32):
	alert("too cold");
	break
	case (temp > 110):
	alert("its too hot");
	break
	default:
	alert("go fo it ")
}

let a = prompt("enter any number")
if (a < 32) {
	alert("too cold")
} else if (a > 110) {
	alert("too hot")
} else{
	alert("moderate")
}

```

4. 🎖 Output of this and the reason behind the output.
```js
alert( alert(1) || 2 || alert(3) ); // 1 after that 2 . first compiler will compare "alert(1) and 2", out of which both are true value and OR operator will give first truthy value so compiler will give first value i.e "alert(1)". After that compiler will compare "2 || alert(3), and both the truthy values so compiler will give first truthy value"
```