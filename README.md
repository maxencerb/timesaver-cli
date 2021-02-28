timesaver-cli
=============

Create and use shortcuts for your cli

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/timesaver-cli.svg)](https://npmjs.org/package/timesaver-cli)
[![Downloads/week](https://img.shields.io/npm/dw/timesaver-cli.svg)](https://npmjs.org/package/timesaver-cli)
[![License](https://img.shields.io/npm/l/timesaver-cli.svg)](https://github.com/maxencerb/timesaver-cli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g timesaver-cli
$ tsrc COMMAND
running command...
$ tsrc (-v|--version|version)
timesaver-cli/0.0.0 win32-x64 node-v14.15.1
$ tsrc --help [COMMAND]
USAGE
  $ tsrc COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`tsrc hello [FILE]`](#tsrc-hello-file)
* [`tsrc help [COMMAND]`](#tsrc-help-command)

## `tsrc hello [FILE]`

describe the command here

```
USAGE
  $ tsrc hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ tsrc hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/maxencerb/timesaver-cli/blob/v0.0.0/src/commands/hello.ts)_

## `tsrc help [COMMAND]`

display help for tsrc

```
USAGE
  $ tsrc help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.2/src/commands/help.ts)_
<!-- commandsstop -->
