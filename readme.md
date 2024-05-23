premain
==================

This document proposes changes in the C++ standard text reflecting
the specification of a `pre_main()` function that is called prior to
static initialization.

Intent:
  - As the name `pre_main` implies, this function is intended to be called one single time.
  - It should be called even _prior_ static initialization which is, itself, called _prior_ to calling the `main()` function.
