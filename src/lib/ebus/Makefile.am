AM_CXXFLAGS = -I$(top_srcdir)/src \
	      -isystem$(top_srcdir) \
	      -Wconversion -Wno-unused-parameter

noinst_LIBRARIES = libebus.a

libebus_a_SOURCES = \
		    result.h result.cpp \
		    symbol.h symbol.cpp \
		    filereader.h filereader.cpp \
		    datatype.h datatype.cpp \
		    data.h data.cpp \
		    device.h device.cpp \
		    message.h message.cpp \
		    stringhelper.h stringhelper.cpp

if CONTRIB
SUBDIRS = contrib
endif

distclean-local:
	-rm -f Makefile.in
