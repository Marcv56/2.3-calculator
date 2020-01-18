// JAVA is a CHALLANGE
console.log("hello world");

// JAVA SCRIPT DATA TYPES
// 1. Boolean

console.log(true)
console.log(false)
console.log (10>5)
console.log()
// thre are certain values  in JSthat evaluate to false- they are falsy
// *.undefined
// *.null
// *.+0, -0, n0
// *.false
// *.string of length 0 e.g. ""

// null
// represents an object that is not defined
// you can empty an object by setting it's value to null
// typ of null is object

// undefined
// represents a value that is not defined
// you can empty an object by setting it's value to null(both the value and type is undefined)

// number represnets a number that does not make sense
// console.log(typeof NaN);

// string
// 'cool'
// "cool"
// "That was 'cool'"
// 'echo' "Hello, World"
// "That was \"cool"\"

// JavaScript Variables
// declar a Variable
var name

// Assign a value to a Variable
name= 'Sammy'

// declar and assign a vaule to a variable in one line
var name = 'Sammy';

// Decalre and assign calues to multiple variables at the same time
var age=12, favoriteColor='pruple', name='Sally'

// varible naming
// firs character a-z, A-Z, $,_
// the other letters can be letters,numbers,$_
// variables are case sensitive
// The convention, but NOT! the rule is to capitalize each word after the first

// var
// decalares a varible, optionaly initializing its value
// subject to hosisting

// let
// decalares a block-scoped, local variable. optionaly initializing it's values
// not subject to hoisting

// const
// declares a block-scoped, read-only name constant
// not subject to hoisting

console.log(fruit);
var furit='apple'

var name;
console.log(name);

// EXPRESSIONS
// An expression is code that evalutes to a value
// value is an expression
//

// operators
// operators act on valutes to produrce new valutes

// arithmetic
// +,=,*,/

// Comparison
// ==,===,!=,!==,>,<,>=,<=
// loose(THEY COERECE TO TYPE)
// strict (DO NOT COERECE)

// LOGICAL
// logical NOT (!)
// logical OR (||)
// logical AND (&&)

// FUNCTIONS
// zero or more explicit parameters
// zero or more arguments
// exactly one return value,
// undefined by default(ending a function with return will return undefined)

//  FUNCTION DECLORTATION
// *****OLD WAY******
// 1. funtion keword
// 2. funtion name
// 3. parameter list(optional)
// 4. funtion body
funtion sum (num1, num2){
  return num1+num2
}
sum(2,4);

// FUNCTION EXPRESSION OLD WAY

var name = function (num1, num2) {
  return num1+num2;

}

// FAT ARROW FUNCTION SYNTAX
let sum= (num1, num2)=> num1+num2;
sum (5,9);
// Blue print for FATARROW
// **let myFunction= () => {}; **
*******************************************************************************
