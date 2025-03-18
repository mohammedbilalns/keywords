# Typescript vs Javascript
## Advantages 
static typing , inteface , type inference , classes inheritance , enums , generics 
## disadvantages
longer compilation times , need of compilation , need of defining types when using some third party libraries 
# Types 
## Any 
dynamic type
## Never 
### never vs void 
## Builtin 
Number, string , boolean , void, null , undefined , Symbol , Object , never 
## User Defined 
### Array 
collection of same elements
#### ReadOnly arrays 

### Tuple 
Array with fixed number of elements whose types are known
### Enums 
Collection of related values that can be numeric or string values
#### Numeric enums 
#### String enums 
#### Heterogenous enums 
#### Const enums 
#### Ambient enums 
#### object vs enums
## Unions 
Union types are a  way to express a value that can be one of the several types.
## Literal Types 
literal types allow us to specify the exact value the variable can contain.
### String literal 
### Numerical literal 
### Combined literal 

# Type Annotation 
explicitly defined the types of variables, function parametres return values...
## annotation for functions 
## annotation for objects 

# Type Inference 
allows the compiler to automatically determine (infer) the type of a variable, function or expression based on their inital value or context 
## Function default parameter 
## Function return type 
## Best Common Type 
## Contextual Typing 
## Inference in objects 

# Duck Typing 
two objects are considered to be of the same type if both share the same set of properties. Duck-typing verifies the presence of certain properties in the objects, rather than their actual type, to check their suitability. 
# Type Aliases 
 type aliases is a way to define a type. It allows you to give a specific name to the type or define a custom type using the 'type' keyword.
## Primitive type aliases 
## Union type aliases 
## Tuple type aliases 
## Type alias with generics 


# Functions 
## Optional Parameters 
Optional parameters can be used when arguments need not be compulsorily passed for a function’s execution
## Default parameters 
## anonymous functions 
## lambda functions lambda statements 
## Function overloading 
mechanism in which program can have multiple methods with the smae name with different implementation 

# Interface 
allows to define the structure of the object but doesn't provide the implementation
## Interface inheritance 

# Classes 
## constructor 
## Inheritance 
Inheritance is the ability of a program to create new classes from an existing class. 
## Method overriding 
## super
## static keyword 
used to reperesent the properties of class rather than the instances
## instanceof
## Data hiding / encapsulation 
## classes and interfaces
## Objects 
## Access modifiers 
used to implement encapsulation or data hiding in TypeScript. The access modifiers define the visibility class members outside the defining class.
## Static 
# ReadOnly 
## Readonly with interface 
## Readonly with classes 
## Readonly with type aliases 
## Const vs readonly
# Abstract classes
## Abstract classes vs interfaces 
abstract class can have non abstract properties and methods , interface can have multiple inheritance , abstract class suport access modifiers 
## Implements vs extends
implements - for creating classes that follws structure of interfaces or abstract classes , does not inherit concrete methods from abstract classes 
extends - used to inherit from abstract or non abstract classes , 
# Accessers 
## Getters
used to access the values of class members and manage how those are accessed outside 
## Setters 
used to set the value of class members without accesing them outside of the class 
# Class vs Interface 
class - blueprint of objects - can contain properties methods which can be accessed using an instance of classes 
interface - It allows to define the structure of the object but doesnt provide the implementation
# Intersection 
it is a way to combine multiple types into a single one . the resulting types have all the properies

# type guards 
allow us to get the type of variables. After that, we can perform multiple operations based on the type of the particular variables
## Type Narrowing 
## typeof 
## instanceof 
## In 
# Type assertion 
# Union 



# Enums 
named constants 
# Generics 
reusable components , function codes or classes that can work with different types rather than working with specific types 
# Union 
allows to declare the multiple types for variables 
# Type Assertion 
allows to change a variable from one type to another
# Type Inference 
allows to determine the type of variable functino or expression based on its usage or its initial value
# Variable scope 
class , local , global 

# Basics 
## String interpolation 
it is a way to embed expressions in between strings using template literals 
## Deeply nested objects 
object that contains multiple levels of nested objects. 
