var num1 = prompt("What's the first number?");
var num2 = prompt("What's the second number?"); 
var choice = prompt("Now, what do you want to do with these numbers?");


if(choice.includes("sum")){
console.log(num1+num2);
}   else if(choice.includes("minus")){
console.log(num1-num2);
}   else if(choice.includes("multiply")){
console.log(num1+num2);
}   else if(choice.includes("divide")){
console.log(num1*1.0/num2)
}
