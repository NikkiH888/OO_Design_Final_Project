# Java
- Lambda Expressions are a way of representing a functional method using an expression.
- They also shorten the amount of code needed for declaring an anonymous inner class.

#### Code Examples:
// Type declaration
MathOperation addition = (int a, int b) -> a + b;

// Without type declaration
MathOperation subtraction = (a, b) -> a - b;

// Return statement along with curly braces
MathOperation multiplication = (int a, int b) -> { return a * b; };

# C#
- A lambda expression is an anonymous function that you can use to create delegates or expression types.
- By using lambda expressions, you can write local functions that can be passed as arguments or returned as the value of function calls.
- To create a lambda expression, you specify input nother or parameters on the left side of the lambda operator =>, and you put the expression or statement block on the other side. For example, the lambda expression x => x * x specifies a parameter that’s named x and returns the value of x squared. 

### There are three main ones:

#### Expression Lambdas:
* (input-parameters) => expression

#### Statement Lambdas:
* (input-parameters) => { statement; }

#### Async Lambdas:
* You can easily create lambda expressions and statements that incorporate asynchronous processing by using the async and await keywords.
