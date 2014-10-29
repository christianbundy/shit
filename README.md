Shit
======

For when you forget to use `sudo`.

## Installation

Append the alias to your `.zshrc`.

```
curl -sSL https://raw.githubusercontent.com/christianbundy/shit/master/shit.zsh >> $HOME/.zshrc
```

## Usage

1. Do something wrong, like try to update APT without root privs.

```sh
$ apt-get update
E: Could not open lock file /var/lib/apt/lists/lock - open (13: Permission denied)
E: Unable to lock directory /var/lib/apt/lists/
E: Could not open lock file /var/lib/dpkg/lock - open (13: Permission denied)
E: Unable to lock the administration directory (/var/lib/dpkg/), are you root?

$ shit
0% [Connecting to archive.ubuntu.com] [Connecting to security.ubuntu.com]
```


## Support

Please [open an issue](https://github.com/christianbundy/shit/issues/new) for questions and concerns.

## Contributing

Fork the project, commit your changes, and [open a pull request](https://github.com/christianbundy/shit/compare/).
