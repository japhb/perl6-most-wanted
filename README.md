# perl6-most-wanted

[Lists](most-wanted/README-wanted.md) of most wanted
[core features](most-wanted/features.md),
[native library bindings](most-wanted/bindings.md), and
[modules](most-wanted/modules.md) for Perl 6, along with the
[research](data-sources/README-sources.md) that helped us select them.


## Why do this?

To kickstart active use of Perl 6 for a broad range of tasks, we need to
provide a "distro" release that includes modules covering many common needs
not met by the standard Perl 6 setting.  For a while now this effort has been
led by [Rakudo Star](http://rakudo.org/how-to-get-rakudo/), but
(as of early 2013) it is far from complete; too incomplete in fact to be
useful for any but early adopters.

To make a distro release useful for "early majority" users, the existing
modules need to be filled out (documentation, better error handling, etc.), and
many more modules need to be created (or ported from Perl 5) to fill existing
gaps.  This repo's goal is a gap analysis: a listing of what we have, what we
need, and what's blocking module authors from filling all the gaps.


## Editing

Once a module, feature, or binding has been constructed, rather than removing it from
the document here in which it appears, instead mark it as such and provide a date and
link for the item.
