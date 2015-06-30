AC_CONFIG_MACRO_DIR([m4])
AC_PREREQ([2.69])
AC_INIT([libcxxfileno], [0.1], [srk31@cl.cam.ac.uk])
LT_INIT
AC_CONFIG_SRCDIR([fileno.cpp])
AC_LANG([C++])
AM_INIT_AUTOMAKE([foreign subdir-objects])
AM_MAINTAINER_MODE
AC_PROG_CXX
AX_CXX_COMPILE_STDCXX_11
AC_PROG_LN_S
AC_PROG_INSTALL
AC_CHECK_HEADER([cstdio])
AC_CHECK_HEADER([fstream])
AC_CHECK_HEADER([cerrno])
AC_CHECK_HEADER([iosfwd])
AC_CHECK_HEADER([ext/stdio_filebuf.h])
AC_CHECK_HEADER([ext/stdio_sync_filebuf.h])
AC_OUTPUT([Makefile])
