# lifeInWeeks-with-javascript
var age = prompt("Please enter your age here.")
function lifeInWeeks(age) {

var years = 90 - age;
var x = years * 365;
var y = years * 52;
var z = years * 12;
  
console.log("You have "+ x + " days, " + y + " weeks, and " + z + " months" + " left.");
