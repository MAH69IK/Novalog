AM_CFLAGS = $(WFLAGS)

sbin_PROGRAMS = \
	novalog

AM_CPPFLAGS = \
	-DCONFDIR=\"$(sysconfdir)\" \
	-I$(top_srcdir)/gnulib/lib

novalog_SOURCES = \
	helpers.h \
	novalog.c \
	novalog.h \
	novalog_p.h
	syslognames.h
novalog_LDADD = $(top_builddir)/gnulib/lib/libgnu.a
