ACLOCAL_AMFLAGS = -I m4
lib_LTLIBRARIES = liblock.la
liblock_la_SOURCES = liblock.c
include_HEADERS = liblock.h
liblock_la_LDFLAGS = -version-info @lt_major@:@lt_revision@:@lt_age@
liblock_la_CFLAGS = -Werror

noinst_PROGRAMS = test_liblock
test_liblock_SOURCE = test_liblock.c
test_liblock_LDADD = -llock -lpthread
