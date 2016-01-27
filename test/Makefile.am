TESTS = testcases
check_HEADERS = testcase-large-exact8.h testcase-large-w-60-64-mxml.h testcase-large-over8.h testcase-large-w-over60.h
check_PROGRAMS = testcases
dist_pkgdata_DATA = testcase-large.b  testcase-large-w.b  testcase-small.a

testcases_SOURCES = testcases.c
testcases_CPPFLAGS = -I$(top_srcdir)/include
testcases_LDADD=../lib/libcliquer.la
