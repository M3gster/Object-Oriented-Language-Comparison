## How is it handled?
#### Java
Java stores objects in the heap. It is divided into two areas, the nursery and the old space. The nursery is reserved for new objects, and when it becomes full some are moved to the old space. When the old space is filled up, garabage collection occurs there as well.

#### Swift
Sample

## How does it work?
#### Java
Memory is set aside for future objects, and is freed through garbage collection. The size of the areas flucuate as more is added and removed.

#### Swift
Sample

## Garbage collection?
#### Java
Yes, there is garbage collection. As explained earlier, it is used when areas become full. The nursery uses young collection to collect its garbage.

#### Swift
Sample

## Automatic reference counting?
#### Java
No

#### Swift
Sample

----

### Sources
Java Answers: 
https://docs.oracle.com/cd/E13150_01/jrockit_jvm/jrockit/geninfo/diagnos/garbage_collect.html
