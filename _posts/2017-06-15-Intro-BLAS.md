---
layout: post
title: Introduction to BLAS (Basic Linear Algebra Subroutine)
comments: True
---

In this post I will give a practical introduction to BLAS.

In common scientific and engineering calculations, we can find
many operations that involve vectors and matrices operations
such as dot product between two vectors, matrix-vector multiplications,
and matrix-matrix multiplication.
A programmer may write their own routines to do such tasks, however,
it is more common to leave this operation to specialized library.

BLAS defines a set of common vectors and matrices operations that are
commonly used in scientific and engineering calculations.
These operations are implemented as a library and can be implemented
by special groups or vendors.
A reference implementation of BLAS can be found in
[NETLIB](www.netlib.org/blas).
