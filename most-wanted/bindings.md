# Most Wanted Native Bindings

These are the native libraries that are most wanted as [NativeCall](https://docs.raku.org/language/nativecall#index-entry-nativecall) bindings
rather than as Raku source ports.  Often this is because the native library
offers performance or security guarantees that would be difficult or
impossible to provide in HLL code.  In other cases, it is because the library
provides such complex or finicky functionality that it could not be reproduced
in a correct new implementation without great effort -- effort that could be
better spent on [other most-wanted tasks](README-wanted.md).


## Archives and Compression

* 7zip (7z.so/lib7zip)


## Databases

* DBD::
  + MySQL (TODO: proper placeholder / prepared statements)
  + Postgres (TODO: binary data, casting to appropriate types)


## Image processing

* Canvas and/or GD (WIP: [GD](https://github.com/mrhdias/perl6-GD/))
* Charting/Graphing
* ImageMagick or similar (WIP: [MagickWand](https://github.com/azawawi/perl6-magickwand))

## i18n and Text processing

Internationalization and Text processing

* [ICU](http://site.icu-project.org/)
* [Snowball](http://snowball.tartarus.org/) (WIP: [perl6-snowball](https://github.com/Sufrostico/perl6-snowball) )

## NLP and Machine Learning

Natural Language Processing and Machine Learning

* [LIBSVM](https://github.com/cjlin1/libsvm) (WIP: [Algorithm::LibSVM](https://github.com/titsuki/p6-Algorithm-LibSVM) )
* [LIBLINEAR](https://github.com/cjlin1/liblinear)
* [XGBoost](https://github.com/dmlc/xgboost)

## Security

* ssh


## User interfaces

* Terminal
  + curses (WIP: [NCurses](https://github.com/azawawi/perl6-ncurses/))
  + readline (WIP: [Readline](https://github.com/drforr/perl6-readline))
* GUI
  + Qt
  + WxWidgets
  + Tcl, Tcl::Tk (WIP: [Tcl](https://github.com/vadrer/perl6-tcl))
* 2D Graphics
  + SDL (WIP: [SDL](https://github.com/PerlGameDev/SDL6/), [SDL2](https://github.com/timo/SDL2_raw-p6))
* 3D Graphics
  + OpenGL
  + [Vulkan](https://en.wikipedia.org/wiki/Vulkan_%28API%29)

## Mail

* MTA
  + [libmilter](https://github.com/opnsense/src/tree/master/contrib/sendmail/libmilter)
  
## Other

* GeoIP (WIP: [GeoIP](https://github.com/bbkr/GeoIPerl6))
* [libgit2](https://libgit2.github.com/) (WIP [LibGit2](https://github.com/CurtTilmes/perl6-libgit2))
* spidev (similarly to [py-spidev](https://github.com/doceme/py-spidev))
* [rsync](https://rsync.samba.org/) 
