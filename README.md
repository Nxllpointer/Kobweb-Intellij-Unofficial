# Unofficial IntelliJ support for [Kobweb](https://github.com/varabyte/kobweb)
- - -
This project is not associated with the actual Kobweb project

## Features
- **Suppression of "Unused" warning for functions with Annotations like `@Page`, `@App` and so on.** If an annotation is missing, then you can add it [here](src/main/kotlin/com/varabyte/kobweb/intellij/inspections/UnusedInspectionSuppressor.kt).

## Building
To build the plugin simply run the `buildPlugin` Gradle task.
The built plugin will be located in the [build/distributions]() directory.

## Installing
1. Download/Build plugin
2. Install plugin from disk ([see here](https://www.jetbrains.com/help/idea/managing-plugins.html#install_plugin_from_disk)) 