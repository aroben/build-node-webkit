# build-node-webkit

This repository aims to make it easy to build
[`node-webkit`](https://github.com/rogerwang/node-webkit).

## Prerequisites

* Xcode and its Command Line Tools: Get it from the Mac App Store.

## One-time setup

```shell
$ script/bootstrap
```

Be patient.

## Building

```shell
$ script/build
```

Be patient.

## Updating to a newer version of `node-webkit`

`script/bootstrap` pulls down the latest version of `node-webkit`.
`script/build` will just rebuild that version over and over no matter how many
times you run it. If you want to update to what is *now* the latest version of
`node-webkit`, just run:

```shell
$ script/update
```

Then build as before.
