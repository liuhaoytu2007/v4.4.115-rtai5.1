# GNUmakefile.in generated by automake 1.14.1 from GNUmakefile.am.
# base/wd/GNUmakefile.  Generated from GNUmakefile.in by configure.

# Copyright (C) 1994-2013 Free Software Foundation, Inc.

# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.




am__is_gnu_make = test -n '$(MAKEFILE_LIST)' && test -n '$(MAKELEVEL)'
am__make_running_with_option = \
  case $${target_option-} in \
      ?) ;; \
      *) echo "am__make_running_with_option: internal error: invalid" \
              "target option '$${target_option-}' specified" >&2; \
         exit 1;; \
  esac; \
  has_opt=no; \
  sane_makeflags=$$MAKEFLAGS; \
  if $(am__is_gnu_make); then \
    sane_makeflags=$$MFLAGS; \
  else \
    case $$MAKEFLAGS in \
      *\\[\ \	]*) \
        bs=\\; \
        sane_makeflags=`printf '%s\n' "$$MAKEFLAGS" \
          | sed "s/$$bs$$bs[$$bs $$bs	]*//g"`;; \
    esac; \
  fi; \
  skip_next=no; \
  strip_trailopt () \
  { \
    flg=`printf '%s\n' "$$flg" | sed "s/$$1.*$$//"`; \
  }; \
  for flg in $$sane_makeflags; do \
    test $$skip_next = yes && { skip_next=no; continue; }; \
    case $$flg in \
      *=*|--*) continue;; \
        -*I) strip_trailopt 'I'; skip_next=yes;; \
      -*I?*) strip_trailopt 'I';; \
        -*O) strip_trailopt 'O'; skip_next=yes;; \
      -*O?*) strip_trailopt 'O';; \
        -*l) strip_trailopt 'l'; skip_next=yes;; \
      -*l?*) strip_trailopt 'l';; \
      -[dEDm]) skip_next=yes;; \
      -[JT]) skip_next=yes;; \
    esac; \
    case $$flg in \
      *$$target_option*) has_opt=yes; break;; \
    esac; \
  done; \
  test $$has_opt = yes
am__make_dryrun = (target_option=n; $(am__make_running_with_option))
am__make_keepgoing = (target_option=k; $(am__make_running_with_option))
pkgdatadir = $(datadir)/rtai
pkgincludedir = $(includedir)/rtai
pkglibdir = $(libdir)/rtai
pkglibexecdir = $(libexecdir)/rtai
am__cd = CDPATH="$${ZSH_VERSION+.}$(PATH_SEPARATOR)" && cd
install_sh_DATA = $(install_sh) -c -m 644
install_sh_PROGRAM = $(install_sh) -c
install_sh_SCRIPT = $(install_sh) -c
INSTALL_HEADER = $(INSTALL_DATA)
transform = $(program_transform_name)
NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
build_triplet = x86_64-unknown-linux-gnu
host_triplet = x86_64-unknown-linux-gnu
subdir = base/wd
DIST_COMMON = $(srcdir)/GNUmakefile.in $(srcdir)/GNUmakefile.am \
	$(top_srcdir)/base/config/autoconf/mkinstalldirs \
	$(srcdir)/Makefile.kbuild \
	$(top_srcdir)/base/config/autoconf/depcomp
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
am__aclocal_m4_deps = $(top_srcdir)/base/config/autoconf/acinclude.m4 \
	$(top_srcdir)/base/config/autoconf/docbook.m4 \
	$(top_srcdir)/configure.ac
am__configure_deps = $(am__aclocal_m4_deps) $(CONFIGURE_DEPENDENCIES) \
	$(ACLOCAL_M4)
mkinstalldirs = $(SHELL) \
	$(top_srcdir)/base/config/autoconf/mkinstalldirs
