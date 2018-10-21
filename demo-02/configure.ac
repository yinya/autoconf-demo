#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT(test, 1.0, yinya@outlook.com)
AC_CONFIG_SRCDIR([src/ModuleA/apple/core/test.c])
AC_CONFIG_HEADERS([config.h])
AM_INIT_AUTOMAKE

# Checks for programs.
AC_PROG_CC

# Checks for libraries.
AC_CHECK_LIB([pthread], [pthread_rwlock_init])
AC_PROG_RANLIB
# Checks for header files.

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.
AC_OUTPUT([Makefile
        src/lib/Makefile
        src/ModuleA/apple/core/Makefile
        src/ModuleA/apple/shell/Makefile
        ])
AC_OUTPUT
