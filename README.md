# CSharp Cheat Sheet Template

## Lingo
Keyword |                  Summary                   | Sample Code | Mentioned In
------- | ------------------------------------------ | ------------ | ------------
Script Execution Order | The order in which script is run and compiled. Generally left to right, top to bottom. | ? | ?
Formatting | The way in which the code is visually presented empasis must be kept on code readability. | ? | ?
Field | A type of data | `string TelephoneNumber;` | ?
Variable | A type of field | `var, int, string, bool etc.` | ?
Variable Initialization | When a value is assigned to a variable for the first time | `int a = 5;` | [Variables](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#variable-initialization)
Variable Declaration | Declaring a field | `int i;` | ?
Variable Assignment | Assigning a field a value | `int i = 0;` | ?
Uninitialized Variable | A field without a value | `int i;` | ?
Global Variable | Fields that have been declared outside of any functions and accessed by all other functions | `class Program { var imAccessibleToAll static void Main() { more code} }` | ?
Scope | Scope is the area of the program where an item (be it variable, constant, function, etc.) that has an identifier name is recognized. | ? | ?
Variable Scope | The location of which a field is being declared and can be accessed/used. | ? | ?
Operand | In computer programming, an operand is a term used to describe any object that is capable of being manipulated. | `1 + 2` the "1" and "2" are the operands and the plus symbol is the operator. | ?
Type Conversion | Changing one data type to another. | ? | ?
Primitive Data Type | Primitive data types are pre-defined. Data types like byte, int, short, float, long, char, bool, etc are called Primitive data types. | ? | ?
Non-Primitive Data Type | Non-primitive data types are user-defined. Non-primitive data types include class, enum, array, delegate, etc. | ? | ?
Implicit Casting | ? | ? | ?
Explicit Casting | ? | ? | ?
-------------------------------



## Basics
Keyword |                  Summary                   | Sample Code | Mentioned In
------- | ------------------------------------------ | ------------ | ------------
`;`     | Used to separate statements from each other. | `int i = 5; i++; Console.WriteLine(i);` | [Script Execution](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#0-script-execution)
`=` | Assignment Operator. Used to give a field a value. | `int i = 0;` | ?
`//`    | Used for single-line comments. | `float multiplier = 0.01f; // % to float (e.g. 24% = 0.24)` | [Comments](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#single-line-comments)
`/*/` | Multi-Line Comment. Used to make several lines of comments. | `/****/` | ?
`///` | XML Documentation Comment. Used to give summaries on your code as well as define your code to the reader (such as class, interface, or delegate) or its member (such as field, property, method, or event). | `/// this method adds two intergers` | ?
`static` | Class cannot can not be instantiated | you can not write `Math math = new Math();` | ?
-------------------------------




## Commands
Keyword |                  Summary                   | Sample Code | Mentioned In
------- | ------------------------------------------ | ------------ | ------------
`Console.WriteLine` | Used to print variable types, usually a string onto the console on a new line. | ? | ?
`Console.Write` | Used to print variable types, usually a string onto the console- note that this will not print on a new line. | ? | ?
`Console.ReadLine` | Used to read input from the console. Which can in turn be stored into a field. | `string name = Console.ReadLine;` | ?
`dotnet new console -o project-name` | Used within Command Prompt to create a new template C# Project Folder | ? | ?
`Convert.ToInt32` | Integer Type Conversion. Used to convert other types of fields into an interger | `int age = Convert.ToInt32(Console.ReadLine());` | ?
-------------------------------




## Fields
Keyword |                  Summary                   | Sample Code | Mentioned In
------- | ------------------------------------------ | ------------ | ------------
`int` | A type of field that is able to store a exact number between -2147483648..2147483647 | `int number = 1;` | ?
`double` | A type of field that is able to store a any number with decimals. 64 bits of size. | `double number = 1.567;` | ?
`float` | A type of field that stores an approximate number, that might be rounded up or down, including decimals. 32 bits of size. | `float number = 1.5` | ?
`bool` | A type of field that can store a true or false statement. | `bool isTired = true;` | ?
`char` | A type of field that stores a character. | `char a;` | ?
`string` | A type of field that stores an array of `char`'s or simple put text/ a sentence. Also called a String Literal. | `string text;` | ?
`byte` | ? | ? | ?
-------------------------------



## Operators
### Symbols used to read or write data.
Keyword |                  Summary                   | Sample Code | Mentioned In
------- | ------------------------------------------ | ------------ | ------------
Operators | Symbols used to read or write data. | ? | ?
Arithmetic Operators | The arithmetic operators perform addition, subtraction, multiplication, division, exponentiation, and modulus operations. | ? | ?
`+` | Addition. Adds the second operand to the first. | ? | ?
`-` | Subtraction. Subtracts the second operand from the first. | ? | ?
`*` | Multiplication. Multiplies first operand by the second. | ? | ?
`/` | Division. Divides the first operand by the second.| ? | ?
`%` | Modulo. Divides the first interger operand by the second, and returns the remainder. | ? | ?
`+=` | Addition Assignment. It performs the addition of left and right operands and assigns a result to the left operand. | `a += 10 is equals to a = a + 10` | ?
`-=` | Subtraction Assignment. It performs the subtraction of left and right operands and assigns a result to the left operand. | `a -= 10 is equals to a = a - 10` | ?
`*=` | Muliplication Assignment. It performs the multiplication of left and right operands and assigns a result to the left operand. | `a *= 10 is equals to a = a * 10` | ?
`/=` | Division Assignment. It performs the division of left and right operands and assigns a result to the left operand. | `a /= 10 is equals to a = a / 10` | ?
`%=` | Modulo Assignment. It performs the modulo operation on two operands and assigns a result to the left operand. | `a %= 10 is equals to a = a % 10` | ?
`**=` | Exponentiation Assignment. Raises the value of a variable to the power of the right operand. | `int a = 3; console.log(a **= 2); // expected output: 9` | ?
`++` | Adds one to its operand. | ? | ?
`--` | Subtracts one from its operand. | ? | ?
`i++` | Post-Increment. The variable is incremented after the expression is set. | ? | ?
`++i` | Pre-Increment. The variable is incremented before the expression is set. | ? | ?
-------------------------------



## Logical Operators
Keyword |                  Summary                   | Sample Code | Mentioned In
------- | ------------------------------------------ | ------------ | ------------
Logical Operators | Logical operators perform and, or, and not operations. They work by evaluating the first operand and then, if necessary the second. The second operand is evaluated only if its value is needed to determine the result. | ? | ?
`!` | NOT | `!thirsty` | ?
`&&` | AND | `randomNumber > 1 && randomNumber < 10` | ?
`||` | OR | `randomNumber > 1 || someAmount < 5` | ?
-------------------------------




## Comparison Operators
Keyword |                  Summary                   | Sample Code | Mentioned In
------- | ------------------------------------------ | ------------ | ------------
Comparison Operators | An operator used for comparing numeric operands that returns a true/false condition. | ? | ?
`>` | Greater than. | `5 > 4` | ?
`<` | Lesser than. | `4 < 5` | ?
`==` | Equals to. | `randomNumber == 1` | ?
`!=` | Not Equals to. | `randomNumber != 1` | ?
`||` | OR | `pepsi || cola` | ?
`>=` | Equals to or greater than. | `cola >= pepsi` | ?
`<=` | Equals to or lesser than. | `pepsi <= cola` | ?
`if` | If the conditions apply then execute the line of code in the if-statement body. | `if { if-body }` | ?
`else if` | If the other `if` statements did not apply then execute the line of code in the else if-statement body instead. | `else if { else if-body }` | ?
`else` | else will execute when other `if` statements did not apply however it doesn't need a condition (body) like `if`, `else if` | `else return;` | ?
-------------------------------




## Strings
Keyword |                  Summary                   | Sample Code | Mentioned In
------- | ------------------------------------------ | ------------ | ------------
`string.Length` | ? | ? | ?
`string.ToUpper` | Converts all characters to uppercase. | ? | ?
`string.ToLower` | Converts all characters to lowercase. | ? | ?
`string.+` | ? | ? | ?
`$"{}"` | Interpolated String Literal. A string that might contain interpolation expressions. | `string name = Mark;`, `Console.WriteLine($"Hi {name} how are you?") // returns Hi Mark how are you?` | ?
`@" "` | Verbatim String Literal. Anything in the string that would normally be interpreted as an escape sequence is ignored. It also allows multi-line contents. | `Console.WriteLine(@"He said ""Hi Mark how are you?"" sarcastically") // returns He said "Hi Mark how are you?" sarcastically` | ?
`string.IndexOf` | ? | ? | ?
`string.SubString(int)` | ? | ? | ?
`string.Substring(int, int)` | ? | ? | ?
`string.Replace` | ? | ? | ?
-------------------------------





## Math
Keyword |                  Summary                   | Sample Code | Mentioned In
------- | ------------------------------------------ | ------------ | ------------
`System.Math` | A static class containing many useful functions for numeric operands. | ? | ?
`Math.Max` | Returns the higher of two numbers. | `Math.Max(int, int)`, `int max = Math.Max (5, 3) // returns 5` | ?
`Math.Min` | Returns the smaller of two numbers. | `Math.Min(int, int)`, `int min = Math.Min (5, 3) // returns 3` | ?
`Math.Sqrt` | Returns the Square Root of a number. | `double Sqrt(double)`, `double sqrt = Math.Sqrt(16); // returns 4.0, because 4 * 4 = 16` | ?
`Math.Abs` | Returns the absolute of a number, which is always positive. | `double Abs(double)`, `double abs = Math.Abs(-4.3); // returns 4.3` | ?
`Math.Round` | Returns the rounded value of a number (closest integer). Uses statistical rounding | `double Round(double)`, `double round = Math.Round(12.6); // returns 13` | ?
`Math.Floor` | Returns the value of the number rounded to the lower integer | `double Floor(double)`, `double floor = Math.Floor(12.6); // returns 12` | ?
`Math.Ceiling` | Returns the value of the number rounded to the higher integer | `double Ceiling(double)`, `double ceil = Math.Ceiling(12.1); // returns 13` | ?
`Math.Clamp` | Returns the value made to fit within the Min and Max | `int Clamp(int value, int min, int max)`, `double clamp = Math.Clamp(15, 0, 10); // The value of 15 fits between 0 and 10 only up to the maximum of 10` | ?
`Math.Pow` | Returns the value to the power of power. | `double Pow(double value, double power)`, `double pow = Math.Pow(2, 3); // 8, because 2^3 = 2 * 2 * 2 = 8` | ?
-------------------------------





## Arrays
Keyword |                  Summary                   | Sample Code | Mentioned In
------- | ------------------------------------------ | ------------ | ------------
`Array` | A static list of a field | ? | ?
`int[]` | A static list of integers. | `int[] x = new int[]`, `int[] list-name = new int[insert number]` | ?
`string[]` | A static list of strings. | ? | ?
`Array.Resize` | Resizes an Array. | ? | ?
`Array.Length` | Used to refer to an Arrays' length. |  `for (int i = 0; i < array.Length; i++)` in this case we're expanding the array. | ?
`foreach` | ? | ? | ?
`2D-Array` | ? | ? | ?
Array Initialization | ? | `int[] list-name = new int[insert number]` | ?
Array Access for Assignment | ? | ? | ?
Array Access for Reading | ? | ? | ?
2D-Array Initialization | ? | ? | ?
2D-Array Access for Assignment | ? | ? | ?
2D-Array Access for Reading | ? | ? | ?
Jagged Arrays | ? | ? | ?
-------------------------------


## Loops
Keyword |                  Summary                   | Sample Code | Mentioned In
------- | ------------------------------------------ | ------------ | ------------
Loop | A piece of statement that is being repeated. | ? | ?
Loop Body | The statments withing the Loop | ? | ?
Initializer statement | The initializer section is used to initialize a variable that will be local to a for loop and cannot be accessed outside loop. It can also be zero or more assignment statements, method call, increment, or decrement expression e.g., ++i or i++, and await expression. | ? | ?
Condition statement | The condition is a boolean expression that will return either true or false. If an expression evaluates to true, then it will execute the loop again; otherwise, the loop is exited. | ? | ?
Iteration statement | The iterator defines the incremental or decremental of the loop variable. | ? | ?
For Loop | A loop that executes a block of statements repeatedly until the specified condition returns false. | `for (initializer; condition; iterator) { loop-body }`, `for (int i = 0 ; i < 5 ; i++) { loop-body }` | ?
While Loop | A loop that runs through a block of statements as long as a specified condition is true. It does not have a initializer. |  `while (condition) { loop-body }` | ?
Do...While Loop | A variant of the while loop. This loop will execute the code block once, before checking if the condition is true, then it will repeat the loop as long as the condition is true. | `do { conditional code ; } while (condition);` | ?
Nested Loop | A loop withing a loop | `while(condition) { while(condition) { loop-body 1 ;} loop-body 2 ;}` | ?
Jump Statements | A Jump Statement or Execution Jump are statements that help in transferring control from one point to the other. | ? | ?
`break` | ? | ? | ?
`continue` | ? | ? | ?
`return` | ? | ? | ?
`goto` | ? | ? | ?
`throw` | ? | ? | ?



## Clean
Keyword |                  Summary                   | Sample Code | Mentioned In
------- | ------------------------------------------ | ------------ | ------------
`const` | Constant. A keyword to make a field immutable. | ? | ?
immutable | Means that the set field cannot be changed. | ? | ?
`? :` | ? | ? | ?
Flow Control Statements | ? | ? | ?
`System.Random` | ? | ? | ?
pseudo-random | ? | ? | ?
seed | ? | ? | ?
`Random.Next(int, int)` | ? | ? | ?
`Random.Next()` | ? | ? | ?
`Random.NextDouble()` | ? | ? | ?
`Random.Next()` | ? | ? | ?
Method | ? | ? | ?
`void` | ? | ? | ?
Return Type | ? | ? | ?
`()` | ? | ? | ?
Parameter | ? | ? | ?
Argument | ? | ? | ?
Parameter | ? | ? | ?
Parameter-List | ? | ? | ?
Named Arguments | ? | ? | ?
Optional Arguments | ? | ? | ?
Default Value | ? | ? | ?
Code Paths | ? | ? | ?
Method Overloading | ? | ? | ?
Object-Oriented Programming | ? | ? | ?
Data | ? | ? | ?
Function | ? | ? | ?
Structured Programming | ? | ? | ?
Objects | ? | ? | ?
Instance Method | ? | ? | ?
Class | ? | ? | ?
Type | ? | ? | ?
`class` | ? | ? | ?
`new` | ? | ? | ?
Class Member | ? | ? | ?
Class Instance | ? | ? | ?
Garbage Collector | ? | ? | ?
`null` | ? | ? | ?
Invoke | ? | ? | ?
Field | ? | ? | ?
Static Class Member | ? | ? | ?
Static Class | ? | ? | ?
Global Access | ? | ? | ?
Constructor | ? | ? | ?
Initial Class Values | ? | ? | ?
Parameterless | ? | ? | ?
Default Contructor | ? | ? | ?
Finalizer | ? | ? | ?
Object Destruction | ? | ? | ?
`GC.Collect` | ? | ? | ?
Encapsulation | ? | ? | ?
Access Modifier | ? | ? | ?
`private` | ? | ? | ?
`protected` | ? | ? | ?
`public` | ? | ? | ?
`internal` | ? | ? | ?
Class Member Access | ? | ? | ?
Inheritance | ? | ? | ?
Property | ? | ? | ?
Getter Method | ? | ? | ?
Setter Method | ? | ? | ?
Validation | ? | ? | ?
Processing | ? | ? | ?
`get` | ? | ? | ?
`set` | ? | ? | ?
Expression Body Syntax | ? | ? | ?
Auto Property | ? | ? | ?
Read-Only Property | ? | ? | ?
Auto Property | ? | ? | ?
base-Class | ? | ? | ?
Inherit From | ? | ? | ?
Derived Class | ? | ? | ?
Child Class | ? | ? | ?
Parent Class | ? | ? | ?
`sealed` | ? | ? | ?
Polymorphism | ? | ? | ?
`as` | ? | ? | ?
`virtual` | ? | ? | ?
`override` | ? | ? | ?
`base` | ? | ? | ?
Abstraction | ? | ? | ?
`abstract` | ? | ? | ?
Implementation | ? | ? | ?
Composition | ? | ? | ?
"Composition over Inheritance" | ? | ? | ?
