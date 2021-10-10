tlylt-scripts
=============

CLI toolbox for common scripts for my projects

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/tlylt-scripts.svg)](https://npmjs.org/package/tlylt-scripts)
[![Downloads/week](https://img.shields.io/npm/dw/tlylt-scripts.svg)](https://npmjs.org/package/tlylt-scripts)
[![License](https://img.shields.io/npm/l/tlylt-scripts.svg)](https://github.com/tlylt/tlylt-scripts/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g tlylt-scripts
$ tlylt-scripts COMMAND
running command...
$ tlylt-scripts (-v|--version|version)
tlylt-scripts/0.0.0 win32-x64 node-v14.15.1
$ tlylt-scripts --help [COMMAND]
USAGE
  $ tlylt-scripts COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`tlylt-scripts hello [FILE]`](#tlylt-scripts-hello-file)
* [`tlylt-scripts help [COMMAND]`](#tlylt-scripts-help-command)

## `tlylt-scripts hello [FILE]`

describe the command here

```
USAGE
  $ tlylt-scripts hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ tlylt-scripts hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/tlylt/tlylt-scripts/blob/v0.0.0/src/commands/hello.ts)_

## `tlylt-scripts help [COMMAND]`

display help for tlylt-scripts

```
USAGE
  $ tlylt-scripts help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.3/src/commands/help.ts)_
<!-- commandsstop -->
