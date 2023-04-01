## For code changes:

1. Include tests for any bug fixes or new features.
2. Update documentation if relevant
3. Ensure that `npm run test` passes
4. Follow the [Angular Commit Message Conventions](https://github.com/angular/angular/blob/master/CONTRIBUTING.md#-commit-message-format).
   **This guarantees that the project gets an appropriate tag**.
   In a nutshell, the commit messages must be written as:

- `fix: stop graphite breaking when too much pressure applied`
- `feat: add 'graphiteWidth' option`
- ```
  perf: remove graphiteWidth option

  BREAKING CHANGE: The graphiteWidth option has been removed.
  The default graphite width of 10mm is always used for performance reasons
  ```
  
**Important: Remove this section**


## Changelog

- Adds a new feature that ... / Solves an issue when ... / Updates dependencies ...
