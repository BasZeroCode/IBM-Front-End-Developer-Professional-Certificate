## Graded Quiz Week 4

### Question 1

In the following declaration, what is the type of the variable 'pi'?

var pi = "3.14"; 

- [x] string
- [ ] char
- [ ] number
- [ ] float
      
Variables in JavaScript assume the data type from the value when it’s assigned. In this case, pi is the same type as "3.14," which is a string.

### Question 2

How do you define an array called array1 in JavaScript?

- [ ] var array1 = (1,2,3)
- [ ] var array1 = new Array[1,2,3]
- [x] var array1 = [1,2,3]
- [ ] var array1 = new Array((1,2,3))

### Question 3

What does the following statement do?

var ndate = new Date();

- [ ] Returns an error
- [x] Assigns the current local time to ndate
- [ ] Assigns an empty string with the properties of dates to ndate
- [ ] Assigns an empty string with the properties of dates to ndate

Providing no arguments to the Date constructor returns the current local time based on your system settings. 
 
### Question 4

Which DOM function returns a node object matching a div with an id value "example_id"?

- [x] document.getElementById("example_id")
- [ ] document.getElementById(div, "example_id")
- [ ] div.getValueOf("example_id")
- [ ] element.getNodeById("example_id")

To get an object given a specified id, the document.getElementById() method should be used. This looks for a specific id and does not differentiate between different tags. 

### Question 5

How are numbers converted to strings?

- [ ] string(123)
- [x] (123).toString()
- [ ] toString(123)
- [ ] (123).string
      
Converting a value to a string requires calling the "toString" method on the object (in this case numbers) and providing no arguments. 

### Question 6

What is the value of 'total' after the following statement is executed?

var total = 10 + 1 +" 3";

- [ ] 1013
- [ ] 14
- [ ] This results in an error
- [x] 113

JavaScript will execute this statement in order. 10 and 1 are both numbers and will be added as such (10 + 1 = 11). Then, this new value (11) will be concatenated with the string "3", resulting in "113". 

### Question 7

What would the alert be when the following code is executed?

var a = new String("Hello");
var b = "Hello";
if (a === b) {
  alert("Same");
} else {
  alert("Different");
}

- [ ] Same
- [x] Different
- [ ] It would not give any alert as it is an error
- [ ] None of the above

The "===" operation checks if the operand on the left is of equal value and equal type to the operand on the right. Since Strings declared by the String wrapper object are different than the primitive string data type, a and b are different types, despite them having the same values.

### Question 8

Which of the following is the proper way to create a for loop?

- [ ] for (var i = minVal; i++; i < maxVal) { … }
- [ ] for (i < maxVal) { … }
- [x] for (var i = minVal; i < maxVal; i++) { … }
- [ ] loop (for i = minVal; i < maxVal; i++) { … }

A for loop requires 3 expressions within the parentheses: an initial expression, a conditional expression, and an increment expression. The expressions must appear in the order listed and must be separated by a semi-colon (;)

### Question 9

Select all of the following which are proper ways to add a color property to a custom Car object.

- [x] Modify the code of the Car object directly to add a color parameter in the constructor
- [ ] Car.prototype(Color, "Red")
- [ ] Car.color = "Red"
- [x] Car.prototype.color = "Re

Modifying the object code directly or adding a property to a prototype are proper ways to add a color property to a custom Car object. 

### Question 10

Which of the following is not an event binder in JavaScript?

- [x] onhover
- [ ] onclick
- [ ] onload
- [ ] onmouseover

onhover is not a valid event in JavaScript. A different event binder is used for when a user hovers over an element.
