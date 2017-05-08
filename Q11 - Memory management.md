## How is it handled?
#### Java
Java stores objects in the heap. It is divided into two areas, the nursery and the old space. The nursery is reserved for new objects, and when it becomes full some are moved to the old space. When the old space is filled up, garabage collection occurs there as well.

#### Swift
Swift does most of the memory management for you. It uses automatic reference counting for this.

## How does it work?
#### Java
Memory is set aside for future objects, and is freed through garbage collection. The size of the areas flucuate as more is added and removed.

#### Swift
ARC sets aside memory every time a new instance of a class is made. When that instance isn't needed, it frees up that memory. ARC tracks a lot of properties, constants, and variables that are currently referring to each class instance so that it doesn't remove anything that still has an active reference. Whenever an instance is assigned to something, a strong reference is created to keep the instance around as long as that strong reference is as well.

## Garbage collection?
#### Java
Yes, there is garbage collection. As explained earlier, it is used when areas become full. The nursery uses young collection to collect its garbage.

#### Swift
No

## Automatic reference counting?
#### Java
No

#### Swift
Swift uses automatic reference counting. It helps track and manage memory usage, so you don't really have to think about memory management much. It works by automatically freeing up memory used by class instances when they aren't needed anymore.

----

### Sources
Java Answers: 

https://docs.oracle.com/cd/E13150_01/jrockit_jvm/jrockit/geninfo/diagnos/garbage_collect.html

Swift Answers:

https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/AutomaticReferenceCounting.html
