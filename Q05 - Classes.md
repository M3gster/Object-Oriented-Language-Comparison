## Defining
#### Java
Defining a class is done through a class declaration. Class declarations can include: modifiers, class name, name of the superclass preceded by the word extends, a listed of implemented interfaces, and the class body.

Example:
```
class Cat {
  int age;
  string name;
  string color;
 }
 ```
#### Swift
Classes in Swift are defined in a similar way to Java. There can be a modifier, class name, interfaces, and a class body. Extension doesn't normally appear the same in Swift as it does in Java.

Example:
```
class Cat{
  var age: Int
  var name: String
  var color: String
 }
 ```

## Creating new instances
#### Java
The new operator is needed to create an instance of the class. It sets aside memory for the new object and returns a reference to that memory. The new operator works by calling the object's constructor.

Example:
```
int height = new Rectangle().height;
```
#### Swift
Sample

## Constructing/initializing
#### Java
Classes contain constructors to initilize an object. Constructors have the same name as its class, but have no return type. Classes must have at least one constructor, but can have more than one assuming they have different signatures. If there isn't a constructor explicitely declared, then it uses the default constructor.

Example of a Constructor:
```
public Cat(int a, string b, string c){
  age = a;
  name = b;
  color = c;
  }
  ```
#### Swift
Sample

## Destructing/de-initializing
#### Java
There are no destructors in Java. However, the finalize method is somewhat similar, but is not recommended. It is used for the cleanup of resources.
#### Swift
Sample

----

### Sources
Java Answers: https://docs.oracle.com/javase/tutorial/java/javaOO/classdecl.html

https://docs.oracle.com/javase/tutorial/java/javaOO/objectcreation.html

http://stackoverflow.com/questions/2506488/when-is-the-finalize-method-called-in-java
