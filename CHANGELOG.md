# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.0] - 2026-10-29

### Added

- v1.0.0-beta.20 to use current_module()
- **releaser**: add dry-run command to releaser
- make keep a changelog compatible
- add minor version to commitizen
- simplify jinja files
- bump to dagger engine v1.0.0-beta.19
- module reproducibility & pyproject.toml test
- documentation improvements
- update to dagger v1.0.0-beta.16
- **releaser**: Add release command
- documentation improvements
- improve shiryu error logging
- update to dagger v1.0.0-beta.16
- **pyproject**: change version provider to uv
- **scm**: write secret variables with _ suffix
- **releaser**: Revert user GitRef to push commits and tags
- **releaser**: add branch option to release
- **releaser**: add push command
- **releaser**: Add release command
- use static project version
- use dagger.Workspace an remove project_directory arguments
- use dagger.Changeset for init, build, fix-code and document
- update dagger.io to v1.0.0-beta.15
- add release command and release workflow
- add linter vcs
- replace mypy for ty
- add documenter auditor that runs with llm
- change to zensical
- add auditor
- Add python SDK
- Initial commit

### Changed

- **releaser**: remove extra steps, make bump easy
- **scm**: remove @check decorator, fix file generation changes
- refact SDKModuleFunctionParameter
- refactor build_gitlab_job
- **version**: use version 0.0.0 as initial version
- **releaser**: remove unnused code
- **dagger**: remove shiryu registry

### Fixed

- project when generated from scratch
- linter
- **pyproject**: pin uv to 0.13.4 to auditor to avoi  PYSEC-2026-4321
- uv 0.13.3 security vulnerabilities
- simplify the python get project metadata
- reproducibility improvements
- remove unused section in github workflow
- fix ReturnType in releaser
- **generate**: run generate command to fix unknown flag
- documentation
- pipelines
- revert branch specific changes
- minor fixes
- commitizen version provider
- remove @dagger.check decorators until CI fails when they are added
-  typing/overload issues in the Python SDK
- **ci**: point to new branch
- **releaser**: fix no awaited async method
- minor issue in template generator
- after init --is-update
- improve releaser release and test chore: update docstrings
- secrets handling
- check that uv.lock is consistent with pyproject.toml
- secrets handling
- git depth for lint-vcs
- dagger function to scm conversion and refactor case module
- documentation zensical.toml parse and improve minimal version definitions
- ty.toml.jinja2
- fix tests
- fix checker
- remove zensical in shiryu branch versions
