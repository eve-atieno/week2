**SNEK PEAK OF WHAT WE DID IN THE LAST CLASS**

We learnt about Javascript data types, and we looke at the few data types Javascript has:

## JAVASCRIPT STRING DATA TYPE

String is one of Javascript data types, it is used to represent text or sequences of characters.
Strings are one of the primitive data types in Javascript, and they are typically enclosed in either
a single (' '), double (" "), or backtick (` `) quotes.

So here are some key characteristics of Javascript String data type:

1. Text representation: Javascript string data type is used to represent plain text as a data. which can be letters, numbers, symbols, and special characters as long as they are all enclosed with a quotation mark single(''), double(" "), or backtick(` `). We will look at backticks(` `) and dive deeper into it later in the course.

code example: 
const firstname = 'kennedy'; //using single quotes here
const lastname = "chukwu"; //using double quotes here;
const email = `mrchukwusinbox@gmail.com` //using backtick quotation sign here, we will look into backticks more.

you can print these out with console.log(variable_name) and see what it will give you:
 console.log(firstname)
 console.log(lastname)
 console.log(email)


2. JavaScript string data types are Immutable:
This means that once a string is created, you can not change it's individual characters.

3. We will look at Concatenation:
Concatenations means combining two string (Joining two strings togethere), and this is done using the plus (+) sign operator(we will look at plus(+) sign operator later in the course). We are going to be using it alot with strings.

code example: using the previous variables created up:

const fullname = firstname + lastname // result will be kennedychukwu. so let edit it a little down.

comment the previous code and re-type it again:
const fullname = firstname + " " + lastname // result will be kennedy chukwu.

this " " is a string, but an empty string and creating space in-between "  ", adds a space in our string result. So that is what separated the 'firstname' vlaue and 'lastname' value, when printed to the terminal.

## JAVSCRIPT NUMBER DATA TYPE

We talked about numbers. Numbers are Javascript data type, it is used to represent a number value in javascript.

code example:
const age = 28; // here the age variable is holding(or storing) 28 as an age.

*NOTE:* Once you wrap '28',"28", or `28` with any of the String symbol. You have turned the number to a string.

TO CHECK THE TYPE OF DATA STORE IN AGE VARIABLE OF ANY VARIABLE: use the typeof operator

type this and print to the terminal: console.log(typeof age) //result printed will be: number


## JAVASCRIPT BOOLEAN DATA TYPE

Hey okay we are not booing some footballer that missed a goal, or booing one wicked lady in BoolyWood movie.. lol we are talking about Boolean it B O O L E A N..lol okay i see a boo in it. Booleans just have two values, true or fale.

TWO VALUES ONLY : true or false. Booleans values are written in small letters and are not wrapped with quotation symbols, I repaeat they are not wrapped with quotaion symbools that ' ', " " or ` `.

const isItCorrect = 'true' // Boooooo you wrapped it with quotation symbol... comment this out.

let's code it again

const isItCorrect = true //YESSSSSSSS, KUDOS your honest and I like that, I know you can have some false too..

YESSSSSSS WE DID IT, we did it the right wayyyyyyy

Booleans are either true or false. Just that


## CREATING VARIABLES

*Principle of creating legal variable. I REPEAT PRINCIPLES OF CREATING LEGAL VARIABLES. if you create illegal varible you will be JAILED ')'. lol dont mind me..*

Okay lets look out the required ways of creating variables.

What are variables: Variables are containers we use in storing any type of data in Javascript. 

*little anology*
Lets say we are backing to go back to school, and we need to carry our books carefully, so that they dont get damaged or roughed up. We carefully back them in a carton, to easily carry it back to school. So see going back to school as a process of Javascript progra written. Preparing to go back to school and packing our books inside a carton we created a variable and added value to it.

*check this out:* const carton = "my books"

So any were we carry our carton, taking it to the car, putting at the car truck, driving it to school, carrying it to my hostel(DOM). we are just carry our book. So once we unpack our carton, we get our book.

*So check this out again* console.log(carton) // printed result: my books.

You can see that our carton variable is used inside our Javascript program in the process of going back to school. All this time it was our books we were just carrying. 

Creating varible principle:

1. please never start with numbers, you can be lock up for it..lol dont mind me.Don't do the following

code example
const 419number = 419; //wrong, reuslt will be an error.
const 69position = 69; //wrong,

*ACCEPTED VARIABLE NAME, BUT BAD PRACTICE*
const $firtName = "Jane" // will not give error when printed, but bad practice.
const _lastname = 'Doe'// will not give error when printed, accepted, but please dont use this, except in some casses.

*GOOD AND HEALTHY VARIABLE HABIT*
const sentence = "Please create your variable this way";
const camelCaseVariable = 'this is a camel case variable written, vlaue is a string wrapped with single quote';
const PascalCaseVariable = "the pacal case variable, all firstname are capital letter.";

*PASCAL TALKING* please  use camel more, it will take you on a longer journey, and it's the best way to create a variable. Trust me. You will use my type of creating variables letter in the course.

*CAMEL* You have heard PASCAL, ride with only me for now never forget the convetion of the journey: variableName


*"I can see the smile of okay I get it now, on your face'*

Please we will stop here to consume this little piece of information properly and continue next class. Practice, practice, write a lot of code creaing different Javascript data type and printing them out to the terminal (console), using console.log() and also check the data types using typeof.




# ASSIGNMENT
Please follow insructions.
create the variables
print out your values.

1. Create a variable firstname, lastname and email, given it the value of string.Your fristname, lastname and email address.
2. Create a variable of number given it the value of your age.
3. Create a variable iAmLearningJavaScript and give it a boolean value of true.

Advanced question, please do attempt them, make research and solve it.

4. Create a variable name called sentence and assign it a value of the concatenation of the other variables, making a sentence with it. 
*hint:* "My name is Kennedy Chukwu, I am 15 years old and it's true am learning Javascript".

HAPPY CODING......
