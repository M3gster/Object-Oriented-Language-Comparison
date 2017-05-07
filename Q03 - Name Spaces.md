## How are name spaces implemented?
#### Java
Name spaces are implemented in Java through the use of packages, a package being a "collection of related classes and interfaces providing access privileges and name space management."
#### Swift
Namespaces are implicitly declared in Swift. Swift makes a namespace at the boundary of each of its modules.

## How are name spaces used?
#### Java
As stated earlier, a package is a Java namespace. You need to import the classes in a package in order to gain access to them. Once you do that, you can create instances of those classes. Importing requires an import statement.
```
import graphics.Rectangle;
```
#### Swift
Similar to Java, to use a namespace in Swift, you need to import the module. Importing in Swift, again is like Java. Use an import statement like this for example:
 ```
 import ModuleExample
 ```

----

### Sources
Java Answers: http://cs.smu.ca/~porter/csc/465/notes/javapl_packages.html
Swift Answers: https://andybargh.com/lifetime-scope-and-namespaces-in-swift/#Namespaces
