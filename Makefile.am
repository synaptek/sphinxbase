SUBDIRS = src doc include test swig

EXTRA_DIST = \
	autogen.sh \
	m4/ax_pkg_swig.m4 \
	m4/pkg.m4 \
	sphinxbase.pc.in \
	sphinxbase.sln \
	win32/sphinx_cepview/sphinx_cepview.vcxproj \
	win32/sphinx_cepview/sphinx_cepview.vcxproj.filters \
	win32/sphinx_fe/sphinx_fe.vcxproj \
	win32/sphinx_fe/sphinx_fe.vcxproj.filters \
	win32/sphinx_jsgf2fsg/sphinx_jsgf2fsg.vcxproj \
	win32/sphinx_jsgf2fsg/sphinx_jsgf2fsg.vcxproj.filters \
	win32/sphinx_lm_convert/sphinx_lm_convert.vcxproj \
	win32/sphinx_lm_convert/sphinx_lm_convert.vcxproj.filters \
	win32/sphinx_pitch/sphinx_pitch.vcxproj \
	win32/sphinx_pitch/sphinx_pitch.vcxproj.filters \
	win32/sphinx_seg/sphinx_seg.vcxproj \
	win32/sphinx_seg/sphinx_seg.vcxproj.filters \
	win32/sphinxbase/sphinxbase.vcxproj \
	win32/sphinxbase/sphinxbase.vcxproj.filters

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = sphinxbase.pc
CLEANFILES = sphinxbase.pc

ACLOCAL_AMFLAGS = -I m4

doxygen: 
	doxygen ./doc/doxygen.cfg
