#### Java
The **EventHandler** class provides support for dynamically generating event listeners whose methods execute a simple statement involving an incoming event object and a target object. The **EventHandler** class is intended to be used by interactive tools, such as application builders, that allow developers to make connections between beans. Typically connections are made from a user interface bean (the event *source*) to an application logic bean (the *target*). The most effective connections of this kind isolate the application logic from the user interface.
#### Swift
Custom event listeners allow users to separate concerns and prevent a mess of function calls. One effective method is to create an **Events** property of type **EventManager** on each class that requires tracking.

----

### Sources
https://docs.oracle.com/javase/7/docs/api/java/beans/EventHandler.html

https://github.com/StephenHaney/Swift-Custom-Events
