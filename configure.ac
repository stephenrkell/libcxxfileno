AC_CONFIG_MACRO_DIR([m4])
AC_PREREQ([2.69])
AC_INIT([libc++fileno], [0.1], [srk31@cl.cam.ac.uk])
LT_INIT
AC_CONFIG_SRCDIR([fileno.cpp])
AC_LANG([C++])
AM_INIT_AUTOMAKE([foreign subdir-objects])
AM_MAINTAINER_MODE
AC_PROG_CXX
AX_CXX_COMPILE_STDCXX_11
AC_PROG_LN_S
AC_PROG_INSTALL
PKG_PROG_PKG_CONFIG
AC_CHECK_HEADERS([cstdio fstream cerrno iosfwd ext/stdio_filebuf.h ext/stdio_sync_filebuf.h], [], [AC_MSG_FAILURE([required standard headers: cstdio fstream cerrno iosfwd ext/stdio_filebuf.h ext/stdio_sync_filebuf.h])])
AC_OUTPUT([Makefile libc++fileno.pc])
