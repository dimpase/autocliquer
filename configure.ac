#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.67])
AC_INIT([cliquer], [1.21], [dimpase@gmail.com])
AM_INIT_AUTOMAKE
LT_PREREQ([2.2])
LT_INIT([dlopen,shared,no-undefined])
AC_CONFIG_MACRO_DIR([m4])
AC_CONFIG_SRCDIR([src/cl.c])
AC_CONFIG_HEADERS([config.h])

# Checks for programs.
AC_PROG_CC
AC_PROG_INSTALL
AC_PROG_MAKE_SET
AM_PROG_CC_C_O

AC_CONFIG_FILES([Makefile src/Makefile lib/Makefile include/Makefile test/Makefile])

# Checks for header files.
AC_CHECK_HEADERS(limits.h stddef.h stdlib.h string.h sys/time.h sys/times.h unistd.h ctype.h time.h getopt.h)

# Checks for typedefs, structures, and compiler characteristics.
AC_TYPE_SIZE_T

# Checks for library functions.
AC_FUNC_MALLOC
AC_CHECK_FUNCS(getopt getopt_long setvbuf strcasecmp gettimeoftheday)

AC_OUTPUT
