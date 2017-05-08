## Which does the language use? (null/nil/etc)
#### Java
null

#### Swift
nil

## Does the language have features for handling null/nil references?
#### Java
You can do exception handling if there is an unwanted null reference, however checking for a null reference and responding explicitly may be less expensive.

#### Swift
Swift uses optionals as a way to handle nil references. If an optional contains a value, then the call succeeds. If the optional is nil, the call returns nil. An optional is wrapped, and if using a ? it will not be forcibly unwrapped. If an optional uses !, it will be forcibly unwrapped and if a force unwrap contains a nil then the program may fail.

Example of Optional:
```
if let catCount = megan.pets?.numCats {
  print("Megan has \(numCats) in her house.")
  } else {
    print("We don't know how many cats she has.")
  }
 ``` 

----

### Sources
Java Answers:

http://stackoverflow.com/questions/5991745/java-null-reference-best-practice

Swift Answers:

https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/OptionalChaining.html
