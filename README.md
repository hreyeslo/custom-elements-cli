custom-elements-cli
===================



[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/custom-elements-cli.svg)](https://npmjs.org/package/custom-elements-cli)
[![CircleCI](https://circleci.com/gh/hreyeslo17/custom-elements-cli/tree/master.svg?style=shield)](https://circleci.com/gh/hreyeslo17/custom-elements-cli/tree/master)
[![Codecov](https://codecov.io/gh/hreyeslo17/custom-elements-cli/branch/master/graph/badge.svg)](https://codecov.io/gh/hreyeslo17/custom-elements-cli)
[![Downloads/week](https://img.shields.io/npm/dw/custom-elements-cli.svg)](https://npmjs.org/package/custom-elements-cli)
[![License](https://img.shields.io/npm/l/custom-elements-cli.svg)](https://github.com/hreyeslo17/custom-elements-cli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g custom-elements-cli
$ ce COMMAND
running command...
$ ce (-v|--version|version)
custom-elements-cli/0.0.1 darwin-x64 node-v12.14.1
$ ce --help [COMMAND]
USAGE
  $ ce COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`ce hello [FILE]`](#ce-hello-file)
* [`ce help [COMMAND]`](#ce-help-command)

## `ce hello [FILE]`

describe the command here

```
USAGE
  $ ce hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ ce hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/hreyeslo17/custom-elements-cli/blob/v0.0.1/src/commands/hello.ts)_

## `ce help [COMMAND]`

display help for ce

```
USAGE
  $ ce help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.2.3/src/commands/help.ts)_
<!-- commandsstop -->
