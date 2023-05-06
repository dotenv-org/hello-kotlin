# hello-kotlin

Source [https://docs.gradle.org/current/samples/sample_building_kotlin_applications.html](https://docs.gradle.org/current/samples/sample_building_kotlin_applications.html)

```
mkdir hello-kotlin
gradle init
gradle run
```

Add dotenv to `app/build.gradle.kts`

```
dependencies {
    ...
    implementation("io.github.cdimascio:dotenv-kotlin:6.4.1")
}
```

```
gradle run
```
