AC_INIT([serviceapp], [0.1], [mx3ldev@gmail.com])
AM_INIT_AUTOMAKE([subdir-objects foreign dist-bzip2 no-define tar-pax])
AC_CONFIG_MACRO_DIR([m4])
LT_INIT

AC_PROG_CC
AC_PROG_CXX
AM_PATH_PYTHON
AX_PYTHON_DEVEL

PKG_CHECK_MODULES(ENIGMA2, enigma2)

AC_DEFINE([DEBUG])

AC_CONFIG_FILES([
Makefile
src/Makefile
src/serviceapp/Makefile
src/plugin/Makefile

])
AC_OUTPUT