LOBJEXT = lo

EXTRA_DIST = firetalk.m4

noinst_LTLIBRARIES = libfiretalk.la
libfiretalk_la_SOURCES = \
	firetalk.c \
	md5.c \
	firetalk-int.h \
	firetalk-errors.h \
	irc.c \
	pdutil.c \
	lily.c

# toc2.c toc2_uuids.h

check_PROGRAMS = tester toctest
tester_SOURCES = \
	tester.c
tester_LDADD = \
	libfiretalk.la
toctest_SOURCES = \
	toctest.c
toctest_LDADD = \
	libfiretalk.la

#TESTS = ${check_PROGRAMS}
TESTS = tester

include_HEADERS = firetalk.h
