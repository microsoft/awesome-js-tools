# Awesome List of JS Tools from Microsoft

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

## Package Publishing

* [Rush](https://rushjs.io) - all-in-one styled monorepo manager (requires repo managed by Rush)
* [Beachball](https://microsoft.github.io/beachball/) - makes automating npm publishing a breeze (works for any workspace implementation: yarn, npm v7, pnpm, rush)

## Linting

* [Boll](https://microsoft.github.io/boll/) - repository wide linter, enforces standards across all packages inside a monorepo
