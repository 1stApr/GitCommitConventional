# AngularChartExercixe


# **conventional-commit-types**

|		|								|
| ------------- |---------------------------------------------------------------|
|Convention	|Commit type: commit subject					|
|		|commit body							|
|		|<Commit reference> Refer to github issue or JIRA project ticket|
|Example 	|fix: Fix user can not loggin with google account		|
|		|- Root cause: Missing google API key				|
|		|- Solution: Create a new google API key and add to config file	|
|		|Refs #123, SCM-123						|

Commit types originally from:
* [Angular Git Commit Message Conventions](https://github.com/angular/angular/blob/master/CONTRIBUTING.md#type)
* [commitizen/cz-conventional-changelog](https://github.com/commitizen/cz-conventional-changelog)
* [conventional-commit-types](https://github.com/commitizen/conventional-commit-types)

## Commit types

| Commit Type | Title                    | Description                                                                                                 |
| ----------- | ------------------------ | ----------------------------------------------------------------------------------------------------------- |
| `feat`      | Features                 | A new feature                                                                                               |
| `fix`       | Bug Fixes                | A bug Fix                                                                                                   |
| `docs`      | Documentation            | Documentation only changes                                                                                  |
| `style`     | Styles                   | Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)      |
| `refactor`  | Code Refactoring         | A code change that neither fixes a bug nor adds a feature                                                   |
| `perf`      | Performance Improvements | A code change that improves performance                                                                     |
| `test`      | Tests                    | Adding missing tests or correcting existing tests                                                           |
| `build`     | Builds                   | Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)         |
| `ci`        | Continuous Integrations  | Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs) |
| `chore`     | Chores                   | Other changes that don't modify src or test files                                                           |
| `revert`    | Reverts                  | Reverts a previous commit                                                                                   |

## Commit aliases

Aliases allow to have additionnal commit types (in a tool like [commitizen](https://github.com/commitizen/cz-cli) for example) that can be formatted to follow [AngularJS Commit Message Conventions](https://docs.google.com/document/d/1QrDFcIiPjSLDn3EL15IJygNPiHORgU1_OOAqWjiDU5Y/edit).


| Commit Type        | Maps to | Title             | Description                     | 
| ------------------ | ------- | ----------------- | ------------------------------  |
| `initial`          | `feat`  | Initial           | Initial commit                  | 
| `dependencies`     | `fix`   | Dependencies      | Update dependencies             | 
| `peerDependencies` | `fix`   | Peer dependencies | Update peer dependencies        | 
| `devDependencies`  | `chore` | Dev dependencies  | Update development dependencies | 
| `metadata`         | `fix`   | Metadata          | Update metadata (package.json)  |


|		|								|
| ------------- |---------------------------------------------------------------|
|Convention	|Commit type: commit subject					|
|		|commit body							|
|		|<Commit reference> Refer to github issue or JIRA project ticket|
|Example 	|fix: Fix user can not loggin with google account		|
|		|- Root cause: Missing google API key				|
|		|- Solution: Create a new google API key and add to config file	|
|		|Refs #123, SCM-123						|
