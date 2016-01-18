Libsoundio Ada bindings
=======================

This is a set of bindings to Libsoundio, a cross-platform/cross-toolkit sound
input and output library. See https://github.com/andrewrk/libsoundio for more
information.

For the moment the bindings are pretty basic. To use them, just include
`soundio.gpr` to your own project, and make sure to add `-lsoundio` to your
linker switches. You can check [the example](https://github.com/raph-amiard/ada-soundio/blob/master/example) to have more details.

In time I will try to provide idiomatic Ada bindings. Stay tuned !
