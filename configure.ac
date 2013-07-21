#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

#AC_PREREQ([2.68])
AC_INIT(iscsi-name, 0.1, bugs@v10networks.ca)
AC_CONFIG_SRCDIR([iscsi-name.c])
AC_CONFIG_HEADERS([config.h])
AC_PREFIX_DEFAULT([/usr])
AM_INIT_AUTOMAKE(iscsi-name, 0.1)
# Checks for programs.
AC_PROG_CC

# Checks for libraries.

# Checks for header files.
AC_CHECK_HEADERS([fcntl.h stdint.h stdlib.h string.h sys/time.h unistd.h])

# Checks for typedefs, structures, and compiler characteristics.
AC_TYPE_UINT32_T

# Checks for library functions.
AC_CHECK_FUNCS([gettimeofday memset strstr uname])

AC_CONFIG_FILES([Makefile])
AC_OUTPUT
