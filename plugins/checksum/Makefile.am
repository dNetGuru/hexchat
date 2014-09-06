libdir = $(hexchatlibdir)

lib_LTLIBRARIES = checksum.la
checksum_la_SOURCES = checksum.c
checksum_la_LDFLAGS = $(PLUGIN_LDFLAGS)
checksum_la_LIBADD = $(GLIB_LIBS) $(OPENSSL_LIBS)
checksum_la_CFLAGS = $(GLIB_CFLAGS) $(OPENSSL_CFLAGS) -I$(top_srcdir)/src/common
