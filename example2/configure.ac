AC_INIT([x11-example],[1.0])
AC_CONFIG_SRCDIR([x11-example.c])
AC_CONFIG_AUX_DIR([build-aux])
AM_INIT_AUTOMAKE([-Wall -Werror foreign])
AC_PROG_CC

#Check for X11
#Exports variables X_CFLAGS and X_LIBS
AC_PATH_XTRA

#AC_PATH_XTRA doesn't error out by default,
#and we must do it manually instead.
#See https://www.gnu.org/software/autoconf/manual/autoconf-2.67/html_node/System-Services.html for explanation of below test.
AS_IF([test "X$no_x" = "Xyes"],[AC_MSG_ERROR([Could not find X11])])

AC_CONFIG_FILES([Makefile])
AC_OUTPUT
