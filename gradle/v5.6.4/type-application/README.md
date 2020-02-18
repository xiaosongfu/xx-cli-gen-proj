

```
$ gradle init

Select type of project to generate:
  1: basic
  2: application
  3: library
  4: Gradle plugin
Enter selection (default: basic) [1..4] 2

Select implementation language:
  1: C++
  2: Groovy
  3: Java
  4: Kotlin
  5: Swift
Enter selection (default: Java) [1..5] 4

Select build script DSL:
  1: Groovy
  2: Kotlin
Enter selection (default: Kotlin) [1..2] 2

Project name (default: type-application):
Source package (default: type.application): ltd.xsfu.test

BUILD SUCCESSFUL in 5m 11s
2 actionable tasks: 2 executed


$ tree
.
├── README.md
├── build.gradle.kts
├── gradle
│   └── wrapper
│       ├── gradle-wrapper.jar
│       └── gradle-wrapper.properties
├── gradlew
├── gradlew.bat
├── settings.gradle.kts
└── src
    ├── main
    │   ├── kotlin
    │   │   └── ltd
    │   │       └── xsfu
    │   │           └── test
    │   │               └── App.kt
    │   └── resources
    └── test
        ├── kotlin
        │   └── ltd
        │       └── xsfu
        │           └── test
        │               └── AppTest.kt
        └── resources

15 directories, 9 files
```
