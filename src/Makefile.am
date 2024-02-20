## Process this file with automake to produce Makefile.in

## Created by Anjuta

AM_CPPFLAGS = \
	-DPACKAGE_LOCALE_DIR=\""$(localedir)"\" \
	-DPACKAGE_SRC_DIR=\""$(srcdir)"\" \
	-DPACKAGE_DATA_DIR=\""$(pkgdatadir)"\" \
	$(ADDLINK_CFLAGS)

AM_CFLAGS =\
	 -Wall\
	 -g

bin_PROGRAMS = addlink

addlink_SOURCES = \
	main.cc

addlink_LDFLAGS = 

addlink_LDADD = $(ADDLINK_LIBS)


if NATIVE_WIN32
addlink_LDFLAGS += -mwindows
endif
