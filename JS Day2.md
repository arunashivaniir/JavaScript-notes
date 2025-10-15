
IF statements- if a condition is true, execute some code

.==checked==-->property that determines the checked state of an HTML checkbox or radio button element.

(input type=checkbox or radio)
(label for = checkbox)-->in html

ternary operator---> shortcut for if() and else() statement
eg: ==age>=18 ? "you are an adult" : "You're a minor";==

switch statements-->replacement for 'n' no. of if-else statements
switch(true){
	case score>=90:
		console.log("Topper");
		break;
		.
		.
}

STRINGS:

let uname="arunashivaniir"
uname.charAt(2)--->u
uname.indexOf("u")-->2
uname.lastIndexOf("n")-->9
uname.length--->14
uname.trim()-->trims starting n trailing whitespaces
uname.toUpperCase();
uname.toLowerCase();
uname.startsWith(" ");--->checks whether if it starts with space
uname.endsWith(" ");---->checks whether if it ends with space
uname.replaceAll("i","u");-->replaces all i's to u's
uname.padStart(5, "a")--->pad the string to 5 characters and add a in the start if it's not 5 characters long
uname.padEnd(5, "a")--->pad the string to 5 characters and add a in the end if it's not 5 characters long

String Slicing

const fname="Arunashivanir"
let firstname=fname.slice(0,11)--->Arunashivani
let lastname=fname.slice(11,12)--->r

**METHOD CHAINING**
Calling 1 method after another in one continuous line of code

uname=uname.trim().charAt(0).toUpperCase() + uname.trim().slice(1).toLowerCase();

