# Changelog


## [1.4.0](https://github.com/superchargejs/redis-github-action/compare/v1.3.0...v1.4.0) - 2022-12-xx

### Added
- use a custom name for the Redis container: this is helpful when starting multiple Redis instances


## [1.3.0](https://github.com/superchargejs/redis-github-action/compare/v1.2.0...v1.3.0) - 2022-12-27

### Added
- start Redis instance on a custom port


## [1.2.0](https://github.com/superchargejs/redis-github-action/compare/v1.1.0...v1.2.0) - 2021-01-08

### Added
- version check before starting the Redis container: fall back to `latest` when no Redis version is defined for the workflow
- run tests on pull requests

### Updated
- refined wording in Readme


## [1.1.0](https://github.com/superchargejs/redis-github-action/compare/v1.0.0...v1.1.0) - 2019-12-18

### Updated
- switched from a Node.js workflow to a Docker-based workflow
  - reduces noise in the repo by removing the Node.js dependencies and only relying on a shell script


## 1.0.0 - 2019-12-17

### Added
- `1.0.0` release 🚀 🎉
