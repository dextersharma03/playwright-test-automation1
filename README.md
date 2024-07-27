# Introduction to Playwright

Hi 👋🏽!

Welcome to the "Playwright Automation" repo.

## Dependencies

- Playwright v1.33.0
- Node v19.8.1
- npm v9.6.5
- VSCode 1.77.3 (Universal)

> Pre requirements: 
- [Node setup](https://nodejs.dev/en/learn/how-to-install-nodejs/)
- [VS Code setup](https://code.visualstudio.com/learn/get-started/basics)

## Fork and clone the project

1. Fork the project
1. Access the forked project `cd <project-dir>`

## Instal the project

On your terminal, type:

1. `npm install`
2. `npm install -D @playwright/test@latest`
3. `npx playwright install --with-deps`

IMPORTANT: to run the tests from `main`, you'll need to setup your [.env](.env) following the [.env.example](.env.example), otherwise many tests will fail.

Happy Testing 🎭