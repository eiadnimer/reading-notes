# Debugging
- Every statement in a script lives in one of three execution contexts:
1- Global context
2- FUNCTION CONTEXT Code that is being run within a function.Each function has its own function context.
3- Eval context
- **Variable scope**
1- Global scope: If a variable is declared **outside** a function, it can be used anywhere because it has global scope
2- Function-level scope: When a variable is declared **within a function**,it can only be used within that function
- **Error objects**
- Error objects can help you find where your mistakes are and browsers have tools to help you read them.
- **Types of built-in error objects in JavaScript**
1- Error	
2- Syntax Error
3- TypeError
4- ReferenceError
5- Range Error
6- URI Error
7- EvalError
- There is two ways to deal with errors:
1- Track down the source of the error, and fix it.
2- You can handle errors gracefully using try, catch, throw, and finally statements.
