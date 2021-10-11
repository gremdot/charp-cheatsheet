# CSharp Cheat Sheet Template

## Basic Lingo
Keyword |                  Summary                   | Sample Code | Mentioned In
------- | ------------------------------------------ | ------------ | ------------
`;`     | Used to separate statements from each other.| `int i = 5; i++; Console.WriteLine(i);` | [Script Execution](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#0-script-execution)
`//`    | Used for single-line comments              | `float multiplier = 0.01f; // % to float (e.g. 24% = 0.24)` | [Comments](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#single-line-comments)
Variable Initialization | When a value is assigned to a variable for the first time | `int a = 5;` | [Variables](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#variable-initialization)
`dotnet new console -o project-name` | Used within Command Prompt to create a new template C# Project Folder | ? | ?
Script Execution Order | The order in which script is run and compiled. Generally left to right, top to bottom. | ? | ?
Formatting | The way in which the code is visually presented empasis must be kept on code readability. | ? | ?
`Console.WriteLine` | Used to print variable types, usually a string onto the console on a new line. | ? | ?
`Console.Write` | Used to print variable types, usually a string onto the console- note that this will not print on a new line. | ? | ?
`Console.ReadLine` | Used to read input from the console. Which can in turn be stored into a field. | `string name = Console.ReadLine;` | ?
Multi-Line Comment | Used to make several lines of comments. | `/*/` | ?
XML Documentation Comment | Used to give summaries on your code as well as define your code to the reader (such as class, interface, or delegate) or its member (such as field, property, method, or event). The .NET compiler has an option that reads and generate the XML documentation you've made. Which can be extracted to a separate XML file.  | `/// this method adds two intergers` | ?
Field | A type of data | `string TelephoneNumber;` | ?
Variable | A type of field | `var, int, string, bool etc.` | ?
Variable Declaration | Declaring a field | `int i;` | ?
Variable Assignment | Assigning a field a value | `int i = 0;` | ?
Uninitialized Variable | A field without a value | `int i;` | ?
`=` (Assignment Operator) | Used to give a field a value | `int i = 0;` | ?
Global Variable | Fields that have been declared outside of any functions and accessed by all other functions | `class Program { var imAccessibleToAll static void Main() { more code} }` | ?
Scope | Scope is the area of the program where an item (be it variable, constant, function, etc.) that has an identifier name is recognized. | ? | ?
Variable Scope | The location of which a field is being declared and can be accessed/used. | ? | ?
-------------------------------


## Fields
Keyword |                  Summary                   | Sample Code | Mentioned In
------- | ------------------------------------------ | ------------ | ------------
`int` | A type of field that is able to store a exact number between -2147483648..2147483647 | `int number = 1;` | ?
`double` | A type of field that is able to store a any number with decimals. 64 bits of size. | `double number = 1.567;` | ?
`float` | A type of field that stores an approximate number, that might be rounded up or down, including decimals. 32 bits of size. | `float number = 1.5` | ?
`bool` | A type of field that can store a true or false statement. | `bool isTired = true;` | ?
`char` | A type of field that stores a character. | `char a;` | ?
`string` | A type of field that stores an array of `char`'s or simple put text/ a sentence. | `string text;` | ?
`byte` | ? | ? | ?
Implicit Casting | ? | ? | ?
Explicit Casting | ? | ? | ?
Type Conversion | ? | ? | ?
`Convert.ToInt32` | Used to convert other types of fields into an interger | `int age = Convert.ToInt32(Console.ReadLine());` | ?
-------------------------------



## Operators
Keyword |                  Summary                   | Sample Code | Mentioned In
------- | ------------------------------------------ | ------------ | ------------
Operators | ? | ? | ?
Arithmetic Operators | ? | ? | ?
`+` | ? | ? | ?
`-` | ? | ? | ?
`*` | ? | ? | ?
`/` | ? | ? | ?
`%` | ? | ? | ?
`+=` | ? | ? | ?
`-=` | ? | ? | ?
`++` | ? | ? | ?
`--` | ? | ? | ?
Post-Increment `i++` | ? | ? | ?
Pre-Increment `++i` | ? | ? | ?
Logical Operators | ? | ? | ?
`!` | ? | ? | ?
`&&` | ? | ? | ?
`||` | ? | ? | ?
-------------------------------
Comparison Operators | ? | ? | ?
`>` | ? | ? | ?
`==` | ? | ? | ?
`!=` | ? | ? | ?
`||` | OR | ? | ?
`>=` | Equals to or greater than. | ? | ?
`<=` | Equals to or lesser than. | ? | ?
`if` | If the conditions apply then execute the line of code in the body. | ? | ?
`else` | If the other `if` statment/ statements did not apple then execute this line of code instead. | ? | ?
`else if` | ? | ? | ?
-------------------------------


## Math
Keyword |                  Summary                   | Sample Code | Mentioned In
------- | ------------------------------------------ | ------------ | ------------
`System.Math` | ? | ? | ?
`static` | ? | ? | ?
`Math.Max` | ? | ? | ?
`Math.Min` | ? | ? | ?
`Math.Sqrt` | ? | ? | ?
`Math.Abs` | ? | ? | ?
`Math.Round` | ? | ? | ?
`Math.Floor` | ? | ? | ?
`Math.Ceiling` | ? | ? | ?
`Math.Clamp` | ? | ? | ?
`Math.Pow` | ? | ? | ?
`string.Length` | ? | ? | ?
`string.ToUpper` | ? | ? | ?
`string.+` | ? | ? | ?
`$"{}"` | ? | ? | ?
`string.[]` | ? | ? | ?
`string.IndexOf` | ? | ? | ?
`string.SubString(int)` | ? | ? | ?
`string.Substring(int, int)` | ? | ? | ?
`string.Replace` | ? | ? | ?
immutable | ? | ? | ?
`? :` | ? | ? | ?
Flow Control Statements | ? | ? | ?
`System.Random` | ? | ? | ?
pseudo-random | ? | ? | ?
seed | ? | ? | ?
`Random.Next(int, int)` | ? | ? | ?
`Random.Next()` | ? | ? | ?
`Random.NextDouble()` | ? | ? | ?
`Random.Next()` | ? | ? | ?
`while` | ? | ? | ?
bool-expression | ? | ? | ?
`do..while` | ? | ? | ?
`for` | ? | ? | ?
iteration statement | ? | ? | ?
loop body | ? | ? | ?
loop | ? | ? | ?
execution | ? | ? | ?
execution jump | ? | ? | ?
`break` | ? | ? | ?
`continue` | ? | ? | ?
`Array` | ? | ? | ?
`int[]` | ? | ? | ?
Array Initialization | ? | ? | ?
Array Access for Assignment | ? | ? | ?
Array Access for Reading | ? | ? | ?
`Array.Resize` | ? | ? | ?
`Array.Length` | ? | ? | ?
`foreach` | ? | ? | ?
`2D-Array` | ? | ? | ?
2D-Array Initialization | ? | ? | ?
2D-Array Access for Assignment | ? | ? | ?
2D-Array Access for Reading | ? | ? | ?
Jagged Arrays | ? | ? | ?
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
`return` | ? | ? | ?
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
