bin_PROGRAMS = x11-example

x11_example_SOURCES = x11-example.c

x11_example_CFLAGS = @X_CFLAGS@

#AX_PATH_XTRA only specifies the root of X11,
#we still have to include -lX11 ourselves.
x11_example_LDADD = @X_LIBS@ -lX11

#NOTE: x11_example_LDFLAGS adds the linker flag before
#	   the object files on command line, which may be
#	   the wrong order (as in this case).



