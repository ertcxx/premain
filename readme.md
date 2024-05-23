premain
==================

This document proposes changes in the C++ standard text reflecting
the specification of a `pre_main()` function that is called prior to
static initialization. As the name `pre_main` implies,
this function is intended to be called one single time
prior to calling the `main()` function.
