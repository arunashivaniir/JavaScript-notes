
console.log(`Hello World`); -> ==prints the message in the console when page is inspected==

window.alert(`Welcome to my website`);-> ==Pop up alert on the website screen==

document.getElementById("H1m").textContent = "Hello!!";
|
|
->from h1 id = H1m in index.html

**VARIABLES**
declaration       let x;
assignment       x=100;

==const==-->a variable's value cant be changed.
(for const variable name should be in caps-->for number and boolean)
when value is changed-->uncaught type error

**ARITHMETIC Operator Precedence**
1.Paranthesis
2.exponents
3.multiplication,division,modulo (left to right)
4.addition n subtraction

window.prompt()-->==to get user input from a pop up window==

document.getElementById("mybutton").onclick=function(){
username=document.getElementById("mytext").value;
consolw.log(username)
}----->==to get the input using the button on click==

let age-window.prompt("enter age");
age=Number(age)---->==type conversion from string to int (type cast)==

let x="pizza"
x=Number(x);
console.log(x, typeof x)----->O/p: ==NaN 'number' (NaN->Not a Number)==

==Math==-->built-in object that provides a collection of properties and methods

Math.round()--->3.99 = 3, 3.11=3
Math.floor(x)---> rounds down
Math.ceil(x)----->rounds up
Math.trunc(x)--->3.21=3
Math.pow(x,y)-->2^2=4
Math.sqrt(x);---->9=3
Math.log(x------> logarithm
Math.sin(x)------>sine function
Math.cos(x)------>cosine function
Math.abs(x)------>negative sign elimination
Math.sign(x)----->-45=-1
let max=Math.max(x,y,z), console.log(max);----> same for min
Math.random()----->gives a num between 0 and 1
