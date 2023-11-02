# learn gradle

Linkedin Learning link: [https://www.linkedin.com/learning/learning-gradle/](https://www.linkedin.com/learning/learning-gradle/)

Gradle builds a directed acyclic graph in memory for tasks and dependencies between them.

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

   1. Can also be in the home directory, then it will be applied to all projects on that machine

## Some Basic Commands

- Download gradle wrapper `gradle wrapper`
- List gradle projects `gradle projects`
- Run a gradle task `gradle <task name>`
- List all tasks `gradle tasks --all`
- Check tasks dependency without execution `gradle <task name> --dry-run`
