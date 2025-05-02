# What is 
High level , dynamically typed 
## characteristics 
interpreted , cross platform , single threaded , dynamic typing 
## Core features 
event driven programming , first class functions , prototype based object orientation , dom manipulation 
## Global execution context 
container where js executes 
### Variable environment 
phase where variables are stored as key value pirs 
### Thread of execution 
phase where code executes line by line 
## Call stack 
## Hoisting 
phenomenon where variabes and functons can be accessible before they are declared 
### TDZ

# Basics 
## Keyword and identifier   
keyword  are reserved words and identifiers are names given to variable func  class ...
## Dynamic and static typing
## Prmitive Datatypes 
single multiple , immutable
number, bigint , string , boolean , undefined , null , symbol 
### Number Methods 
toFixed, toString, isFinite
Math - abs , round , trunc, floor , ceil , random , max, min , pow , sqrt  
global - Number , parseInt , parseFloat , isNan , isFinite 

#### Number vs parseInt 
### BigInt 
numbers greater than  2^53-1 
### String Methods
- concat 
- charAt , at , charCodeAt 
- trim, trimStart , trimEnd 
- indexOf , lastIndexOf 
- replace ,replaceAll 
- toUpperCase, toLowerCase 
- startsWith , endsWith 
- includes
- subStr, substring, slice 
- split 
- repeat 
- codePointAt, fromCodePoint 
- repeat
### Boolean 
#### Truthy and Falsy values
falsey - null , undefined , NaN , empty string , 0
### Null vs undefined vs not defined 
## Non primitive Datatypes 
complex , object 
### Copy type and reference type
copied by value , copies by reference
### Object Methods(10)
- assign, structuredClone , create , fromEntries 
- keys, values , entries,
- freeze , seal
-  getPrototypeOf , setPrototypeOf, instanceof 
## Mutable immutable 
## let vs var vs const
scope , hoisting , initialisation 
## ES6 features 
let const declaration , arrow functino , template literals , desctructuring assignment , spread and rest , classes , promises 


### Escape sequences 
### Template literals 
## Symbol 
use cases - unique object keys , private properties 
## Array methods (14)
- map , reduce , filter, forEach  
- push , pop , shift , unshift ,
- slice , splice 
- from,  indexOf , includes, join , reverse , sort, every , findIndex, Array.from() , concat 
### forEach vs Map
### splice vs slice 

### Destructuring 
### Spread and Rest operators
iterable 
### Iterable vs Iterators 
#### Deep and Shallow Copy 
#### Constructor 
##### Constructor inheritance 
###### instanceof 
#### Class 
##### Class inheritance 
#### Optional Chaining 
#### Prototype 
##### Prototype inheritance
## Additional Data Structures 
### Map Methods 
set, get, has , size , looping, flatmap  
### Set Methods 
add, has, size , looping 
### WeakMap Methods 
set , get, has , delete 
### WeakSet Methods 
add, has , size 
## Type Conversion Type coercion 
## Operators 
### Logical operators 
|| , &&, ! 
### Nullish Coalescing operator
# Functions 
## Default parameters
## First class functions 
## Scope
### Global , local , block ,function scopes 
### Lexical environment 
### Scope chaining 
## What is Closure 
### Advantages and disadvantages of closure (3,3)
- advantages - Encapsulation and data hiding , memoization , currying , async programming, implementing debouncing and throttling  
- disadvantages - memmory consumption(delay in garbage collection ), perfomance overhead due to memmory duplication  
## Function expression 
## Arrow Functions 
No own this , cannot be used as a constructor , 
## Anonymous Functions 
## Callback and Higher Order Functions First Class functinos 
### Callback hell 
poor readability , complex error handling and debugging , reduced scalability 
## Pure and Impure Functions 
## Factory Functions 
## Currying 
### Advantages and disadvantages of currying 
- advantages - function composition, modularity , improved readability  
- disadvantages - complexity for beginners , perfomance overhead in some case 
## What is memoization  
## What is function binding 
### Difference between call apply and bind 
## Generator function
### Generator Object
### yield and next
## IIFE 
### Advantages 
### Disadvantages 
## this
# Asynchronous concepts 
## Promises 
### Promise chain 
### Promise States 
### Promise Methods 
all , race, any , allsettled 
### Starvation 
situation in which program blocks the main thread 
## Async await 
## Event loop 
## Timers 
### setTimeout vs setInterval 
## Queues 
# JSON
## Json Methods 
# DOM and BOM 
## Dom Methods 
## Bom Mehods 
## Events and lisners 
## Event propogation 
### Event delegation 
# Error handling 
## Try catch and finally 
## Types of errors 
syntax, type , reference , range errors , logical errors 
# Use Strict
prevent variable initialisation without declaration , disallow duplicate parameter names , prevent deletion of variables , some additional reserved words 
# Getters and setters 
methods that allows to control how properties of an object are accessed or modified 
# Short circuit evaluation 
feature of logical operators (&& and ||) in JavaScript where the evaluation of an expression stops as soon as the final result can be determined, without evaluating all operand
# Illegal shadowing 
 restriction that occurs when you attempt to declare a variable in an inner scope using var after the same variable has already been declared in an outer scope using let or const




- nullish assigning operator
- isArray 
- crossorigin in script 
- eval 
- object introspection -  process by which a program examines the type, structure, and properties of objects at runtime 


## Practical Questions 

- find second largest of an array using reduce 
- sort an array using reduce
- convert object into set and set into object 
- convert array into object 