CONFIG_HEADER = $(top_builddir)/rtai_config.h
CONFIG_CLEAN_FILES = Makefile
CONFIG_CLEAN_VPATH_FILES =
LIBRARIES = $(noinst_LIBRARIES)
ARFLAGS = cru
AM_V_AR = $(am__v_AR_$(V))
am__v_AR_ = $(am__v_AR_$(AM_DEFAULT_VERBOSITY))
am__v_AR_0 = @echo "  AR      " $@;
am__v_AR_1 = 
libwd_a_LIBADD =
am_libwd_a_OBJECTS = wd.$(OBJEXT)
libwd_a_OBJECTS = $(am_libwd_a_OBJECTS)
AM_V_P = $(am__v_P_$(V))
am__v_P_ = $(am__v_P_$(AM_DEFAULT_VERBOSITY))
am__v_P_0 = false
am__v_P_1 = :
AM_V_GEN = $(am__v_GEN_$(V))
am__v_GEN_ = $(am__v_GEN_$(AM_DEFAULT_VERBOSITY))
am__v_GEN_0 = @echo "  GEN     " $@;
am__v_GEN_1 = 
AM_V_at = $(am__v_at_$(V))
am__v_at_ = $(am__v_at_$(AM_DEFAULT_VERBOSITY))
am__v_at_0 = @
am__v_at_1 = 
DEFAULT_INCLUDES = -I. -I$(top_builddir)
depcomp = $(SHELL) $(top_srcdir)/base/config/autoconf/depcomp
am__depfiles_maybe = depfiles
am__mv = mv -f
COMPILE = $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) \
	$(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
AM_V_lt = $(am__v_lt_$(V))
am__v_lt_ = $(am__v_lt_$(AM_DEFAULT_VERBOSITY))
am__v_lt_0 = --silent
am__v_lt_1 = 
LTCOMPILE = $(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) \
	$(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) \
	$(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) \
	$(AM_CFLAGS) $(CFLAGS)
AM_V_CC = $(am__v_CC_$(V))
am__v_CC_ = $(am__v_CC_$(AM_DEFAULT_VERBOSITY))
am__v_CC_0 = @echo "  CC      " $@;
am__v_CC_1 = 
CCLD = $(CC)
LINK = $(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) \
	$(LIBTOOLFLAGS) --mode=link $(CCLD) $(AM_CFLAGS) $(CFLAGS) \
	$(AM_LDFLAGS) $(LDFLAGS) -o $@
AM_V_CCLD = $(am__v_CCLD_$(V))
am__v_CCLD_ = $(am__v_CCLD_$(AM_DEFAULT_VERBOSITY))
am__v_CCLD_0 = @echo "  CCLD    " $@;
am__v_CCLD_1 = 
SOURCES = $(libwd_a_SOURCES)
DIST_SOURCES = $(libwd_a_SOURCES)
am__can_run_installinfo = \
  case $$AM_UPDATE_INFO_DIR in \
    n|no|NO) false;; \
    *) (install-info --version) >/dev/null 2>&1;; \
  esac
am__tagged_files = $(HEADERS) $(SOURCES) $(TAGS_FILES) $(LISP)
# Read a list of newline-separated strings from the standard input,
# and print each of them once, without duplicates.  Input order is
# *not* preserved.
am__uniquify_input = $(AWK) '\
  BEGIN { nonempty = 0; } \
  { items[$$0] = 1; nonempty = 1; } \
  END { if (nonempty) { for (i in items) print i; }; } \
'
# Make sure the list of sources is unique.  This is necessary because,
# e.g., the same source file might be shared among _SOURCES variables
# for different programs/libraries.
am__define_uniq_tagged_files = \
  list='$(am__tagged_files)'; \
  unique=`for i in $$list; do \
    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
  done | $(am__uniquify_input)`
