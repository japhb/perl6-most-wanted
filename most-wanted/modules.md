# Most Wanted Modules

These are the most-wanted pure Perl 6 modules (as opposed to
[native library bindings](bindings.md)).  These may be direct ports of Perl 5
libraries, but that is not necessarily the case.


## Algorithms

* Diff (WIP: [Algorithm::Diff](https://github.com/Takadonet/Algorithm--Diff/), [Text::Diff](https://github.com/Takadonet/Text--Diff/))
* Levenshtein (WIP: [Text::Levenshtein](https://github.com/thundergnat/Text-Levenshtein/))


## Configuration

* INI (WIP: [Config::INI](https://github.com/tadzik/perl6-Config-INI/))
* GitLike
* Netrc


## Cryptography and security

* Digest (unified interface) (WIP: [Digest](https://github.com/grondilu/libdigest-perl6/))
  + CRC32 (WIP: [String::CRC32](https://github.com/cosimo/perl6-string-crc32/))
  + MD5 (WIP: [Digest::MD5](https://github.com/cosimo/perl6-digest-md5/))
  + SHA* (WIP: [Digest::SHA256](https://github.com/soh-cah-toa/p6-digest-sha256/), [Digest](https://github.com/grondilu/libdigest-perl6))
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
  + CSV (WIP: [Text::CSV](https://github.com/masak/csv/)), [CSV::Parser](https://github.com/tony-o/perl6-csv-parser)
  + TSV [CSV::Parser](https://github.com/tony-o/perl6-csv-parser) #this works with TSV
* Textual interchange of structured data
  + JSON (WIP: [JSON::Tiny](https://github.com/moritz/json/))
    - JSONPath (WIP: [JSON::Path](https://github.com/jnthn/json-path/))
  + XML
    - parse (WIP: [XML::Parser::Tiny](https://github.com/afiskon/p6-xml-parser-tiny/))
    - emit (WIP: [XML::Writer](https://github.com/masak/xml-writer/))
    - full (WIP: [XML](https://github.com/supernovus/exemel/))
  + YAML (WIP: [YAML](https://github.com/ingydotnet/yaml-pm6/))
* Binary interchange of structured data
  + BSON (WIP: [BSON](https://github.com/bbkr/BSON/))
* Web markup
  + HTML
  + CSS
  + SVG (WIP: [SVG](https://github.com/moritz/svg/))
* Documents
  + Pod::* (some functionality handled internally, but lots to fill in)
    - perldoc (WIP: [p6doc](https://github.com/perl6/doc/))
    - Pod::To::HTML (WIP: [Pod::To::HTML](https://github.com/perl6/Pod-To-HTML/))
  + Markdown (WIP: [Text::Markdown](https://github.com/masak/markdown/))
  + PDF
* File metadata
  + Image::Exiftool
  + MP3 tags
* Email
  + Email::Simple (WIP: [Email::Simple](https://github.com/retupmoca/p6-Email-Simple/))
  + MIME (WIP: [Email::MIME](https://github.com/retupmoca/p6-Email-MIME/))
    - MIME::Types (WIP: [MIME::Types](https://github.com/supernovus/perl6-mime-types/))
  + Base64 (WIP: [MIME::Base64](https://github.com/moritz/Perl6-MIME-Base64/), [Enc::MIME::Base64](https://github.com/ronaldxs/perl6-Enc-MIME-Base64/))
  + QuotedPrint (WIP: [MIME::QuotedPrint](https://github.com/retupmoca/p6-MIME-QuotedPrint/))
* XML-based formats
  + RSS/Atom
  + Sitemap-XML (WIP: [Sitemap::XML::Parser](https://github.com/afiskon/p6-sitemap-xml-parser/))


## Data processing

* Data::GUID
* Data::Visitor


## Databases

* DBI (WIP: [DBIish](https://github.com/perl6/DBIish/) -- for drivers see [native bindings](bindings.md))
* DBM?
* NoSQL
  + MongoDB (WIP: [MongoDB](https://github.com/bbkr/mongo-perl6-driver/))
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
  + Grammars (WIP: [Grammar::Debugger](https://github.com/jnthn/grammar-debugger/))
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


## Filesystems

* File::Find (WIP: [File-Tools](https://github.com/tadzik/perl6-File-Tools/))
* File::Spec (WIP: [File::Spec](https://github.com/FROGGS/p6-File-Spec/))
* File::pushd


## Internationalization

* App::Uni
* Unicode::Collate?
* Unicode::UCD?
* Unicode::Tussle?
* Encodings/charsets other than builtin UTF-8/Unicode
* Maketext
* Locales? (WIP: [CLDR::List](https://github.com/perl-cldr/cldr-list-pm6/))
* Standard codes:
  + country (WIP: [Locale::US](https://github.com/perlpilot/p6-Locale-US))
  + currency
  + language
  + script
* Lingua::* (WIP: [Lingua::EN::Syllable](https://github.com/coke/p6-lingua-en-syllable), [Lingua::EN::Numbers::Ordinal](https://github.com/lue/Lingua--EN--Numbers--Ordinal/), [Lingua::EN::Sentence](https://github.com/dginev/perl6-Lingua-EN-Sentence/), [Lingua::Number](https://github.com/labster/p6-Lingua-Number/))


## IPC

* IPC::Cmd
* App::Whiff
* IO::Capture (WIP: [IO::Capture::Simple](https://github.com/sergot/IO-Capture-Simple/))


## Logging

* pluggable logging
  + syslog
  + Windows logging
  + file/handle


## Networking

* URI (WIP: [URI](https://github.com/ihrd/uri/))
* Email
  + POP3 (WIP: [Net::POP3](https://github.com/retupmoca/P6-Net-POP3/))
  + IMAP
  + SMTP (WIP: [Net::SMTP](https://github.com/retupmoca/P6-Net-SMTP/))
  + Email::Sender
* HTTP
  + LWP or modern equivalent (Mojo::*?)
    - LWP::Simple (WIP: [LWP::Simple](https://github.com/cosimo/perl6-lwp-simple/))
    - HTTP::Client (WIP: [HTTP::Client](https://github.com/supernovus/perl6-http-client/))
    - Curl (WIP: [Net::Curl](https://github.com/azawawi/perl6-net-curl/))
  + PSGI (WIP: [HTTP::Easy](https://github.com/supernovus/perl6-http-easy/), [HTTP::Server::Simple](https://github.com/mberends/http-server-simple/))
  + Misc
    - Status (WIP: [HTTP::Status](https://github.com/supernovus/perl6-http-status/))
  + Plack/Task::Plack
  + Mechanize
  + RobotUA?
* RPC
  + JSON-RPC (WIP: [JSON::RPC](https://github.com/bbkr/jsonrpc/))
  + SOAP
  + XML-RPC?
* IRC
  + IRC::Utils (WIP: [IRC::Utils](https://github.com/soh-cah-toa/p6-irc-utils/))
  + Net::IRC::Bot (WIP: [Net::IRC::Bot](https://github.com/TiMBuS/Net--IRC/))
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
  + Any text
    - TT (WIP: [Template6](https://github.com/supernovus/template6/))
    - Mojo::Template (WIP: [Template::Mojo](https://github.com/tadzik/Template-Mojo/))
  + HTML (WIP: [HTML::Template](https://github.com/masak/html-template/))
* Specialized tasks
  + Text::Wrap/Text::Tabs (WIP: [Text-Tabs-Wrap](https://github.com/flussence/Text-Tabs-Wrap/))
  + Text::Abbrev (WIP: [Text::Abbrev](https://github.com/GlitchMr/perl6-Text-Abbrev/))
* Regex/Grammar utilities
  + Regexp::Common


## Testing

* Smoking and reporting
  + Test::Reporter
  + CPANTS
* Harnesses
  + TAP::Parser
  + Test::Harness (WIP: [Test::Harness](https://github.com/tadzik/Test-Harness/))
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
  + Test::Requires
  + Test::Spelling
  + Test::NoTabs
* Simulation
  + Test::Without::Module
  + Test::Mock (WIP: [Test::Mock](https://github.com/jnthn/test-mock/))


## Unix

* IO::Select (WIP: [IO::Select](https://github.com/tadzik/IO-Select/))
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
  + IO::Prompter (WIP: [IO::Prompter](https://github.com/colomon/io-prompter/))
  + Term::ProgressBar (WIP: [Term::ProgressBar](https://github.com/sergot/Term--ProgressBar/))
  + Term::UI?
* Terminal
  + Term::ANSIColor (WIP: [Term::ANSIColor](https://github.com/tadzik/perl6-Term-ANSIColor/))
  + Term::Cap
  + Term::Complete
  + Term::ReadLine
  + App::Ttyrec?
  + App::Termcast?
* Plotting/Charting/Graphing
  + SVG::Plot (WIP: [SVG::Plot](https://github.com/moritz/svg-plot/))
  + Chart::Clicker


## Utilities

* ExtUtils::Command or Shell::Command (WIP: [File-Tools](https://github.com/tadzik/perl6-File-Tools/))
* App::Ack
* Email::Filter
