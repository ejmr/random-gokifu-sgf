Random Go Kifu
==============

## DESCRIPTION
 
Fetches the URL of a random SGF file representing a Go game between
two professionals, and prints that URL to standard output where it is
suitable to use with something like `curl` and then into `sabaki`,
or whatever other SGF editor.

## EXAMPLE

    $ curl `random-gokifu-sgf` -o game.sgf && sabaki game.sgf

**Note:** The program `sabaki` does not accept a filename from
the command-line like in this example.  The example is meant to be
illustrative, and not something you should blindly copy-paste into
your shell.

## REQUIREMENTS

* Python 3.6
* BeautifulSoup 4

The program may work with older versions of Python 3 and the BeautifulSoup
library but we do not test against them.  We will not address bug reports
related to using older versions of the requirements listed above.

## INSTALLATION

    pip install -r ./requirements.txt

**Note:** Many systems which have both Python 2 and Python 3 tend to
use `pip` for Python 2 libraries.  If you are using such a system then
you will probably want to use `pip3` in the command above.  Use the
`--version` flag to determine exactly which `pip` you are using.

## COPYRIGHT
 
Written by Eric James Michael Ritz, 2018

This code belongs to the Public Domain.

## SEE ALSO

* [Python 3 Documentation](https://docs.python.org/3/)
* [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/)
* [cURL](https://curl.haxx.se/)
* [Smart Game Format](http://www.red-bean.com/sgf/index.html)
* [Sabaki](https://github.com/SabakiHQ/Sabaki)
