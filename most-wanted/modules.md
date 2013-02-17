# Most Wanted Modules

These are the most-wanted pure Perl 6 modules (as opposed to
[native library bindings](bindings.md)).  These may be direct ports of Perl 5
libraries, but that is not necessarily the case.


## Configuration

* INI
* Netrc


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

* Archives
  + Tar
  + ZIP
* Delimited Text
  + CSV (WIP: [Text::CSV](https://github.com/masak/csv/))
  + TSV
* Textual interchange of structured data
  + JSON (WIP: [JSON::Tiny](https://github.com/moritz/json/))
  + XML
  + YAML
* MIME
  + Base64
  + QuotedPrint
* PDF
* RSS/Atom


## Data processing


## Databases

* DBI (for drivers see [native bindings](bindings.md))
* DBM?


## Development

* Corelist
* Ecosystem (WIP: [panda](https://github.com/tadzik/panda/))
  + Pod::Cpandoc
  + CPAN::Mini equivalent?
* Dist::Zilla
  + CPAN::Uploader
* App::Grindperl
* Benchmark (WIP: [Benchmark](https://github.com/perlpilot/benchmark/))
* Debugger (WIP: [Rakudo::Debugger](https://github.com/jnthn/rakudo-debugger/))
  + Carp::REPL
* Profiler
  + Grammars (WIP: [Grammar::Profiler::Simple](https://github.com/perlpilot/Grammar-Profiler-Simple/))
  + Devel::NYTProf?
* Editor/IDE interfaces
  + Vi::QuickFix?


## Internationalization

* Unicode::Collate?
* Unicode::UCD?
* App::Uni
* Encodings/charsets other than builtin UTF-8/Unicode
* Maketext
* Locales?
* Standard codes:
  + country
  + currency
  + language
  + script


## IPC

* IPC::Cmd


## Logging

* pluggable logging
  + syslog
  + Windows logging
  + file/handle


## Misc

* File::pushd


## Networking

* Email
  + POP3
  + IMAP
  + SMTP
  + Email::Sender
* HTTP
  + LWP or modern equivalent (Mojo::*?)
  + Mechanize
  + Plack
  + RobotUA?
* RPC
  + SOAP
  + XML-RPC?
* Other
  + FTP
  + NNTP
  + Ping
  + Telnet
  + App::Nopaste


## Text processing

* Templating
* Text::Wrap
* Text::Tabs?
* Text::Abbrev?


## Testing

* TAP::Parser
* Test::Harness/App::Prove
* Coverage
* Pod coverage


## Unix

* open2/open3
* shared mem
* Fcntl
* POSIX
* User::grent
* User::pwent


## User interfaces

* Command line
  + Term::UI?
* Terminal
  + Term::ANSIColor
  + Term::Cap
  + Term::Complete
  + Term::ReadLine


## Utilities

* ExtUtils::Command or Shell::Command
* App::Ack
