---
layout: post
title:  "Building ABINIT"
---

First, download the ABINIT distribution and extract it.

I use the standard command:

```
./configure
make
make install
```

I usually install ABINIT locally, so I use `--prefix` option to `./configure` script:
```
./configure --prefix=/home/efefer/local/abinit-8.6.1
```

By default, the `configure` script did not enable compilation with MPI.
To enable this I defined:
```
CC=mpicc
CXX=mpicxx
FC=mpif90
```
before calling the configure script.

```
CC=mpicc CXX=mpicxx FC=mpif90 ./configure --prefix=/home/efefer/local/abinit-8.6.1
```