ETAGS = etags
CTAGS = ctags
DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)
ACLOCAL = aclocal-1.14
AMTAR = $${TAR-tar}
AM_DEFAULT_VERBOSITY = 1
AR = ar
AUTOCONF = autoconf
AUTOHEADER = autoheader
AUTOMAKE = automake-1.14
AWK = gawk
CC = cc
CCAS = cc
CCASDEPMODE = depmode=gcc3
CCASFLAGS = 
CCDEPMODE = depmode=gcc3
CFLAGS = 
COMEDI_DIR = 
CONFIG_RTAI_CPUS = 4
CONFIG_RTAI_LINUXDIR = /usr/src/linux-headers-4.4.115-rtai-5.1+
CPP = cc -E
CPPFLAGS = 
CROSSCOMPILE_TEST = 
CROSS_COMPILE = 
CXX = g++
CXXCPP = g++ -E
CXXDEPMODE = depmode=gcc3
CXXFLAGS = 
CYGPATH_W = echo
DBX_DOC_ROOT = doc/docbook
DBX_FOP = 
DBX_GEN_DOC_ROOT = doc/generated
DBX_LINT = xmllint
DBX_MAYBE_NONET = --nonet
DBX_ROOT = file:///usr/share/sgml/docbook/dtd/xml/4.2
DBX_XSLTPROC = xsltproc
DBX_XSL_ROOT = file:///usr/share/sgml/docbook/stylesheet/xsl/nwalsh
DEFS = -DHAVE_CONFIG_H
DEPDIR = .deps
DLLTOOL = false
DOXYGEN = doxygen
DOXYGEN_HAVE_DOT = NO
DOXYGEN_SHOW_INCLUDE_FILES = YES
DSYMUTIL = 
DUMPBIN = 
ECHO_C = 
ECHO_N = -n
ECHO_T = 
EFLTK_DIR = 
EGREP = /bin/grep -E
EXEEXT = 
FGREP = /bin/grep -F
GL_CFLAGS = 
GL_LIBS = 
GREP = /bin/grep
INSTALL = /usr/bin/install -c
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = $(install_sh) -c -s
LATEX_BATCHMODE = YES
LATEX_MODE = batchmode
LD = ld -m elf_x86_64
LDFLAGS = 
LIBOBJS = 
LIBS = 
LIBTOOL = $(SHELL) $(top_builddir)/libtool
LIPO = 
LN_S = ln -s
LTLIBOBJS = 
MAINT = #
MAKEINFO = makeinfo
MANIFEST_TOOL = :
MKDIR_P = /bin/mkdir -p
NM = nm
NMEDIT = 
OBJDUMP = objdump
OBJEXT = o
OTOOL = 
OTOOL64 = 
PACKAGE = rtai
PACKAGE_BUGREPORT = rtai@rtai.org
PACKAGE_NAME = rtai
PACKAGE_STRING = rtai 5.1
PACKAGE_TARNAME = rtai
PACKAGE_URL = 
PACKAGE_VERSION = 5.1
PATH_SEPARATOR = :
RANLIB = ranlib
RTAI_BUILD_STRING = x86_64-unknown-linux-gnu
RTAI_BUILTIN_MODLIST =  malloc
RTAI_COMPAT_CPPFLAGS = 
RTAI_FP_CFLAGS =  -ffast-math -mhard-float
RTAI_HOST_STRING = x86_64-unknown-linux-gnu
RTAI_INSTALL_DIR = ${exec_prefix}
RTAI_KBUILD_BOTTOM = 
RTAI_KBUILD_CLEAN = rm -f *.ko *.mod.c .*.cmd *.o Module.symvers Module.markers modules.order && rm -Rf .tmp_versions
RTAI_KBUILD_CMD = for src in $^; do if test \! -r `basename $$src`; then $(LN_S) $$src; fi; done; 		    rm -f /usr/src/linux-headers-4.4.115-rtai-5.1+/.tmp_versions/rtai_*.mod /usr/src/linux-headers-4.4.115-rtai-5.1+/.tmp_versions/*_rt.mod;                     $(MAKE) -C /usr/src/linux-headers-4.4.115-rtai-5.1+ CROSS_COMPILE=$(CROSS_COMPILE) CC=cc ARCH=x86 		    SUBDIRS=$$PWD M=$$PWD rtai_srctree=`cd $(top_srcdir) && pwd` rtai_srcdir=`cd $(srcdir) && pwd` V=$(V) modules 		    rtai_objs='$(call src2obj,c,$^) $(call src2obj,S,$^) $(call src2obj,cc,$^) $(call src2obj,cpp,$^)' rtai_target=$(basename $@)
RTAI_KBUILD_DISTCLEAN = 
RTAI_KBUILD_ENV = src2obj = $(patsubst %.$(1),%.o,$(filter %.$(1),$(call notdir,$(2))))
RTAI_KBUILD_TOP = @if test \! -r Module.symvers ; then $(LN_S) -f "`cd $(top_builddir) && pwd`/Module.symvers" . ; fi;
RTAI_KMOD_APP_CFLAGS = 
RTAI_KMOD_APP_CXXFLAGS =  -fno-rtti -fno-exceptions -fno-strength-reduce -pipe -fno-use-cxa-atexit
RTAI_KMOD_CFLAGS =  -D__IN_RTAI__
RTAI_KMOD_CXXFLAGS =  -fno-rtti -fno-exceptions -fno-strength-reduce -pipe -fno-use-cxa-atexit -D__IN_RTAI__
RTAI_LINUX_DIR = /usr/src/linux-headers-4.4.115-rtai-5.1+
RTAI_LINUX_VERSION = 4.4.115
RTAI_LXRT_LDADD = 
RTAI_MATH_LIBM = 
RTAI_MAYBE_DOCDIR = doc
RTAI_MAYBE_SIMDIR = 
RTAI_MODULE_DIR = ${exec_prefix}/modules
RTAI_MODULE_EXT = .ko
RTAI_POSIX_WRAP =  -Wl,--wrap -Wl,timer_create -Wl,--wrap -Wl,timer_delete -Wl,--wrap -Wl,timer_getoverrun -Wl,--wrap -Wl,timer_gettime -Wl,--wrap -Wl,timer_settime -Wl,--wrap -Wl,clock_getres -Wl,--wrap -Wl,clock_gettime -Wl,--wrap -Wl,clock_settime -Wl,--wrap -Wl,clock_nanosleep -Wl,--wrap -Wl,nanosleep -Wl,--wrap -Wl,pthread_barrier_init -Wl,--wrap -Wl,pthread_barrier_destroy -Wl,--wrap -Wl,pthread_barrier_wait -Wl,--wrap -Wl,pthread_barrierattr_init -Wl,--wrap -Wl,pthread_barrierattr_destroy -Wl,--wrap -Wl,pthread_barrierattr_getpshared -Wl,--wrap -Wl,pthread_barrierattr_setpshared -Wl,--wrap -Wl,pthread_cond_init -Wl,--wrap -Wl,pthread_cond_destroy -Wl,--wrap -Wl,pthread_cond_signal -Wl,--wrap -Wl,pthread_cond_broadcast -Wl,--wrap -Wl,pthread_cond_wait -Wl,--wrap -Wl,pthread_cond_timedwait -Wl,--wrap -Wl,pthread_condattr_init -Wl,--wrap -Wl,pthread_condattr_destroy -Wl,--wrap -Wl,pthread_condattr_getpshared -Wl,--wrap -Wl,pthread_condattr_setpshared -Wl,--wrap -Wl,pthread_condattr_getclock -Wl,--wrap -Wl,pthread_condattr_setclock -Wl,--wrap -Wl,pthread_mutex_init -Wl,--wrap -Wl,pthread_mutex_destroy -Wl,--wrap -Wl,pthread_mutex_lock -Wl,--wrap -Wl,pthread_mutex_timedlock -Wl,--wrap -Wl,pthread_mutex_trylock -Wl,--wrap -Wl,pthread_mutex_unlock -Wl,--wrap -Wl,pthread_mutexattr_init -Wl,--wrap -Wl,pthread_mutexattr_destroy -Wl,--wrap -Wl,pthread_mutexattr_getpshared -Wl,--wrap -Wl,pthread_mutexattr_setpshared -Wl,--wrap -Wl,pthread_mutexattr_settype -Wl,--wrap -Wl,pthread_mutexattr_gettype -Wl,--wrap -Wl,pthread_rwlock_init -Wl,--wrap -Wl,pthread_rwlock_destroy -Wl,--wrap -Wl,pthread_rwlock_rdlock -Wl,--wrap -Wl,pthread_rwlock_tryrdlock -Wl,--wrap -Wl,pthread_rwlock_timedrdlock -Wl,--wrap -Wl,pthread_rwlock_wrlock -Wl,--wrap -Wl,pthread_rwlock_trywrlock -Wl,--wrap -Wl,pthread_rwlock_timedwrlock -Wl,--wrap -Wl,pthread_rwlock_unlock -Wl,--wrap -Wl,pthread_rwlockattr_init -Wl,--wrap -Wl,pthread_rwlockattr_destroy -Wl,--wrap -Wl,pthread_rwlockattr_getpshared -Wl,--wrap -Wl,pthread_rwlockattr_setpshared -Wl,--wrap -Wl,pthread_rwlockattr_getkind_np -Wl,--wrap -Wl,pthread_rwlockattr_setkind_np -Wl,--wrap -Wl,pthread_spin_init -Wl,--wrap -Wl,pthread_spin_destroy -Wl,--wrap -Wl,pthread_spin_lock -Wl,--wrap -Wl,pthread_spin_trylock -Wl,--wrap -Wl,pthread_spin_unlock -Wl,--wrap -Wl,sem_open -Wl,--wrap -Wl,sem_close -Wl,--wrap -Wl,sem_unlink -Wl,--wrap -Wl,sem_init -Wl,--wrap -Wl,sem_destroy -Wl,--wrap -Wl,sem_wait -Wl,--wrap -Wl,sem_trywait -Wl,--wrap -Wl,sem_timedwait -Wl,--wrap -Wl,sem_post -Wl,--wrap -Wl,sem_getvalue
RTAI_REAL_USER_CFLAGS = -O2  -Wall -Wstrict-prototypes -pipe -D__IN_RTAI__
RTAI_TARGET_ARCH = x86
RTAI_TARGET_ARCH_OPTS =  -msse -mpreferred-stack-boundary=4
RTAI_TARGET_SUBARCH = 64
RTAI_USER_APP_CFLAGS = -O2  -Wall -Wstrict-prototypes -pipe
RTAI_USER_CFLAGS = -I/usr/src/linux-headers-4.4.115-rtai-5.1+/include -O2  -Wall -Wstrict-prototypes -pipe -D__IN_RTAI__
SED = /bin/sed
SENSORS_LIBS = -lsensors
SET_MAKE = 
SHELL = /bin/sh
STRIP = strip
VERSION = 5.1
XMKMF = 
X_CFLAGS = 
X_EXTRA_LIBS = 
X_LIBS = 
X_PRE_LIBS = 
abs_builddir = /home/bruce/ubuntu-kernel/v4.4.115-rtai5.1/rtai-5.1/base/wd
abs_srcdir = /home/bruce/ubuntu-kernel/v4.4.115-rtai5.1/rtai-5.1/base/wd
abs_top_builddir = /home/bruce/ubuntu-kernel/v4.4.115-rtai5.1/rtai-5.1
abs_top_srcdir = /home/bruce/ubuntu-kernel/v4.4.115-rtai5.1/rtai-5.1
ac_ct_AR = 
ac_ct_CC = 
ac_ct_CXX = 
ac_ct_DUMPBIN = 
am__include = include
am__leading_dot = .
am__quote = 
am__tar = $${TAR-tar} chof - "$$tardir"
am__untar = $${TAR-tar} xf -
bindir = ${exec_prefix}/bin
build = x86_64-unknown-linux-gnu
build_alias = x86_64-unknown-linux-gnu
build_cpu = x86_64
build_os = linux-gnu
build_vendor = unknown
builddir = .
datadir = ${datarootdir}
datarootdir = ${prefix}/share
docdir = ${datarootdir}/doc/${PACKAGE_TARNAME}
dvidir = ${docdir}
exec_prefix = ${prefix}
host = x86_64-unknown-linux-gnu
host_alias = x86_64-unknown-linux-gnu
host_cpu = x86_64
host_os = linux-gnu
host_vendor = unknown
htmldir = ${docdir}
includedir = ${prefix}/include
infodir = ${datarootdir}/info
install_sh = ${SHELL} /home/bruce/ubuntu-kernel/v4.4.115-rtai5.1/rtai-5.1/base/config/autoconf/install-sh
libdir = ${exec_prefix}/lib
libexecdir = ${exec_prefix}/libexec
localedir = ${datarootdir}/locale
localstatedir = ${prefix}/var
mandir = ${datarootdir}/man
mkdir_p = $(MKDIR_P)
oldincludedir = /usr/include
pdfdir = ${docdir}
prefix = /opt/rtai-5.1_v4.4.115
program_transform_name = s,x,x,
psdir = ${docdir}
sbindir = ${exec_prefix}/sbin
sharedstatedir = ${prefix}/com
srcdir = .
subdirs = 
sysconfdir = ${prefix}/etc
target_alias = 
top_build_prefix = ../../
top_builddir = ../..
top_srcdir = ../..
moduledir = ${exec_prefix}/modules
modext = .ko
libwd_a_SOURCES = wd.c
#noinst_LIBRARIES = libwd.a
#libwd_a_AR = $(CROSS_COMPILE)ar cru
#INCLUDES = \
#	 -D__IN_RTAI__ \
#	-I$(top_srcdir)/base/include \
#	-I../include

EXTRA_DIST = Makefile.kbuild
all: all-am

.SUFFIXES:
.SUFFIXES: .c .lo .o .obj
$(srcdir)/GNUmakefile.in: # $(srcdir)/GNUmakefile.am  $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      ( cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh ) \
	        && { if test -f $@; then exit 0; else break; fi; }; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --foreign base/wd/GNUmakefile'; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --foreign base/wd/GNUmakefile
.PRECIOUS: GNUmakefile
GNUmakefile: $(srcdir)/GNUmakefile.in $(top_builddir)/config.status
	@case '$?' in \
	  *config.status*) \
	    cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh;; \
	  *) \
	    echo ' cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe)'; \
	    cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe);; \
	esac;

$(top_builddir)/config.status: $(top_srcdir)/configure $(CONFIG_STATUS_DEPENDENCIES)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh

$(top_srcdir)/configure: # $(am__configure_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(ACLOCAL_M4): # $(am__aclocal_m4_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(am__aclocal_m4_deps):

clean-noinstLIBRARIES:
	-test -z "$(noinst_LIBRARIES)" || rm -f $(noinst_LIBRARIES)

libwd.a: $(libwd_a_OBJECTS) $(libwd_a_DEPENDENCIES) $(EXTRA_libwd_a_DEPENDENCIES) 
	$(AM_V_at)-rm -f libwd.a
	$(AM_V_AR)$(libwd_a_AR) libwd.a $(libwd_a_OBJECTS) $(libwd_a_LIBADD)
	$(AM_V_at)$(RANLIB) libwd.a

mostlyclean-compile:
	-rm -f *.$(OBJEXT)

distclean-compile:
	-rm -f *.tab.c

include ./$(DEPDIR)/wd.Po

.c.o:
	$(AM_V_CC)$(COMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ $<
	$(AM_V_at)$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Po
#	$(AM_V_CC)source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(AM_V_CC_no)$(COMPILE) -c -o $@ $<

.c.obj:
	$(AM_V_CC)$(COMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ `$(CYGPATH_W) '$<'`
	$(AM_V_at)$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Po
#	$(AM_V_CC)source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(AM_V_CC_no)$(COMPILE) -c -o $@ `$(CYGPATH_W) '$<'`

.c.lo:
	$(AM_V_CC)$(LTCOMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ $<
	$(AM_V_at)$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Plo
#	$(AM_V_CC)source='$<' object='$@' libtool=yes \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(AM_V_CC_no)$(LTCOMPILE) -c -o $@ $<

mostlyclean-libtool:
	-rm -f *.lo

clean-libtool:
	-rm -rf .libs _libs

ID: $(am__tagged_files)
	$(am__define_uniq_tagged_files); mkid -fID $$unique
tags: tags-am
TAGS: tags

tags-am: $(TAGS_DEPENDENCIES) $(am__tagged_files)
	set x; \
	here=`pwd`; \
	$(am__define_uniq_tagged_files); \
	shift; \
	if test -z "$(ETAGS_ARGS)$$*$$unique"; then :; else \
	  test -n "$$unique" || unique=$$empty_fix; \
	  if test $$# -gt 0; then \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      "$$@" $$unique; \
	  else \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      $$unique; \
	  fi; \
	fi
ctags: ctags-am

CTAGS: ctags
ctags-am: $(TAGS_DEPENDENCIES) $(am__tagged_files)
	$(am__define_uniq_tagged_files); \
	test -z "$(CTAGS_ARGS)$$unique" \
	  || $(CTAGS) $(CTAGSFLAGS) $(AM_CTAGSFLAGS) $(CTAGS_ARGS) \
	     $$unique

GTAGS:
	here=`$(am__cd) $(top_builddir) && pwd` \
	  && $(am__cd) $(top_srcdir) \
	  && gtags -i $(GTAGS_ARGS) "$$here"
cscopelist: cscopelist-am

cscopelist-am: $(am__tagged_files)
	list='$(am__tagged_files)'; \
	case "$(srcdir)" in \
	  [\\/]* | ?:[\\/]*) sdir="$(srcdir)" ;; \
	  *) sdir=$(subdir)/$(srcdir) ;; \
	esac; \
	for i in $$list; do \
	  if test -f "$$i"; then \
	    echo "$(subdir)/$$i"; \
	  else \
	    echo "$$sdir/$$i"; \
	  fi; \
	done >> $(top_builddir)/cscope.files

distclean-tags:
	-rm -f TAGS ID GTAGS GRTAGS GSYMS GPATH tags

distdir: $(DISTFILES)
	@srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	topsrcdirstrip=`echo "$(top_srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	list='$(DISTFILES)'; \
	  dist_files=`for file in $$list; do echo $$file; done | \
	  sed -e "s|^$$srcdirstrip/||;t" \
	      -e "s|^$$topsrcdirstrip/|$(top_builddir)/|;t"`; \
	case $$dist_files in \
	  */*) $(MKDIR_P) `echo "$$dist_files" | \
			   sed '/\//!d;s|^|$(distdir)/|;s,/[^/]*$$,,' | \
			   sort -u` ;; \
	esac; \
	for file in $$dist_files; do \
	  if test -f $$file || test -d $$file; then d=.; else d=$(srcdir); fi; \
	  if test -d $$d/$$file; then \
	    dir=`echo "/$$file" | sed -e 's,/[^/]*$$,,'`; \
	    if test -d "$(distdir)/$$file"; then \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    if test -d $(srcdir)/$$file && test $$d != $(srcdir); then \
	      cp -fpR $(srcdir)/$$file "$(distdir)$$dir" || exit 1; \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    cp -fpR $$d/$$file "$(distdir)$$dir" || exit 1; \
	  else \
	    test -f "$(distdir)/$$file" \
	    || cp -p $$d/$$file "$(distdir)/$$file" \
	    || exit 1; \
	  fi; \
	done
