# Programming with Javascript

## Functions

+ function mySum(){
    let x = 2 + 2;
}
**function keyword/function name/()parameters/{}body**

mysum()
**function delclaration**

+ const myFunction = function(){
    let y = 3 * 3;
}
**function expression**

mySum();
**calling the above function**

## Parameters and Arguements

function bestSum(parameter1, parameter2){
let z = parameter1 + parameter2
}

bestSum(10,20);
**calls the above function, substituting parameter1 and parameter2 for 10 and 20**

bestSum("My name is ","Joe");
bestSum("I am ",37);
**More examples**

In HTML <script> embeds client side javascript

if
**if operator**

&&
**and operator**

||
**or operator**

## Arrays

+ **For loop**  
let myPets = ["dog", "cat", "rat"]  
for (**initialisation/condition/increment**){}  
for (let i = 0; i < mypets.length; i++>){  
console.log("I love my pet " + myPets[i])  
}  
**dog is 0 in the array, sat is 2 and rat is 3**  
**i++ increases i by 1**  
i < mypets.length **checks the length of i**  
[i] **refers to the i position in the array**  
  
+ **While loop**  
while(**condition**){  
    **statement**  
}  

let n = 0  
let x = 0  

while(n < 3){  
    n++  
    x +=n;  
    console.log(n);  
    console.log(x);  
}  

if (x < 3) {  
    **break**;  
}  
**will end the script upon condition being met**  