
```
$ gradle init

Select type of project to generate:
  1: basic
  2: application
  3: library
  4: Gradle plugin
Enter selection (default: basic) [1..4] 3

Select implementation language:
  1: C++
  2: Groovy
  3: Java
  4: Kotlin
  5: Scala
  6: Swift
Enter selection (default: Java) [1..6] 4

Select build script DSL:
  1: Groovy
  2: Kotlin
Enter selection (default: Kotlin) [1..2] 2

Project name (default: type-library):
Source package (default: type.library): ltd.xsfu.test

BUILD SUCCESSFUL in 42s
2 actionable tasks: 2 executed


$ tree
.
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
    │   │               └── Library.kt
    │   └── resources
    └── test
        ├── kotlin
        │   └── ltd
        │       └── xsfu
        │           └── test
        │               └── LibraryTest.kt
        └── resources

15 directories, 8 files
```
