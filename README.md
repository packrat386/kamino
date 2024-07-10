kamino
---

`kamino` is a tool to clone repos into a standardized path.

## Installation

Put the `kamino` binary somewhere in your `PATH`

## Usage

```
usage:
kamino clone <url>
  clones <url> to $KAMINO_ROOT/<forge>/<username>/<repo>
kamino init <forge> <username> <repo>
  creates directory $KAMINO_ROOT/<forge>/<username>/<repo> and initalizes
  git repository with the matching remote set to "origin"
kamino help
  display this message
```

## Motivation

I wrote this because I'm too lazy to maintain any kind of structure otherwise. Without it everything just ends up in `~/code` and I forget which org or even which forge a given repo comes from.

## TODO

* Test support for anything that's not github.
* Cleaner installation (homebrew?)

## License

This code is licensed under the terms found in `LICENSE.txt` (Standard MIT License)
