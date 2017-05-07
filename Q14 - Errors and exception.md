#### Java
###### Reasons for Exceptions
- A user has entered an invalid data.
- A file that needs to be opened cannot be found.
- A network connection has been lost in the middle of communications or the JVM has run out of memory.
###### Throwing Exceptions
Before you can catch an exception, some code somewhere must throw one. Any code can throw an exception: your code, code from a package written by someone else such as the packages that come with the Java platform, or the Java runtime environment. Regardless of what throws the exception, it's always thrown with the **throw** statement.
###### Errors
When a dynamic linking failure or other hard failure in the Java virtual machine occurs, the virtual machine throws an **Error**. Simple programs typically do not catch or throw **Errors**.

#### Swift
###### Representing and Throwing Errors
In Swift, errors are represented by values of types that conform to the **Error** protocol. This empty protocol indicates that a type can be used for error handling.
###### Handling Errors
When an error is thrown, some surrounding piece of code must be responsible for handling the error—for example, by correcting the problem, trying an alternative approach, or informing the user of the failure.

----

### Sources
https://www.tutorialspoint.com/java/java_exceptions.htm

https://docs.oracle.com/javase/tutorial/essential/exceptions/throwing.html

https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/ErrorHandling.html
