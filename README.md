Random Go Kifu
==============

## DESCRIPTION
 
Fetches the URL of a random SGF file representing a Go game between
two professionals, and prints that URL to standard output where it is
suitable to use with something like `curl` and then into `sabaki`,
or whatever other SGF editor.

## EXAMPLE

    $ curl `random-gokifu-sgf` -o game.sgf && sabaki game.sgf

## REQUIREMENTS

* Python 3
* BeatifulSoup

## COPYRIGHT
 
Written by Eric James Michael Ritz, 2018

This code belongs to the Public Domain.

## SEE ALSO

* [Python 3 Documentation](https://docs.python.org/3/)
* [Beatiful Soup](https://www.crummy.com/software/BeautifulSoup/)
* [cURL](https://curl.haxx.se/)
* [Smart Game Format](http://www.red-bean.com/sgf/index.html)
* [Sabaki](https://github.com/SabakiHQ/Sabaki)
