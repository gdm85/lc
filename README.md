This is a port of 'lc' (List files in categories and columns) from MWC (Mark Williams Company) [Coherent UNIX](https://en.wikipedia.org/wiki/Coherent_(operating_system)).

You can find the original source tarball here: http://www.nesssoftware.com/home/mwc/source.php

The original source file is `COHERENT/romana/relic/d/bin/lc.c` in the archive.

## Manual

The original manual page, lightly edited and converted to use modern `-man` macros, is in the file `doc/lc.1`.
On a modern Linux system, it may be viewed with `man ./docs/lc.1`. The original, unaltered manual page source is in `doc/lc.orig.troff`.

A scanned manual page may be viewed below:

![lc manual page](./lc_manual.png)

## Differences from original

I added support of symlinks (`-l` command-line option).

## License

Released with the original [LICENSE](./LICENSE.md).
