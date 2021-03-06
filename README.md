[![Build Status](https://travis-ci.org/cea-sec/ivre.svg)](https://travis-ci.org/cea-sec/ivre)

This file is part of IVRE.

Copyright 2011 - 2015 [Pierre LALET](mailto:pierre.lalet@cea.fr)

# What is it? #

IVRE (Instrument de veille sur les réseaux extérieurs) or DRUNK
(Dynamic Recon of UNKnown networks) is a network recon framework,
including two modules for passive recon (one
[p0f](http://lcamtuf.coredump.cx/p0f/)-based and one
[Bro](https://www.bro.org/)-based) and one module for active recon
(mostly [Nmap](http://nmap.org/)-based, with a bit of
[ZMap](https://zmap.io/)).

The advertising slogans are:

  - (in French): IVRE, il scanne Internet.
  - (in English): Know the networks, get DRUNK!

The names IVRE and DRUNK have been chosen as a tribute to "Le
Taullier".

# Overview #

See [doc/SCREENSHOTS](doc/SCREENSHOTS.md) for an overview (of the Web
interface). We also have a demonstration instance,
[contact us](#contact) to get an access.

A few
[blog posts](http://pierre.droids-corp.org/blog/html/tags/ivre.html)
have been written to show some features of IVRE.

# Documentation #

See [doc/README](doc/README.md) (and `doc/*` files) for more
information.

On a server with the IVRE web server properly installed with a
Dokuwiki notepad, the `doc/*` files are available under the `doc:`
namespace (e.g., `doc:readme` for the [doc/README](doc/README.md)
file).

On a client with IVRE installed, you can use a `--help` option with
most IVRE CLI tools, and use `help(ivre.module)` with most IVRE Python
sub-modules.

# License #

IVRE is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

IVRE is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
[along with IVRE](doc/LICENSE.md). If not, see [the gnu.org web
site](http://www.gnu.org/licenses/).

# Support #

Try `--help` for the CLI tools, `help()` under Python and the "HELP"
button in the web interface.

Feel free to contact the author and offer him a beer if you need help!

If you don't like beer, a good scotch or any other good alcoholic
beverage will do (it is the author's unalienable right to decide
whether a beverage is good or not).

# Contributing #

Code contributions (pull-requests) are of course welcome!

The project needs scan results and capture files that can be provided
as examples. If you can contribute some samples, or if you want to
contribute some samples and would need some help to do so, or if you
can provide a server to run scans, please contact the author.

# Contact #

For both support and contribution, the
[repository](https://github.com/cea-sec/ivre) on Github should be
used: feel free to create a new issue or a pull request!

You can also try to use the e-mail `ivre` on the domain
`droids-corp.org`, or to join the IRC chan
[#ivre](irc://irc.freenode.net/%23ivre) on
[Freenode](https://freenode.net/).
