# Copyright (C) 2008-2013 Assaf Gordon <assafgordon@gmail.com>
#  
# This file is free software; as a special exception the author gives
# unlimited permission to copy and/or distribute it, with or without 
# modifications, as long as this notice is preserved.
# 
# This program is distributed in the hope that it will be useful, but
# WITHOUT ANY WARRANTY, to the extent permitted by law; without even the
# implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.


bin_PROGRAMS = fasta_formatter

AM_CPPFLAGS = $(CC_WARNINGS) $(GTEXTUTILS_CFLAGS) \
	-I$(top_srcdir)/src/libfastx

LDADD = $(GTEXTUTILS_LIBS) ../libfastx/libfastx.a $(LT_LDFLAGS)

fasta_formatter_SOURCES = fasta_formatter.cpp \
			sequence_writers.h

