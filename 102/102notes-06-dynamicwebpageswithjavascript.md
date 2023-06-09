        # Dynamic Webpages with Javascript Notes  

---

**Camelcase = start lower case for the first worm/term then uppercase e.g.**
"myName"

console.log"lorem" (console.log(typeof ####) for defined variables)
**writes to the browser console**

**comments are written with two slashes e.g.**
this code is good  

## VARIABLES

+ var  
**not best used**  
+ let   
**can redifine later in code without having to type let**  
**can also use let but not define right away, can define later in code**  
+ const  
**defines a value that will be unchangable later in code**  

## Data Types (Values)

+ let myname =("Joe") this data type is a **string**

+ let age =(37) this data type is a **number**

+ **concatenating is linking together e.g.**
    let mydetails ="I am" + age;

+ let likesfood = true;  **this data type is a boolean**

## Arithmatic Operators

+ let addition = 7 + 7  
**for addition**

+ let subtraction = 5 - 2  
**for subtraction**

+ let multiplication = 5 * 2  
**for multiplication**

+ let division = 10 / 2  
**for division**

+ let mynum = 5  
let thisnum = ++mynum  
**increases number by one**

+ let mynum = 5  
let thisnum = --mynum  
**decreases number by one**

## Comparison Operators

+ ==  
**Equal to**

+ ===  
**Equal value AND equal type**

+ !=  
**Not equal to**

+ !==  
**not equal value and not equal type**

+ ">"  
**greater than**

+ <  
**less than**

+ ">="  
**greater than or equal to**

+ <=  
**less than or equal to**

## Conditional Statement  
**Controls whether a piece of code should run or not**  

+ if (mynum === 5) {  
    console.log("Bingo");
}  
**Prints if entered value ***strictly*** matches input (is true)**  
**The above comparison operators can be used**  

+ if (mynum === 5) {  
    console.log("Bingo");  
} else{  
    "That is not a bingo"   
}  
**Else will output if the first condition is false**  

+ if (mynum === 5) {    
    console.log("Bingo");  
} if else (mynum === 4); {  
    console.log("You are close");  
} else {  
    "That is not a bingo"  
}  
**Multiple conditions can be used as above**  

## Prompting

+ let userName = prompt("What is your name?");  
**creates a box that can be typed into that captures the user input and defines the variable to that input**  
**A prompt will interrupt loading of html code until the prompt is completed by a user? Something to test out**

## Alerting

+ const welcomeMsg = alert("Welcome to my website " + userName);  
**Shows a box without enterable fields**  
