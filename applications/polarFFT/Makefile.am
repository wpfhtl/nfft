# $Id: Makefile.am 3639 2011-10-05 20:20:30Z keiner $

AM_CPPFLAGS = -I$(top_srcdir)/include

noinst_PROGRAMS = polar_fft_test mpolar_fft_test linogram_fft_test

polar_fft_test_SOURCES = polar_fft_test.c doxygen.h
polar_fft_test_LDADD = $(top_builddir)/libnfft3.la

mpolar_fft_test_SOURCES = mpolar_fft_test.c
mpolar_fft_test_LDADD = $(top_builddir)/libnfft3.la @fftw3_LDFLAGS@ @fftw3_LIBS@

linogram_fft_test_SOURCES = linogram_fft_test.c
linogram_fft_test_LDADD = $(top_builddir)/libnfft3.la @fftw3_LDFLAGS@ @fftw3_LIBS@

EXTRA_DIST = phantom.m fft_test.m README
