# igdm-cli

> Instagram's direct message, right in your terminal.

<img src="igdm.gif" width="480">

## Installation

```sh
$ npm i -g igdm-cli
```

## Usage

```sh
igdm-cli

Usage:
    igdm
    igdm [-h] | [-v] | [-u <username>] [-p <password>] [-i <polling interval>]
    igdm [--help] | [--version] | [--username=<username>] [--password=<password>] [--interval=<polling interval>]

Options:
    -h, --help                  Show this screen.
    -v, --version               Show version.
    -u, --username <username>   Set Instagram username. [default: will prompt]
    -p, --password <password>   Set Instagram password. [default: will prompt]
    -i, --interval <interval>   Set polling interval (seconds) in chat rooms [default: 5]

Notes:
    In chatroom mode, exit by entering '/end'. Manually refresh the room by entering '/refresh'.
```

## Developing

To transpile our code using babel, you will need `node` version `>= 6.4.0`.

## License

MIT © [Muhammad Mustadi](https://github.com/mathdroid)