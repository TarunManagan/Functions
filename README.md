# Name: S.Tarun Managan
# PRN: 22070123118

# Functions
A function is a set of statements that takes input, does some specific computation, and produces output. 
The idea is to put some commonly or repeatedly done tasks together to make a function so that instead of writing the same code again and again 
for different inputs, we can call this function.
In simple terms, a function is a block of code that runs only when it is called.
* Functions help us in reducing code redundancy. We create a function and call it everywhere. This also helps in maintenance as we have to make changes in only one place if we make changes to the functionality in the future.
* Functions make code modular. Consider a big file having many lines of code. It becomes really simple to read and use the code  if the code is divided into functions.
* Functions provide abstraction. For example, we can use library functions without worrying about their internal work.

# There are two most popular ways to pass parameters:

* Pass by Value: In this parameter passing method, values of actual parameters are copied to the function’s formal parameters. The actual and formal parameters are stored in different memory locations so any changes made in the functions are not reflected in the actual parameters of the caller. 
 
* Pass by Reference: Both actual and formal parameters refer to the same locations, so any changes made inside the function are reflected in the actual parameters of the caller.

# Syntax: 
void myFunction() { // declaration
  // the body of the function (definition)
}
