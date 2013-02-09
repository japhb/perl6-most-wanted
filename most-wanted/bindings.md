# Most Wanted Native Bindings

These are the native libraries that are most wanted as NativeCall bindings
rather than as Perl 6 source ports.  Often this is because the native library
offers performance or security guarantees that would be difficult or
impossible to provide in HLL code.  In other cases, it is because the library
provides such complex or finicky functionality that it could not be reproduced
in a correct new implementation without great effort -- effort that could be
better spent on [other most-wanted tasks](README-wanted.md).


## Compression

* zlib


## Security

* openssl
