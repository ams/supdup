#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([FULL-PACKAGE-NAME], [VERSION], [BUG-REPORT-ADDRESS])
AC_CONFIG_SRCDIR([supdup.c])
AC_CONFIG_HEADERS([config.h])
AM_INIT_AUTOMAKE([foreign])

# Checks for programs.
AC_PROG_CC

# Checks for libraries.
AX_WITH_CURSES

# Checks for header files.
AC_HEADER_RESOLV

# Checks for typedefs, structures, and compiler characteristics.
AC_CHECK_DECLS([ns_c_chaos], [], [], [arpa/nameserv.h])
 
# Checks for library functions.

AC_CONFIG_FILES([Makefile])
AC_OUTPUT
