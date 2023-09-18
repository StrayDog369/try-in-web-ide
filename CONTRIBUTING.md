# Contributing guide

## Getting started

The following devfile tasks or npm commands can be used to perform common development tasks for this project.

| **Devfile task**                          | **Npm command**                                              |
|-------------------------------------------|--------------------------------------------------------------|
| Install dependencies                      | `npm i`                                                      |
| Run linter                                | `npm run lint`                                               |
| Bundle (generate dist folder)             | `npm run bundle`                                             |
| Run tests                                 | `npm run test`                                               |
| Update GitHub action's inputs and outputs | `npx action-io-generator -o src/generated/inputs-outputs.ts` |

## Running new changes of the GitHub action

To run your new changes to the GitHub action,

1. Run the `Bundle (generate dist folder)` devfile task, or run the `npm run bundle` command in the terminal. 
2. Push the resulting `dist` folder to your fork
```
git push fork pr-branch
``` 


Before making a PR, ensure that you have ran the `Run linter`, `Bundle`, and `Run tests` tasks successfully.
