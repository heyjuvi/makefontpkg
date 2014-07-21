makefontpkg
===========

Name
----

**makefontpkg** - builds a Pacman package from a set of font files

Synopsis
--------

<pre><code>makefontpkg [-h] [-i | -S] [-n <var>NAME</var>] [--ver <var>VER</var>[-<var>REL</var>]] [--desc <var>DESC</var>]
            <var>FILE</var> [<var>FILE</var> ...]</code></pre>

Description
-----------

Builds a Pacman package from a set of TrueType and/or OpenType font files.

Options
-------

  - `-h`, `--help`

    display the help message and quit

  - `-i`, `--install`

    directly install the package instead of building the package

  - `-S`, `--source`, `-s`

    make a source-only tarball instead of building the package

  - <code>-n <var>NAME</var></code>, <code>--name <var>NAME</var></code>

    name of the package; defaults to the name of the first file

  - <code>--ver <var>VER</var>[-<var>REL</var>]</code>

    version and release number of the package; defaults to `1.0.0-1`

  - <code>--desc <var>DESC</var></code>

    description of the package; defaults to "<i>Custom font</i>"

  - <code><var>FILE</var></code>

    font files with extensions `.ttf` or `.otf`
