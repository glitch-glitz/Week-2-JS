 Variables-- Containers for storing data for future retrieval

Rules
* Use camelCase
* Do not use keywords
* Js is case sensitive
* Always use const uncless the value might change. That's when to use let
* Const creates immutable variables
* Let creates mutable variables


* Datatypes -> Allow us rep real world data in 

* Numbers ->> 1 , 2 , 3 ,
* Strings ->> "" '' ``
* Symbols
* Boolean ->> True/False
* Null->> Intentionally omitted
* Undefined ->> Not assigned 
* Objects ->> Group of data, separeted by commas and sorrounded by curly brackets
* Arrays ->> List of things sorrounded by square brackets


* * String concatenation --- Joining one or more stings using the + operator
const name = "Peterson"
console.log(name +"Kanyua") return value will be "Peterson Kanyua"

* * String interpolation --> Inserting  values into strings
 console.log(`${firstName} ${lastName}) 

* * Boolean expression --> any expresion that evaluates o true/false

1. comparison -> (===, !==, ==, !=)
----->>> Strict operators compare value and datatypes

---->>> Loose compare values 
2. Logical ----bang operate
* * !, !!, &&, 

* Double bang (!!)
............converts datatypes to boolean
............shortcut to the boolean constructor 
* Bang operator (!)
------------returns the oposite 
* AND (&&) and OR (||)
------------Allow to combine boolean expressions

console.log(2 === 2 && 2 == "2" || (2!==3))-------------- this gives true

for AND every expression has to evaluate to true in order for the entire expression to be true

for the OR only one of the expressions need to be true for the entire expression to be true

3. Number (>, <, <=, >=)


* * -->> Statements 
...Selection (if, switch)
... Repetition (do/while, while)
