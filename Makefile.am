ACLOCAL_AMFLAGS = -I m4
lib_LTLIBRARIES = libc++fileno.la
libc__fileno_la_SOURCES = fileno.cpp
pkginclude_HEADERS = fileno.hpp
extra_DIST = libc++fileno.pc.in
pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = libc++fileno.pc

lib/libc++fileno.so: $(lib_LTLIBRARIES)
	mkdir -p lib && cd lib && ln -sf ../.libs/libc++fileno.so .

lib/libc++fileno.so.0: $(lib_LTLIBRARIES)
	mkdir -p lib && cd lib && ln -sf ../.libs/libc++fileno.so.0 .

all: lib/libc++fileno.so lib/libc++fileno.so.0
