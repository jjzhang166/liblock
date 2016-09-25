#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([liblock], [1.0.0], [gozfree@163.com])
lt_major=1
lt_revision=0
lt_age=0
AC_SUBST([lt_major])
AC_SUBST([lt_revision])
AC_SUBST([lt_age])
AC_CONFIG_AUX_DIR([scripts])
AM_INIT_AUTOMAKE
AC_PROG_LIBTOOL
AC_CONFIG_SRCDIR([liblock.c])
AC_CONFIG_HEADERS([config.h])
AC_CONFIG_MACRO_DIRS([m4])

# Checks for programs.
AC_PROG_CC

# Checks for libraries.

# Checks for header files.
AC_CHECK_HEADERS([inttypes.h stdint.h stdlib.h string.h sys/time.h unistd.h])

# Checks for typedefs, structures, and compiler characteristics.
AC_TYPE_INT64_T
AC_TYPE_UINT64_T

# Checks for library functions.
AC_CHECK_FUNCS([clock_gettime gettimeofday strerror strtoul])

AC_CONFIG_FILES([Makefile])
AC_OUTPUT
