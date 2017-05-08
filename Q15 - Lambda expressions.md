#### Java
Lambda experiences help provide a clearer way to represent a method interface using an expression. They also help reduce the bulkiness of an anonymous inner class by reducing the number of lines of code needed. 

Example of Lambda Expressions:
```
Runnable ex = () -> System.out.println("This is a lambda expression example!");
ex.run();
```

Lambda Expressions have several key characteristics:

  -- Optional Type Declaration
  
  -- Optional Paranthesis Around Parameter
  
  -- Optional Curly Braces
  
  -- Optional Return Keyword
  
All of these characteriscs help reduce and simplify code

#### Swift
Swift doesn't have lambda expressions, but it does have closures which are comparable. However, closures are more powerful. They can capture non-constant variables and they support shorthand argument names. Like a lambda expression, closures are a way to make code more brief and focused.

Closure Example:
```
megansCats = names.sorted*by: { s1: String, s2: String ) -> Bool in 
  return s1 > s2
})
```

----

### Sources
Java Answers:

http://www.oracle.com/webfolder/technetwork/tutorials/obe/java/Lambda-QuickStart/index.html

https://www.tutorialspoint.com/java8/java8_lambda_expressions.htm

Swift Answers:

http://stackoverflow.com/questions/40459440/comparing-javas-lambda-expression-with-swifts-function-type

https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/Closures.html#//apple_ref/doc/uid/TP40014097-CH11-ID95
