Installation Instructions for procps
====================================
Depending on how you retrieve this code you
may need to run the `autogen.sh` program to create the
configure script. If you have a configure script already then
you may not need to do this.

A typical installation would go something like

    ./autogen.sh
    ./configure
    make
    make install

The configure script has a lot of options, so please have a read
of `configure --help` to see what they are and what they are used
for.

Testing
-------
procps has a series of test scripts (and more are welcome if they
are repeatable). You will need to install DejaGNU to run it and
it is simply:

    make check
