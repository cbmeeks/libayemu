lib_LTLIBRARIES         = libayemu.la
libayemu_la_SOURCES     = ay8912.c lh5dec.c vtxfile.c psgfile.c stcfile.c player.c

## info autobook, 11.4 Library Versioning
libayemu_la_LDFLAGS     = -no-undefined -release 0.95 -version-info 0:0:0
AM_CPPFLAGS             = -Wall -I$(top_srcdir)/include

check_PROGRAMS = test
test_SOURCES = test.c
