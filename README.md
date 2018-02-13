@oclif/dev-cli
===============

helpers for oclif CLIs

[![Version](https://img.shields.io/npm/v/@oclif/dev-cli.svg)](https://npmjs.org/package/@oclif/dev-cli)
[![CircleCI](https://circleci.com/gh/oclif/dev-cli/tree/master.svg?style=svg)](https://circleci.com/gh/oclif/dev-cli/tree/master)
[![Appveyor CI](https://ci.appveyor.com/api/projects/status/github/oclif/dev-cli?branch=master&svg=true)](https://ci.appveyor.com/project/heroku/dev-cli/branch/master)
[![Codecov](https://codecov.io/gh/oclif/dev-cli/branch/master/graph/badge.svg)](https://codecov.io/gh/oclif/dev-cli)
[![Greenkeeper](https://badges.greenkeeper.io/oclif/dev-cli.svg)](https://greenkeeper.io/)
[![Known Vulnerabilities](https://snyk.io/test/npm/@oclif/dev-cli/badge.svg)](https://snyk.io/test/npm/@oclif/dev-cli)
[![Downloads/week](https://img.shields.io/npm/dw/@oclif/dev-cli.svg)](https://npmjs.org/package/@oclif/dev-cli)
[![License](https://img.shields.io/npm/l/@oclif/dev-cli.svg)](https://github.com/oclif/dev-cli/blob/master/package.json)

<!-- install -->
# Installing @oclif/dev-cli

with yarn:
```
$ yarn global add @oclif/dev-cli
```

or with npm:
```
$ npm install -g @oclif/dev-cli
```
<!-- installstop -->
<!-- usage -->
# Usage

```sh-session
$ oclif-dev COMMAND
running command...
$ oclif-dev (-v|--version|version)
@oclif/dev-cli/0.3.12 (linux-x64) node-v9.5.0
$ oclif-dev --help [COMMAND]
USAGE
  $ oclif-dev COMMAND [OPTIONS]
...
```
<!-- usagestop -->
<!-- commands -->
# Commands

* [oclif-dev help [COMMAND] [OPTIONS]](#help)
* [oclif-dev manifest [PATH] [OPTIONS]](#manifest)
* [oclif-dev readme [OPTIONS]](#readme)
## help

display help for oclif-dev

```
USAGE
  $ oclif-dev help [COMMAND] [OPTIONS]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v0.7.3/src/commands/help.ts)_

## manifest

generates plugin manifest json

```
USAGE
  $ oclif-dev manifest [PATH] [OPTIONS]

ARGUMENTS
  PATH  [default: .] path to plugin

OPTIONS
  --help     show CLI help
  --version  show CLI version
```

_See code: [@oclif/dev-cli](https://github.com/oclif/dev-cli/blob/v0.3.12/src/commands/manifest.ts)_

## readme

adds commands to README.md in current directory

```
USAGE
  $ oclif-dev readme [OPTIONS]

OPTIONS
  --multi  create a different markdown page for each topic

DESCRIPTION

  The readme must have any of the following tags inside of it for it to be replaced or else it will do nothing:
  <!-- install -->
  <!-- usage -->
  <!-- commands -->
```

_See code: [@oclif/dev-cli](https://github.com/oclif/dev-cli/blob/v0.3.12/src/commands/readme.ts)_
<!-- commandsstop -->
