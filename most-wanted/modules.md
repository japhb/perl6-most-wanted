# Most Wanted Modules

These are the most-wanted pure Perl 6 modules (as opposed to
[native library bindings](bindings.md)).  These may be direct ports of Perl 5
libraries, but that is not necessarily the case.


## Algorithms

* Diff (WIP: [Algorithm::Diff](https://github.com/Takadonet/Algorithm--Diff/))

## Configuration

* INI (WIP: [Config::INI](https://github.com/tadzik/perl6-Config-INI/))
* GitLike
* Netrc


## Cryptography and security

* Digest (unified interface) (WIP: [Digest](https://github.com/grondilu/libdigest-perl6/))
  + MD5 (WIP: [Digest::MD5](https://github.com/cosimo/perl6-digest-md5/))
  + SHA* (WIP: [Digest::SHA256](https://github.com/soh-cah-toa/p6-digest-sha256/))
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
* Binary interchange of structured data
  + BSON (WIP: [BSON](https://github.com/bbkr/BSON/))
* Web markup
  + HTML
  + CSS
  + SVG
* Documents
  + Pod::* (some functionality handled internally, but lots to fill in)
  + Markdown
  + PDF
* File metadata
  + Image::Exiftool
  + MP3 tags
* Email
  + Email::Simple (WIP: [Email::Simple](https://github.com/retupmoca/p6-Email-Simple/))
  + MIME
  + Base64
  + QuotedPrint
* RSS/Atom


## Data processing

* Data::GUID
* Data::Visitor


## Databases

* DBI (WIP: [DBIish](https://github.com/perl6/DBIish/) -- for drivers see [native bindings](bindings.md))
* DBM?
* Key-value stores
  + Memcached (WIP: [Cache::Memcached](https://github.com/cosimo/perl6-cache-memcached/))


## Development

* Corelist
* Ecosystem (WIP: [panda](https://github.com/tadzik/panda/))
  + File::ShareDir
  + Pod::Cpandoc
  + CPAN::Mini equivalent?
  + App::cpanoutdated (equivalent for panda)
* App::Grindperl
* Benchmarking (WIP: [Benchmark](https://github.com/perlpilot/benchmark/))
* Debugging (WIP: [Rakudo::Debugger](https://github.com/jnthn/rakudo-debugger/))
  + Carp::REPL
  + Devel::FindRef
  + Devel::PartialDump
* Tracing
  + Devel::Trace
  + Devel::STDERR::Indent
* Profiling
  + Grammars (WIP: [Grammar::Profiler::Simple](https://github.com/perlpilot/Grammar-Profiler-Simple/))
  + Devel::NYTProf?
* Tidying
  * Perl::Tidy
  * Code::TidyAll
* Editor/IDE interfaces
  + Proc::InvokeEditor
  + Vi::QuickFix?
* Project lifecycle
  + Dist::Zilla
  + CPAN::Uploader
* License management
  + Software::License/App::Software::License
* Source management
  + Git::Wrapper


## Internationalization

* App::Uni
* Unicode::Collate?
* Unicode::UCD?
* Unicode::Tussle?
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
* App::Whiff


## Logging

* pluggable logging
  + syslog
  + Windows logging
  + file/handle


## Misc

* File::pushd


## Networking

* URI (WIP: [URI](https://github.com/ihrd/uri/))
* Email
  + POP3
  + IMAP
  + SMTP
  + Email::Sender
* HTTP
  + LWP or modern equivalent (Mojo::*?)
  + Mechanize
  + Plack/Task::Plack
  + RobotUA?
* RPC
  + SOAP
  + XML-RPC?
* Other protocols
  + FTP
  + NNTP
  + Ping
  + Telnet
* Internet services
  + App::Nopaste
  + Net::GitHub::V3
  + App::ph
* Security
  + Mozilla::CA


## Text processing

* Templating
* Specialized tasks
  + Text::Wrap
  + Text::Tabs
  + Text::Abbrev
* Regex/Grammar utilities
  + Regexp::Common


## Testing

* Smoking and reporting
  + Test::Reporter
  + CPANTS
* Harnesses
  + TAP::Parser
  + Test::Harness
  + App::Prove
  + App::ForkProve
  + Test::Aggregate?
* Test output
  + Test::Differences
  + Test::Deep
  + Test::Pretty?
* Completeness
  + Code coverage
  + Pod coverage
* Specific tests
  + Test::CPAN::Meta (but for panda)
  + Test::Without::Module
  + Test::Requires
  + Test::Spelling
  + Test::NoTabs


## Unix

* IO::Pty/IO::Pty::Easy
* open2/open3
* shared mem
* Fcntl
* POSIX
* User::grent
* User::pwent
* Daemonize


## User interfaces

* Command line
  + Term::UI?
  + Term::ProgressBar or some variant?
* Terminal
  + Term::ANSIColor
  + Term::Cap
  + Term::Complete
  + Term::ReadLine
  + App::Ttyrec?
  + App::Termcast?
* Charting/Graphing
  + Chart::Clicker


## Utilities

* ExtUtils::Command or Shell::Command
* App::Ack
* Email::Filter
