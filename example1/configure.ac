#Initialize autoconf with project name and version number
AC_INIT([hello],[1.0])

#Safety check for when building out of directory.
#i.e. when the configure script is given an option
#of the for '--srcdir=dirname' to specify where the
#sources are located.
AC_CONFIG_SRCDIR([hello.c])

#Store auxilliary build tools
AC_CONFIG_AUX_DIR([build-aux])

#Initialize automake and specify relaxed (foreign) structures.
#Suppresses complaints of project not conforming to GNU standards.
AM_INIT_AUTOMAKE([-Wall -Werror foreign])

#Check for C compiler
AC_PROG_CC

#Tell automake to create a Makefile
AC_CONFIG_FILES([Makefile])

#Generate output
AC_OUTPUT
