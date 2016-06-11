# Most Wanted Native Bindings

These are the native libraries that are most wanted as NativeCall bindings
rather than as Perl 6 source ports.  Often this is because the native library
offers performance or security guarantees that would be difficult or
impossible to provide in HLL code.  In other cases, it is because the library
provides such complex or finicky functionality that it could not be reproduced
in a correct new implementation without great effort -- effort that could be
better spent on [other most-wanted tasks](README-wanted.md).


## Archives and Compression

* zlib (WIP: [Compress::Zlib](https://github.com/retupmoca/P6-Compress-Zlib/))
* bzip2 ([Compress::Bzip2](https://github.com/Altai-man/perl6-Compress-Bzip2))
* 7zip (7z.so/lib7zip)


## Databases

* DBD::
  + MySQL (TODO: proper placeholder / prepared statements)
  + Postgres (TODO: binary data, casting to appropriate types)
  + SQLite (done)


## Image processing

* Canvas and/or GD (WIP: [GD](https://github.com/mrhdias/perl6-GD/), [Cairo](https://github.com/timo/cairo-p6))
* Charting/Graphing
* ImageMagick or similar (WIP: [MagickWand](https://github.com/azawawi/perl6-magickwand))


## i18n and Text processing

Internationalization and Text processing

* [ICU](http://site.icu-project.org/)
* [Snowball](http://snowball.tartarus.org/) (WIP: [perl6-snowball](https://github.com/Sufrostico/perl6-snowball) )

## NLP and Machine Learning

Natural Language Processing and Machine Learning

* [LIBSVM](https://github.com/cjlin1/libsvm)
* [LIBLINEAR](https://github.com/cjlin1/liblinear)
* [XGBoost](https://github.com/dmlc/xgboost)
* [MeCab](http://mecab.googlecode.com/svn/trunk/mecab/doc/index.html)

## Security

* openssl (WIP: [SSL](https://github.com/grondilu/openssl/), [OpenSSL](https://github.com/sergot/openssl/))
* ssh


## User interfaces

* Terminal
  + curses (WIP: [NCurses](https://github.com/azawawi/perl6-ncurses/))
  + readline (WIP: [Readline](https://github.com/drforr/perl6-readline))
* GUI
  + Qt
  + Gtk (WIP: [GTK::Simple](https://github.com/perl6/gtk-simple/))
* 2D Graphics
  + SDL (WIP: [SDL](https://github.com/PerlGameDev/SDL6/), [SDL2](https://github.com/timo/SDL2_raw-p6))
* 3D Graphics
  + OpenGL

## Other

* XML
  + Libxml2 (WIP: [XML::LibXML](https://github.com/FROGGS/p6-XML-LibXML))
  + Libxslt
* GeoIP (WIP: [GeoIP](https://github.com/bbkr/GeoIPerl6))
* [libgit2](https://libgit2.github.com/)
* spidev (similarly to [py-spidev](https://github.com/doceme/py-spidev))
