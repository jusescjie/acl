include ../Makefile.in
#Path for SunOS
ifeq ($(findstring SunOS, $(UNIXNAME)), SunOS)
	EXTLIBS = -liconv
endif
ifeq ($(findstring FreeBSD, $(UNIXNAME)), FreeBSD)
	EXTLIBS = -L/usr/local/lib -liconv
endif
PROG = mime
