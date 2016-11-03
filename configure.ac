#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([MCPE Neutralism Addon],
        [0.1],
        [https://github.com/depressed-pho/mcpe-neutralism-addon/issues],
        [],
        [https://github.com/depressed-pho/mcpe-neutralism-addon])
AM_INIT_AUTOMAKE([1.9])
AC_CONFIG_SRCDIR([src/pack_manifest.yaml.in])

AM_MAINTAINER_MODE
AM_SILENT_RULES([yes])

# Checks for programs.
AC_ARG_VAR([YAML2JSON], [The yaml2json command @<:@autodetected@:>@])
AC_CHECK_PROGS([YAML2JSON], [yaml2json])
AS_IF([test "x$YAML2JSON" = x],
      [AC_MSG_ERROR([You need to install the yamljs npm package. Run `npm install -g yamljs'.])])

AC_ARG_VAR([ZIP], [The Info-Zip zip command @<:@autodetected@:>@])
AC_CHECK_PROGS([ZIP], [zip])
AS_IF([test "x$ZIP" = x],
      [AC_MSG_ERROR([You need to install the Info-Zip zip command.])])

# Checks for libraries.

# Checks for header files.

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.

AC_CONFIG_FILES([
    Makefile
    img/Makefile
    src/Makefile
    src/pack_manifest.yaml
])
AC_OUTPUT