check-am: all-am
check: check-am
all-am: GNUmakefile $(LIBRARIES) all-local
installdirs:
install: install-am
install-exec: install-exec-am
install-data: install-data-am
uninstall: uninstall-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am

installcheck: installcheck-am
install-strip:
	if test -z '$(STRIP)'; then \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	      install; \
	else \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	    "INSTALL_PROGRAM_ENV=STRIPPROG='$(STRIP)'" install; \
	fi
mostlyclean-generic:

clean-generic:

distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)

maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
#clean-local:
clean: clean-am

clean-am: clean-generic clean-libtool clean-local \
	clean-noinstLIBRARIES mostlyclean-am

distclean: distclean-am
	-rm -rf ./$(DEPDIR)
	-rm -f GNUmakefile
distclean-am: clean-am distclean-compile distclean-generic \
	distclean-tags

dvi: dvi-am

dvi-am:

html: html-am

html-am:

info: info-am

info-am:

install-data-am:

install-dvi: install-dvi-am

install-dvi-am:

install-exec-am: install-exec-local

install-html: install-html-am

install-html-am:

install-info: install-info-am

install-info-am:

install-man:

install-pdf: install-pdf-am

install-pdf-am:

install-ps: install-ps-am

install-ps-am:

installcheck-am:

