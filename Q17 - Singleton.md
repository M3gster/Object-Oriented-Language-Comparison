#### Java
A singleton is used when you want just one instance of a class. The singleton design pattern allows you to make sure only one instance is create, provides a global point of access to the object, and lets multiple instances in the future without impacting the singleton class's clients. Singletons are similar to static fields in that they only occur once per class.

Example (from source):
```public class ClassicSingleton {
   private static ClassicSingleton instance = null;
   protected ClassicSingleton() {
      // Exists only to defeat instantiation.
   }
   public static ClassicSingleton getInstance() {
      if(instance == null) {
         instance = new ClassicSingleton();
      }
      return instance;
   }
}
```

#### Swift
Singletons serve the same idea in Swift as they do in Java. The most basic way to create a singleton in Swift is by defining a global variable, and those are initialized lazily. 

Example:
```
class Settings {
    let user: UserSettings
    let system: SystemSettings

    static let sharedInstance = Settings()

    fileprivate init() {
        self.user = UserSettings()
        self.system = SystemSettings()
    }
}
```
----

### Sources
Java Answers:

http://www.javaworld.com/article/2073352/core-java/simply-singleton.html

https://www.tutorialspoint.com/java/java_using_singleton.htm

Swift Answers:

Class 32-33 on Canvas
