# Welcome to nookure maven repository
## How to add this repository to your project
### Gradle kotlin DSL
```kotlin
repositories {
    maven("https://maven.nookure.com")
}
```

### Gradle groovy DSL
```groovy
repositories {
    maven {
        name = "nookure"
        url = "https://maven.nookure.com"
    }
}
```

### Maven
```xml
<repositories>
    <repository>
        <id>nookure</id>
        <url>https://maven.nookure.com</url>
    </repository>
</repositories>
```