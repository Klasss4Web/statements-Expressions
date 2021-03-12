# statements-Expressions

EXPRESSIONS
 An expression produces a value and can be written wherever a value is expected, for example as an argument in a function call. Each of the following lines contains an expression:
    myvar
    3 + x
    myfunc("a", "b")
    
 STATEMENT
 a statement performs an action. Loops and if statements are examples of statements. A program is basically a sequence of statements (we’re ignoring declarations here). Wherever JavaScript expects a statement, you can also write an expression. Such a statement is called an expression statement. The reverse does not hold: you cannot write a statement where JavaScript expects an expression. For example, an if statement cannot become the argument of a function.
 The following is an example of an if statement:
    var x;
    if (y >= 0) {
        x = y;
    } else {
        x = -y;
    }