maintainer-clean: maintainer-clean-am
	-rm -rf ./$(DEPDIR)
	-rm -f GNUmakefile
maintainer-clean-am: distclean-am maintainer-clean-generic

mostlyclean: mostlyclean-am

mostlyclean-am: mostlyclean-compile mostlyclean-generic \
	mostlyclean-libtool

pdf: pdf-am

pdf-am:

ps: ps-am

ps-am:

uninstall-am:

.MAKE: install-am install-strip

.PHONY: CTAGS GTAGS TAGS all all-am all-local check check-am clean \
	clean-generic clean-libtool clean-local clean-noinstLIBRARIES \
	cscopelist-am ctags ctags-am distclean distclean-compile \
	distclean-generic distclean-libtool distclean-tags distdir dvi \
	dvi-am html html-am info info-am install install-am \
	install-data install-data-am install-dvi install-dvi-am \
	install-exec install-exec-am install-exec-local install-html \
	install-html-am install-info install-info-am install-man \
	install-pdf install-pdf-am install-ps install-ps-am \
	install-strip installcheck installcheck-am installdirs \
	maintainer-clean maintainer-clean-generic mostlyclean \
	mostlyclean-compile mostlyclean-generic mostlyclean-libtool \
	pdf pdf-am ps ps-am tags tags-am uninstall uninstall-am


