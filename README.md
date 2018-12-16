# cp-tools

![Travis](https://travis-ci.org/edsomjr/competitive-problems-tools.svg?branch=master)

A competitive programming problem formatter tool. 

## Instalation

Clone this project and build with command `make`:

```
$ make
```

To install `cp-tools`, use the command below as a super user:

```
# make install
```

The binary will be copied in `/usr/local/bin`. The support files will be copied in `/usr/local/lib/cp-tools` directory.

To uninstall run

```
# make uninstall
```


## Basic usage

To create a basic problem template use the following command on an empty directory:

```
$ cp-tools init
```

To remove autogenerated files (which are located in `.cp-build` folder in current directory), use
the command

```
$ cp-tools clean
```

For more information, use the option `-h` (or `--help`), as shown below:

```
$ cp-tools -h
```
