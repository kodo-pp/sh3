# sh3
A very simple-to-use build system designed mainly for C/C++, but extensible to almost any programming language

## Installation

### Using pak and pake
```sh
$ pake install
```

### Manual

These commands assume that you want to install *sh3* to `/usr/bin`.
However, you can install *sh3* to any directory, e.g. `/usr/local/bin`, `~/bin` or `/opt/sh3/bin` (be sure to include is into `$PATH`)

```sh
$ sudo install -Dm755 sh3 /usr/bin/
$ sudo chown root:root /usr/bin/sh3
```
