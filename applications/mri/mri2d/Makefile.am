# $Id: Makefile.am 3639 2011-10-05 20:20:30Z keiner $

AM_CPPFLAGS = -I$(top_srcdir)/include

noinst_PROGRAMS = \
  construct_data_2d \
  construct_data_inh_2d1d \
  construct_data_inh_3d \
  reconstruct_data_gridding \
  reconstruct_data_2d \
  reconstruct_data_inh_3d \
  reconstruct_data_inh_2d1d \
  reconstruct_data_inh_nnfft

construct_data_2d_SOURCES = construct_data_2d.c doxygen.h
construct_data_2d_LDADD = $(top_builddir)/libnfft3.la

construct_data_inh_2d1d_SOURCES = construct_data_inh_2d1d.c
construct_data_inh_2d1d_LDADD = $(top_builddir)/libnfft3.la

construct_data_inh_3d_SOURCES = construct_data_inh_3d.c
construct_data_inh_3d_LDADD = $(top_builddir)/libnfft3.la

reconstruct_data_gridding_SOURCES = reconstruct_data_gridding.c
reconstruct_data_gridding_LDADD = $(top_builddir)/libnfft3.la

reconstruct_data_2d_SOURCES = reconstruct_data_2d.c
reconstruct_data_2d_LDADD = $(top_builddir)/libnfft3.la

reconstruct_data_inh_3d_SOURCES = reconstruct_data_inh_3d.c
reconstruct_data_inh_3d_LDADD = $(top_builddir)/libnfft3.la

reconstruct_data_inh_2d1d_SOURCES = reconstruct_data_inh_2d1d.c
reconstruct_data_inh_2d1d_LDADD = $(top_builddir)/libnfft3.la

reconstruct_data_inh_nnfft_SOURCES = reconstruct_data_inh_nnfft.c
reconstruct_data_inh_nnfft_LDADD = $(top_builddir)/libnfft3.la

EXTRA_DIST = 	construct_inh.m \
		construct_readout_time.m \
		precompute_weights.m \
		construct_knots_linogram.m \
		mri_inh.m \
		rms.m \
		construct_knots_radial.m \
		mri.m \
		construct_knots_rose.m \
		visualize_data.m \
		construct_knots_spiral.m \
		phantom.m \
		README
