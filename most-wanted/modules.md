# Most Wanted Modules

These are the most-wanted pure Perl 6 modules (as opposed to
[native library bindings](bindings.md)).  These may be direct ports of Perl 5
libraries, but that is not necessarily the case.

## WIP Tags

If you start implementing a module, but it's not ready for the release to the
public yet, please mark it in the list as WIP (Work In Progress) with a link
to the repository, so other potential authors do not assume no one is working
on this problem.

Once your work is added to the ecosystem, please **remove it from the Most
Wanted list,** even if you're still fleshing out the module.

## Configuration

* GitLike

## Cryptography and security

* Crypto
  + GPG
  + Block cyphers
    - DES
    - Blowfish
    - Twofish
  + Full set of block cypher modes

## Data formats

* Archives
  + Tar (WIP: [Archive::Tar](https://github.com/FROGGS/p6-Archive-Tar))
* Textual interchange of structured data
  + LDIF
      - Net::LDAP portbb
* File metadata
  + Image::Exiftool
* XML-based formats
  + RSS/Atom

## Data processing

* Data::Visito
* Deep::Clone

## Databases

* DBM?
* NoSQL
  + CouchDB (WIP: [Sofa](https://github.com/jonathanstowe/Sofa))
* CHI, Cache::Cache, or similar

## Data Structures

* Trees
  + Data::BinaryTree
  + Data::N-aryTree

## Development

* Corelist
* Ecosystem
  + File::ShareDir
  + Pod::Cpandoc
  + Pod::Checker
  + Test::Pod
  + App::cpanoutdated (equivalent for panda)
* App::Grindperl
* Debugging (WIP: [Rakudo::Debugger](https://github.com/jnthn/rakudo-debugger/))
  + Carp::REPL
  + Devel::FindRef
  + Devel::PartialDump
* Tracing
  + Devel::STDERR::Indent
* Profiling (?? not covered by --profile?)
  + Devel::NYTProf?
* Tidying
  * Perl::Tidy (WIP: [Perl6::Tidy](https://github.com/drforr/perl6-Perl6-Tidy))
  * Code::TidyAll
* Editor/IDE interfaces
  + Vi::QuickFix?
* Project lifecycle
  + Dist::Zilla
  + CPAN::Uploader
* Deployment
  + Carton (WIP: [6pm](https://github.com/FCO/6pm)?)
  + cpanfile
  + Pinto

## Graphics

* Graphics::Magick (port of Perl 5 version)

## Filesystems

* File::Spec (WIP: [File::Spec](https://github.com/FROGGS/p6-File-Spec/))
* File::pushd (WIP: [File::pushd](https://github.com/Emeric54/File-pushd))


## i18n and NLP

Internationalization and Natural Language Processing

* Unicode::Collate?
* Unicode::UCD?
* Unicode::Tussle?
* Unicode::LineBreak?
* Encodings/charsets other than builtin UTF-8/Unicode
* Maketext
* Standard codes: (WIP: [Unicode::CLDR](https://github.com/tbrowder/Unicode-CLDR-Perl6/))
  + country
  + currency
  + language
  + script
* Lingua::Stem::*


## IPC

* IPC::Cmd
* DBus via [sd-bus](http://0pointer.net/blog/the-new-sd-bus-api-of-systemd.html)
* Device::SerialPort


## Logging

* pluggable logging
  + Windows logging
  + file/handle


## Networking

* Email
  + Email::Sender
* HTTP
  + HTTP2 client and server (See [Cro::HTTP](https://github.com/croservices/cro-http))
  + RobotUA?
  + OAuth
  + CGI (WIP: [CGI](https://github.com/tbrowder/CGI-Perl6))
  + Data::Session
  + CGI::Session::Auth
* RPC
  + JSON-RPC (WIP: [JSON::RPC](https://github.com/bbkr/jsonrpc/))
  + SOAP
  + XML-RPC?
* IRC
  + IRC::Utils (WIP: [IRC::Utils](https://github.com/soh-cah-toa/p6-irc-utils/))
* Other protocols
  + NNTP
  + Ping
  + Telnet (WIP: [Net::Telnet](https://github.com/Kaiepi/p6-Net-Telnet/))
* Internet services
  + Net::GitHub::V3
  + App::ph
  + Net::DNS::BIND::Manage (WIP: [Net::DNS::BIND::Manage](https://github.com/tbrowder/Net-DNS-BIND-Manage-Perl6/))
  + API::DigitalOcean (WIP: [API::DigitalOcean](https://github.com/tbrowder/API-DigitalOcean-Perl6/))
  + API::Mailman
  + Net::ACME2
  + WebService::Client
* Security
  + Mozilla::CA
* Automation
  + WWW::Mechanize


## Numerical

* Math::Units (WIP: [Unit::SI](https://github.com/holli-holzer/perl6-Unit-SI) (Name is just temporary)


## Text processing

* Regex/Grammar utilities
  + Regexp::Common
* String utilities
  + Lisp::Format
* Printing
  + PostScript (functions, text output, graphics inclusion, etc.) (WIP: [PostScript::Lib](https://github.com/tbrowder/PostScript-Lib-Perl6))
  + RTF::Writer (WIP: [RTF::Writer](https://github.com/tbrowder/RTF-Writer-Perl6))
  
## Testing

* Smoking and reporting
  + Test::Reporter
  + CPANTS
* Harnesses
  + TAP::Parser
  + App::Prove
  + App::ForkProve
  + Test::Aggregate?
* Test output
  + Test::Differences
  + Test::Deep
  + Test::Pretty?
* Completeness
  + Code coverage
* Specific tests
  + Test::Requires
  + Test::Spelling
* Simulation
  + Test::Without::Modu
* Mocking
  + Mock::Import - *overriding module's imports* ([SO question](http://stackoverflow.com/questions/42645801/how-to-mock-an-imported-subroutine-when-unit-testing-a-module), [IRC discussion](https://irclog.perlgeek.de/perl6/2017-03-07#i_14218539))
  + Mock::Sub - *overriding a module's lexical subroutines* ([IRC discussion](https://irclog.perlgeek.de/perl6/2017-03-07#i_14218601); c.f. [Test::MockModule](https://metacpan.org/pod/Test::MockModule), [Sub::Override](https://metacpan.org/pod/Sub::Override))
  
## Time / Date / Calendar

* Calendar::Any::Util::Calendar
* DateTime::Math::More (WIP: [DateTime::Math::More](https://github.com/tbrowder/DateTime-Math-More-Perl6))
* DateTime::Format::More (WIP: [DateTime::Format::More](https://github.com/tbrowder/DateTime-Format-More-Perl6))
* Date::Calc (port of Perl 5 version)

## Unix

* IO::Select (WIP: [IO::Select](https://github.com/tadzik/IO-Select/))
* IO::Pty/IO::Pty::Easy
* open2/open3
* shared mem
* POSIX (WIP: [POSIX](https://github.com/cspencer/perl6-posix))

## User interfaces

* Command line
  + Term::UI?
* Terminal
  + Term::Cap  (WIP: [Term::Cap](https://github.com/jonathanstowe/p6-Term-Cap))
  + Term::Complete
  + Term::ReadLine
  + App::Ttyrec?
  + App::Termcast?
  + Term::KBD
* Plotting/Charting/Graphing
  + Chart::Clicker

## Utilities

+ App::Ack (WIP: [App::Ack](https://github.com/elohmrow/App-Ack))
* Email::Filter
