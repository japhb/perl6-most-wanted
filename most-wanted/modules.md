# Most Wanted Modules

These are the most-wanted pure Perl 6 modules (as opposed to
[native library bindings](bindings.md)).  These may be direct ports of Perl 5
libraries, but that is not necessarily the case.


## Configuration


## Cryptography and security

* Digest (unified interface)
  + MD5
  + SHA* (at least SHA1 and SHA256)
* Crypto
  + GPG
  + Block cyphers
    - DES
    - AES
    - Blowfish
    - Twofish
  + Full set of block cypher modes
* RNG
  + MT (Mersenne Twister)
  + TrulyRandom (portable access to OS-provided truly random sources)


## Data formats

* Delimited Text
  + CSV
  + TSV
* MIME
* PDF


## Data processing


## Databases


## Networking

* Email
  + POP
  + IMAP
  + SMTP
* HTTP
  + LWP or modern equivalent
  + Mechanize
  + Plack
* RPC
  + SOAP?
  + XML-RPC?
* Other
  + FTP
  + Telnet


## Text processing

* Templating


## Testing


## User interfaces

### Command line

### Terminal

### GUI

### Web


## Utilities

* ExtUtils::Command or Shell::Command
