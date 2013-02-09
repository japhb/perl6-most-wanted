# Data Sources

In order to figure out what we're missing, the first step is to determine
what is expected or needed.  To do this, I've collected the following sources:

* The Perl 6 setting (for determining what *doesn't* need to be a module)
* The Perl 6 Modules Directory ([text](perl6-module-list.txt) - [json](perl6-module-list.json)) (http://modules.perl6.org/)
* The Perl 6 Ecosystem [Most Wanted Modules](perl6-most-wanted) (https://github.com/perl6/ecosystem/wiki/Most-Wanted-Modules)
* The [Perl 5 bundled modules](perl5-corelist-5.014002) (http://perl5.git.perl.org/perl.git)
* The CPAN Top 100: [Volatile 100](cpan-top-100-volatile-100.tsv) (http://ali.as/top100/)
* (WIP) Perl 5 modules packaged by multiple Linux distros and/or Strawberry Perl
  + In particular, modules in Strawberry or ActivePerl that aren't in Core (au++)
* Task::BeLike::*
  + [DAGOLDEN](task-belike-DAGOLDEN)
  + [DOY](task-belike-DOY), [FLORA](task-belike-FLORA) (AKA rafl), [RJBS](task-belike-RJBS), [SARTAK](task-belike-SARTAK) (sorear++)
* [Requests from module and app authors](requests-from-authors.md)
* [Dog food](dog-food.md): modules, tools, and apps we use
