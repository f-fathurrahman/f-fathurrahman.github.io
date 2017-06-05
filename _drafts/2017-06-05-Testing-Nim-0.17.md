---
layout: post
title: Installing and using Nim
comments: False
categories:
- blog
- 2017
---

# Using NIM

Build NIM using script `build.sh`
```
./build.sh
```
This will build Nim executable.

Install it to some directory, in my case I installed Nim at `$HOME/mysoftwares/nim`.
```
./install.sh $HOME/mysoftwares
```

Compile Nim package manager, `koch`. Make sure that the executable `nim` (in my case it is found
in directory `$HOME/mysoftwares/nim/nim`) is in the `PATH`
```
nim c koch.nim
```

An executable `koch` will be produced. Copy this to `$HOME/mysoftwares/nim/bin` directory.
```
cp koch $HOME/mysoftwares/nim/bin
```


