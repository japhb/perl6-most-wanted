= Requests from module and app authors

These are core features and/or base modules that various authors need
before they can build/port their modules and apps to Perl 6.


== __sri, primary author of Mojo/Mojolicious

* http://irclog.perlgeek.de/perl6/2013-02-07#i_6422674
  + CORE: unicode
  + CORE: hires time
  + md5/sha1 (existing module already?)
  + base64 (existing module already?)
  + async socket and file IO
  + poll() in addition to non-blocking sockets
  + proper signal handling
  + decent performance
  + zlib
  + openssl
  + threads
  + automatic restart?


== tadzik, panda maintainer and prolific Perl 6 module author

* proper async IO
* libuv binding or the equivalent


== skids, Perl 6 module author

* unsigned sized native types
* diamond role composition
