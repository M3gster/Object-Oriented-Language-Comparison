#### Java
Sample
#### Swift
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

Swift Answers:

Class 32-33 on Canvas
