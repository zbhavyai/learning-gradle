# learn gradle

Linkedin Learning link: [https://www.linkedin.com/learning/learning-gradle/](https://www.linkedin.com/learning/learning-gradle/)


1. Run the `example-01`

```
cd example-01
gradle helloWorld
```


## Gradle multi-project build structure

`build.gradle`
1. Resides in root directory
2. Contains all build logic
3. Can become hard to maintain

`settings.gradle`
1. Resides in root directory
2. Declares participating projects
3. Can change defaults, like project name (default is folder name)

`gradle.properties`



## Commands

- Download gradle wrapper `gradle wrapper`
- List gradle projects `gradle projects`
- Run a gradle task `gradle <task name>`
- List all tasks `gradle tasks --all`