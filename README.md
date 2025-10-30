## EntityLib by Tofaa2

<br>
All credits go to https://github.com/Tofaa2/EntityLib
Here you will just find independent builds of the library
<br>

Currently supported **platforms** are `spigot` and `velocity`.
You can easily use EntityLib platformless by using the api or common module
<br>

Gradle (Kotlin DSL):
```kotlin
repositories {
    maven("https://jitpack.io")
}

dependencies {
    implementation("com.github.maximjsx.EntityLib:<platform>:1.0.0") // replace <platform> with: api, spigot, velocity..
}
```

Gradle (Groovy DSL):
```groovy
repositories {
    maven { url 'https://jitpack.io' }
}

dependencies {
    implementation 'com.github.maximjsx.EntityLib:<platform>:1.0.0' // replace <platform> with: api, spigot, velocity..
}
```


Maven:
```xml
<repositories>
    <repository>
        <id>jitpack.io</id>
        <url>https://jitpack.io</url>
    </repository>
</repositories>

<dependencies>
    <dependency>
        <groupId>com.github.maximjsx.EntityLib</groupId>
        <artifactId><platform></artifactId> <!-- oreplace <platform> with: api, spigot, velocity -->
        <version>1.0.0</version>
    </dependency>
</dependencies>
```


### Credits
- https://github.com/Tofaa2/EntityLib
- PacketEvents for providing the API and retrooper being a cool guy in general
- Minestom certain mappings were taken from Minestom cause i have not slept in 4 days and it was faster
