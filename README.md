# nanotools

Connect to Nanobox.io Database

Currently tested on Mac OS only

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/nanotools.svg)](https://npmjs.org/package/nanotools)
[![Downloads/week](https://img.shields.io/npm/dw/nanotools.svg)](https://npmjs.org/package/nanotools)
[![License](https://img.shields.io/npm/l/nanotools.svg)](https://github.com/pingsrl/nanotools/blob/master/package.json)

# What is this?

This is a simple tool that opens the database component of [nanobox.io](http://nanobox.io) in your favorite ide (It must support URI like `mysql://` o `postgres://`)

# Installation

    npm i -g nanotools

# Usage examples

### Connect to local DB

    $ cd my-nanobox-project
    $ nanotools db [local]
    running open mysql://nanobox:78sdhdJAax@172.23.0.34/gonano

### Connect to remote storage

    $ cd my-nanobox-project
    $ nanotools storage productions
    running open sftp://nanobox:78sdhdJAax@127.0.0.1:1234/app
