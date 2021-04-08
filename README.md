# Awesome List of JS Tools from Microsoft

A list of amazing and awesome open sourced and free tools that power a good portion of Microsoft products that rely on JavaScript.

## Language & Language Tools

* [TypeScript](https://typescriptlang.org) - Typed JavaScript at any scale
* [API Extractor](https://api-extractor.com/) - Enforce API surface for libraries, create `d.ts` rollups, graduate unstable APIs, creates nicely formatted API documentation, and more 

## Package Managers

* [Midgard Yarn](https://github.com/VincentBailly/yarn) - yarn v1, but faster for Azure DevOps feeds
* [Midgard Yarn Strict](https://github.com/VincentBailly/midgard-yarn-strict) - midgard-yarn, but enforces strictness avoiding phantom dependencies

## Monorepo Manager

* [Rush](https://rushjs.io) - all-in-one styled monorepo manager

## Package Scripts

* [Just](https://microsoft.github.io/just/) - A sensible set of task to build, test, and lint your frontend projects
* [Heft](https://rushstack.io/pages/heft/overview/) - Heft is an extensible build system designed for use with the Rush Stack family of tools

## Task Runners

* [Rush](https://rushjs.io) - all-in-one styled monorepo manager (supports incremental builds, scopes)
* [Lage](https://microsoft.github.io/lage/) - Run npm scripts in topological order incrementally with cloud cache (supports incremental builds, scopes, cloud cache, pipelining)
* [BuildXL](https://github.com/Microsoft/BuildXL) ([npm](https://www.npmjs.com/package/@microsoft/buildxl)) - distributed build runner (works with rush or lage repos) 

## End-to-End Testing

* [Playwright](https://playwright.dev/) - enables reliable end-to-end testing for modern web apps (works on all modern browsers)
* [Flamegrill](https://microsoft.github.io/flamegrill) - scenario level test automation that generates a V8-level sample-based flamegraphs

## Package Publishing

* [Rush](https://rushjs.io) - all-in-one styled monorepo manager (requires repo managed by Rush)
* [Beachball](https://microsoft.github.io/beachball/) - makes automating npm publishing a breeze (works for any workspace implementation: yarn, npm v7, pnpm, rush)

## Linting

* [Boll](https://microsoft.github.io/boll/) - repository wide linter, enforces standards across all packages inside a monorepo

## Libraries

* [workspace-tools](https://npmjs.org/package/workspace-tools) - A collection of tools that are useful in a git-controlled monorepo
* [p-graph](https://www.npmjs.com/package/p-graph) - Run a promise graph with concurrency control.
* [@microsoft/task-scheduler](https://www.npmjs.com/package/@microsoft/task-scheduler) - Run a sequence of steps across all the packages of a monorepo
* [Rush](https://rushstack.io/) - contains many useful libraries like command line parsing, incremental build engine using git hashes, useful webpack plugins etc.
* [Monaco Editor](https://microsoft.github.io/monaco-editor/) - code editor that powers [Visual Studio Code](https://github.com/Microsoft/vscode)
* [Rooster Editor](https://github.com/Microsoft/roosterjs) | [demo](https://microsoft.github.io/roosterjs/index.html) - framework agnostic rich text editor that powers Outlook 

## Cross Platform Development

* [React Native Windows](https://github.com/microsoft/react-native-windows) - cross platform JS development with React Native (Windows)
* [React Native MacOS](https://github.com/microsoft/react-native-macos) - cross platform JS development with React Native (MacOS)