rtai_wd.ko: src2obj = $(patsubst %.$(1),%.o,$(filter %.$(1),$(call notdir,$(2))))
rtai_wd.ko: $(libwd_a_SOURCES)
	@if test \! -r Module.symvers ; then $(LN_S) -f "`cd $(top_builddir) && pwd`/Module.symvers" . ; fi; \
	for src in $^; do if test \! -r `basename $$src`; then $(LN_S) $$src; fi; done; 		    rm -f /usr/src/linux-headers-4.4.115-rtai-5.1+/.tmp_versions/rtai_*.mod /usr/src/linux-headers-4.4.115-rtai-5.1+/.tmp_versions/*_rt.mod;                     $(MAKE) -C /usr/src/linux-headers-4.4.115-rtai-5.1+ CROSS_COMPILE=$(CROSS_COMPILE) CC=cc ARCH=x86 		    SUBDIRS=$$PWD M=$$PWD rtai_srctree=`cd $(top_srcdir) && pwd` rtai_srcdir=`cd $(srcdir) && pwd` V=$(V) modules 		    rtai_objs='$(call src2obj,c,$^) $(call src2obj,S,$^) $(call src2obj,cc,$^) $(call src2obj,cpp,$^)' rtai_target=$(basename $@) \
	

clean-local:
	rm -f *.ko *.mod.c .*.cmd *.o Module.symvers Module.markers modules.order && rm -Rf .tmp_versions

#rtai_wd.o: libwd.a
#	$(CROSS_COMPILE)$(LD) --whole-archive $< -r -o $@

all-local: rtai_wd$(modext)
#	$(mkinstalldirs) $(top_srcdir)/modules
#	$(INSTALL_DATA) $^ $(top_srcdir)/modules

install-exec-local: rtai_wd$(modext)
	$(mkinstalldirs) $(DESTDIR)$(moduledir)
	$(INSTALL_DATA) $< $(DESTDIR)$(moduledir)

# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
