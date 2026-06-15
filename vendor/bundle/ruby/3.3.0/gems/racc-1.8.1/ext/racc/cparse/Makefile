
SHELL = /bin/sh

# V=0 quiet, V=1 verbose.  other values don't work.
V = 0
V0 = $(V:0=)
Q1 = $(V:1=)
Q = $(Q1:0=@)
ECHO1 = $(V:1=@ exit /b0.)
ECHO = $(ECHO1:0=@ echo)
NULLCMD = exit /b0.

#### Start of system configuration section. ####

srcdir = .
topdir = C:/Users/kdy/anaconda3/envs/jekyllmm/include/ruby-3.3.0
hdrdir = $(topdir)
arch_hdrdir = C:/Users/kdy/anaconda3/envs/jekyllmm/include/ruby-3.3.0/x64-mswin64_140
PATH_SEPARATOR = ;
VPATH = $(srcdir);$(arch_hdrdir)/ruby;$(hdrdir)/ruby

DESTDIR = C:
prefix = $(DESTDIR)/Users/kdy/anaconda3/envs/jekyllmm
exec_prefix = $(prefix)
rubylibprefix = $(prefix)/lib/$(RUBY_BASE_NAME)
bindir = $(exec_prefix)/bin
sbindir = $(exec_prefix)/sbin
libexecdir = $(exec_prefix)/libexec
datadir = $(prefix)/share
sysconfdir = $(DESTDIR)
sharedstatedir = $(prefix)/com
localstatedir = $(prefix)/var
libdir = $(exec_prefix)/lib
includedir = $(prefix)/include
oldincludedir = $(DESTDIR)/usr/include
infodir = $(datadir)/info
mandir = $(datadir)/man
ridir = $(datadir)/ri
docdir = $(datadir)/doc/$(RUBY_BASE_NAME)
archlibdir = $(libdir)/$(arch)
sitearchlibdir = $(libdir)/$(sitearch)
archincludedir = $(includedir)/$(arch)
sitearchincludedir = $(includedir)/$(sitearch)
rubyarchdir = $(rubylibdir)/$(arch)
rubylibdir = $(rubylibprefix)/$(ruby_version)
sitedir = $(rubylibprefix)/site_ruby
sitearchdir = $(sitelibdir)/$(sitearch)
sitelibdir = $(sitedir)/$(ruby_version)
vendordir = $(rubylibprefix)/vendor_ruby
vendorarchdir = $(vendorlibdir)/$(sitearch)
vendorlibdir = $(vendordir)/$(ruby_version)
rubyhdrdir = $(includedir)/$(RUBY_BASE_NAME)-$(ruby_version)
sitehdrdir = $(rubyhdrdir)/site_ruby
vendorhdrdir = $(rubyhdrdir)/vendor_ruby
rubyarchhdrdir = $(rubyhdrdir)/$(arch)
sitearchhdrdir = $(sitehdrdir)/$(sitearch)
vendorarchhdrdir = $(vendorhdrdir)/$(sitearch)
archdir = $(rubyarchdir)


CC_WRAPPER = 
CC = cl.exe -nologo
CXX = $(CC)
LIBRUBY = $(RUBY_SO_NAME).lib
LIBRUBY_A = $(RUBY_SO_NAME)-static.lib
LIBRUBYARG_SHARED = $(LIBRUBY)
LIBRUBYARG_STATIC = $(LIBRUBY_A) $(MAINLIBS)
empty =
OUTFLAG = -Fe$(empty)
COUTFLAG = -Fo$(empty)
CSRCFLAG = -Tc$(empty)

RUBY_EXTCONF_H = 
cflags   = 
cxxflags = 
optflags = 
debugflags = 
warnflags = 
cppflags = 
CCDLFLAGS = 
CFLAGS   = $(CCDLFLAGS) -MD -Zi -W2 -wd4100 -wd4127 -wd4210 -wd4214 -wd4255 -wd4574  -wd4668 -wd4710 -wd4711 -wd4820 -wd4996  -we4028 -we4142 -we4047 -O2sy- -Zm600  $(ARCH_FLAG)
INCFLAGS = -I. -I$(arch_hdrdir) -I$(hdrdir)/ruby/backward -I$(hdrdir) -I$(srcdir)
DEFS     = 
CPPFLAGS = -DRACC_INFO_VERSION=1.8.1  -D_WIN32_WINNT=0x0600  
CXXFLAGS = $(CCDLFLAGS) -MD -Zi -W2 -wd4100 -wd4127 -wd4210 -wd4214 -wd4255 -wd4574  -wd4668 -wd4710 -wd4711 -wd4820 -wd4996  -we4028 -we4142 -we4047 -O2sy- -Zm600  $(ARCH_FLAG)
ldflags  = -incremental:no -debug -opt:ref -opt:icf
dldflags = -incremental:no -debug -opt:ref -opt:icf -dll $(LIBPATH) 
ARCH_FLAG = 
DLDFLAGS = $(ldflags) $(dldflags) $(ARCH_FLAG)
LDSHARED = cl.exe -nologo -LD
LDSHAREDXX = $(LDSHARED)
AR = lib -nologo
EXEEXT = .exe

RUBY_INSTALL_NAME = ruby
RUBY_SO_NAME = x64-vcruntime140-ruby330
RUBY_BASE_NAME = ruby
RUBYW_INSTALL_NAME = rubyw

arch = x64-mswin64_140
sitearch = x64-vcruntime140
ruby_version = 3.3.0
ruby = $(bindir)/ruby
RUBY = $(ruby:/=\)
BUILTRUBY = $(bindir)/ruby.exe
ruby_headers = {.;$(VPATH)}$(hdrdir)/ruby.h {.;$(VPATH)}$(hdrdir)/ruby/backward.h {.;$(VPATH)}$(hdrdir)/ruby/ruby.h {.;$(VPATH)}$(hdrdir)/ruby/defines.h {.;$(VPATH)}$(hdrdir)/ruby/missing.h {.;$(VPATH)}$(hdrdir)/ruby/intern.h {.;$(VPATH)}$(hdrdir)/ruby/st.h {.;$(VPATH)}$(hdrdir)/ruby/subst.h $(arch_hdrdir)/ruby/config.h

RM = $(RUBY) -run -e rm -- -f
RM_RF = $(RUBY) -run -e rm -- -rf
RMDIRS = $(RUBY) -run -e rmdir -- -p
MAKEDIRS = @$(RUBY) -run -e mkdir -- -p
INSTALL = @$(RUBY) -run -e install -- -vp
INSTALL_PROG = $(INSTALL) -m 0755
INSTALL_DATA = $(INSTALL) -m 0644
COPY = @$(RUBY) -run -e cp -- -v
TOUCH = exit >

#### End of system configuration section. ####

preload = 
libpath = . $(libdir)
LIBPATH =  -libpath:. -libpath:$(libdir)
DEFFILE = $(TARGET)-$(arch).def

CLEANFILES = mkmf.log $(DEFFILE)
DISTCLEANFILES = vc*.pdb
DISTCLEANDIRS = 

extout = 
extout_prefix = 
target_prefix = /racc
LOCAL_LIBS = 
LIBS = $(LIBRUBYARG_SHARED)  user32.lib 
ORIG_SRCS = cparse.c
SRCS = $(ORIG_SRCS) 
OBJS = cparse.obj
HDRS = 
LOCAL_HDRS = 
TARGET = cparse
TARGET_NAME = cparse
TARGET_ENTRY = Init_$(TARGET_NAME)
DLLIB = $(TARGET).so
EXTSTATIC = 
STATIC_LIB = 

TIMESTAMP_DIR = .
BINDIR        = $(bindir)
RUBYCOMMONDIR = $(sitedir)$(target_prefix)
RUBYLIBDIR    = $(sitelibdir)$(target_prefix)
RUBYARCHDIR   = $(sitearchdir)$(target_prefix)
HDRDIR        = $(sitehdrdir)$(target_prefix)
ARCHHDRDIR    = $(sitearchhdrdir)$(target_prefix)
TARGET_SO_DIR =
TARGET_SO     = $(TARGET_SO_DIR)$(DLLIB)
CLEANLIBS     = $(TARGET_SO) 
CLEANOBJS     = $(OBJS) $(TARGET)-$(arch).exp $(TARGET)-$(arch).lib $(TARGET)-$(arch).pdb *.bak
TARGET_SO_DIR_TIMESTAMP = $(TIMESTAMP_DIR)/.sitearchdir.-.racc.time

all:    $(DLLIB)
static: $(STATIC_LIB)
.PHONY: all install static install-so install-rb
.PHONY: clean clean-so clean-static clean-rb

clean-static::
clean-rb-default::
clean-rb::
clean-so::
clean: clean-so clean-static clean-rb-default clean-rb
		-$(Q)$(RM_RF) $(CLEANLIBS:/=\) $(CLEANOBJS:/=\) $(CLEANFILES:/=\) .*.time

distclean-rb-default::
distclean-rb::
distclean-so::
distclean-static::
distclean: clean distclean-so distclean-static distclean-rb-default distclean-rb
		-$(Q)$(RM) Makefile $(RUBY_EXTCONF_H) conftest.* mkmf.log
		-$(Q)$(RM) core ruby$(EXEEXT) *~ $(DISTCLEANFILES:/=\)
		-$(Q)$(RMDIRS) $(DISTCLEANDIRS:/=\) 2> NUL || exit /b0

realclean: distclean
install: install-so install-rb

install-so: $(DLLIB) $(TARGET_SO_DIR_TIMESTAMP)
	$(INSTALL_PROG) $(DLLIB:/=\) $(RUBYARCHDIR)
clean-static::
	-$(Q)$(RM) $(STATIC_LIB)
install-rb: pre-install-rb do-install-rb install-rb-default
install-rb-default: pre-install-rb-default do-install-rb-default
pre-install-rb: Makefile
pre-install-rb-default: Makefile
do-install-rb:
do-install-rb-default:
pre-install-rb-default:
	@$(NULLCMD)
$(TARGET_SO_DIR_TIMESTAMP):
	$(Q) $(MAKEDIRS) $(@D) $(RUBYARCHDIR)
	$(Q) $(TOUCH) $@

site-install: site-install-so site-install-rb
site-install-so: install-so
site-install-rb: install-rb

.SUFFIXES: .c .m .cc .mm .cxx .cpp .obj .asm

{$(srcdir)}.cc.obj:
	$(ECHO) compiling $(<:\=/)
	$(Q) $(CXX) $(INCFLAGS) $(CXXFLAGS) $(CPPFLAGS) $(COUTFLAG)$(@) -c -Tp$(<:\=/)

{$(srcdir)}.cc.asm:
	$(ECHO) translating $(<:\=/)
	$(Q) $(CXX) $(CXXFLAGS) $(CPPFLAGS) -Fa$(@) -c -Tp$(<:\=/)

{$(arch_hdrdir)/ruby}.cc.obj:
	$(ECHO) compiling $(<:\=/)
	$(Q) $(CXX) $(INCFLAGS) $(CXXFLAGS) $(CPPFLAGS) $(COUTFLAG)$(@) -c -Tp$(<:\=/)

{$(arch_hdrdir)/ruby}.cc.asm:
	$(ECHO) translating $(<:\=/)
	$(Q) $(CXX) $(CXXFLAGS) $(CPPFLAGS) -Fa$(@) -c -Tp$(<:\=/)

{$(hdrdir)/ruby}.cc.obj:
	$(ECHO) compiling $(<:\=/)
	$(Q) $(CXX) $(INCFLAGS) $(CXXFLAGS) $(CPPFLAGS) $(COUTFLAG)$(@) -c -Tp$(<:\=/)

{$(hdrdir)/ruby}.cc.asm:
	$(ECHO) translating $(<:\=/)
	$(Q) $(CXX) $(CXXFLAGS) $(CPPFLAGS) -Fa$(@) -c -Tp$(<:\=/)

.cc.obj:
	$(ECHO) compiling $(<:\=/)
	$(Q) $(CXX) $(INCFLAGS) $(CXXFLAGS) $(CPPFLAGS) $(COUTFLAG)$(@) -c -Tp$(<:\=/)

.cc.asm:
	$(ECHO) translating $(<:\=/)
	$(Q) $(CXX) $(CXXFLAGS) $(CPPFLAGS) -Fa$(@) -c -Tp$(<:\=/)

{$(srcdir)}.mm.obj:
	$(ECHO) compiling $(<:\=/)
	$(Q) $(CXX) $(INCFLAGS) $(CXXFLAGS) $(CPPFLAGS) $(COUTFLAG)$(@) -c -Tp$(<:\=/)

{$(srcdir)}.mm.asm:
	$(ECHO) translating $(<:\=/)
	$(Q) $(CXX) $(CXXFLAGS) $(CPPFLAGS) -Fa$(@) -c -Tp$(<:\=/)

{$(arch_hdrdir)/ruby}.mm.obj:
	$(ECHO) compiling $(<:\=/)
	$(Q) $(CXX) $(INCFLAGS) $(CXXFLAGS) $(CPPFLAGS) $(COUTFLAG)$(@) -c -Tp$(<:\=/)

{$(arch_hdrdir)/ruby}.mm.asm:
	$(ECHO) translating $(<:\=/)
	$(Q) $(CXX) $(CXXFLAGS) $(CPPFLAGS) -Fa$(@) -c -Tp$(<:\=/)

{$(hdrdir)/ruby}.mm.obj:
	$(ECHO) compiling $(<:\=/)
	$(Q) $(CXX) $(INCFLAGS) $(CXXFLAGS) $(CPPFLAGS) $(COUTFLAG)$(@) -c -Tp$(<:\=/)

{$(hdrdir)/ruby}.mm.asm:
	$(ECHO) translating $(<:\=/)
	$(Q) $(CXX) $(CXXFLAGS) $(CPPFLAGS) -Fa$(@) -c -Tp$(<:\=/)

.mm.obj:
	$(ECHO) compiling $(<:\=/)
	$(Q) $(CXX) $(INCFLAGS) $(CXXFLAGS) $(CPPFLAGS) $(COUTFLAG)$(@) -c -Tp$(<:\=/)

.mm.asm:
	$(ECHO) translating $(<:\=/)
	$(Q) $(CXX) $(CXXFLAGS) $(CPPFLAGS) -Fa$(@) -c -Tp$(<:\=/)

{$(srcdir)}.cxx.obj:
	$(ECHO) compiling $(<:\=/)
	$(Q) $(CXX) $(INCFLAGS) $(CXXFLAGS) $(CPPFLAGS) $(COUTFLAG)$(@) -c -Tp$(<:\=/)

{$(srcdir)}.cxx.asm:
	$(ECHO) translating $(<:\=/)
	$(Q) $(CXX) $(CXXFLAGS) $(CPPFLAGS) -Fa$(@) -c -Tp$(<:\=/)

{$(arch_hdrdir)/ruby}.cxx.obj:
	$(ECHO) compiling $(<:\=/)
	$(Q) $(CXX) $(INCFLAGS) $(CXXFLAGS) $(CPPFLAGS) $(COUTFLAG)$(@) -c -Tp$(<:\=/)

{$(arch_hdrdir)/ruby}.cxx.asm:
	$(ECHO) translating $(<:\=/)
	$(Q) $(CXX) $(CXXFLAGS) $(CPPFLAGS) -Fa$(@) -c -Tp$(<:\=/)

{$(hdrdir)/ruby}.cxx.obj:
	$(ECHO) compiling $(<:\=/)
	$(Q) $(CXX) $(INCFLAGS) $(CXXFLAGS) $(CPPFLAGS) $(COUTFLAG)$(@) -c -Tp$(<:\=/)

{$(hdrdir)/ruby}.cxx.asm:
	$(ECHO) translating $(<:\=/)
	$(Q) $(CXX) $(CXXFLAGS) $(CPPFLAGS) -Fa$(@) -c -Tp$(<:\=/)

.cxx.obj:
	$(ECHO) compiling $(<:\=/)
	$(Q) $(CXX) $(INCFLAGS) $(CXXFLAGS) $(CPPFLAGS) $(COUTFLAG)$(@) -c -Tp$(<:\=/)

.cxx.asm:
	$(ECHO) translating $(<:\=/)
	$(Q) $(CXX) $(CXXFLAGS) $(CPPFLAGS) -Fa$(@) -c -Tp$(<:\=/)

{$(srcdir)}.cpp.obj:
	$(ECHO) compiling $(<:\=/)
	$(Q) $(CXX) $(INCFLAGS) $(CXXFLAGS) $(CPPFLAGS) $(COUTFLAG)$(@) -c -Tp$(<:\=/)

{$(srcdir)}.cpp.asm:
	$(ECHO) translating $(<:\=/)
	$(Q) $(CXX) $(CXXFLAGS) $(CPPFLAGS) -Fa$(@) -c -Tp$(<:\=/)

{$(arch_hdrdir)/ruby}.cpp.obj:
	$(ECHO) compiling $(<:\=/)
	$(Q) $(CXX) $(INCFLAGS) $(CXXFLAGS) $(CPPFLAGS) $(COUTFLAG)$(@) -c -Tp$(<:\=/)

{$(arch_hdrdir)/ruby}.cpp.asm:
	$(ECHO) translating $(<:\=/)
	$(Q) $(CXX) $(CXXFLAGS) $(CPPFLAGS) -Fa$(@) -c -Tp$(<:\=/)

{$(hdrdir)/ruby}.cpp.obj:
	$(ECHO) compiling $(<:\=/)
	$(Q) $(CXX) $(INCFLAGS) $(CXXFLAGS) $(CPPFLAGS) $(COUTFLAG)$(@) -c -Tp$(<:\=/)

{$(hdrdir)/ruby}.cpp.asm:
	$(ECHO) translating $(<:\=/)
	$(Q) $(CXX) $(CXXFLAGS) $(CPPFLAGS) -Fa$(@) -c -Tp$(<:\=/)

.cpp.obj:
	$(ECHO) compiling $(<:\=/)
	$(Q) $(CXX) $(INCFLAGS) $(CXXFLAGS) $(CPPFLAGS) $(COUTFLAG)$(@) -c -Tp$(<:\=/)

.cpp.asm:
	$(ECHO) translating $(<:\=/)
	$(Q) $(CXX) $(CXXFLAGS) $(CPPFLAGS) -Fa$(@) -c -Tp$(<:\=/)

{$(srcdir)}.c.obj:
	$(ECHO) compiling $(<:\=/)
	$(Q) $(CC) $(INCFLAGS) $(CFLAGS) $(CPPFLAGS) $(COUTFLAG)$(@) -c $(CSRCFLAG)$(<:\=/)

{$(srcdir)}.c.asm:
	$(ECHO) translating $(<:\=/)
	$(Q) $(CC) $(CFLAGS) $(CPPFLAGS) -Fa$(@) -c $(CSRCFLAG)$(<:\=/)

{$(arch_hdrdir)/ruby}.c.obj:
	$(ECHO) compiling $(<:\=/)
	$(Q) $(CC) $(INCFLAGS) $(CFLAGS) $(CPPFLAGS) $(COUTFLAG)$(@) -c $(CSRCFLAG)$(<:\=/)

{$(arch_hdrdir)/ruby}.c.asm:
	$(ECHO) translating $(<:\=/)
	$(Q) $(CC) $(CFLAGS) $(CPPFLAGS) -Fa$(@) -c $(CSRCFLAG)$(<:\=/)

{$(hdrdir)/ruby}.c.obj:
	$(ECHO) compiling $(<:\=/)
	$(Q) $(CC) $(INCFLAGS) $(CFLAGS) $(CPPFLAGS) $(COUTFLAG)$(@) -c $(CSRCFLAG)$(<:\=/)

{$(hdrdir)/ruby}.c.asm:
	$(ECHO) translating $(<:\=/)
	$(Q) $(CC) $(CFLAGS) $(CPPFLAGS) -Fa$(@) -c $(CSRCFLAG)$(<:\=/)

.c.obj:
	$(ECHO) compiling $(<:\=/)
	$(Q) $(CC) $(INCFLAGS) $(CFLAGS) $(CPPFLAGS) $(COUTFLAG)$(@) -c $(CSRCFLAG)$(<:\=/)

.c.asm:
	$(ECHO) translating $(<:\=/)
	$(Q) $(CC) $(CFLAGS) $(CPPFLAGS) -Fa$(@) -c $(CSRCFLAG)$(<:\=/)

{$(srcdir)}.m.obj:
	$(ECHO) compiling $(<:\=/)
	$(Q) $(CC) $(INCFLAGS) $(CFLAGS) $(CPPFLAGS) $(COUTFLAG)$(@) -c $(CSRCFLAG)$(<:\=/)

{$(srcdir)}.m.asm:
	$(ECHO) translating $(<:\=/)
	$(Q) $(CC) $(CFLAGS) $(CPPFLAGS) -Fa$(@) -c $(CSRCFLAG)$(<:\=/)

{$(arch_hdrdir)/ruby}.m.obj:
	$(ECHO) compiling $(<:\=/)
	$(Q) $(CC) $(INCFLAGS) $(CFLAGS) $(CPPFLAGS) $(COUTFLAG)$(@) -c $(CSRCFLAG)$(<:\=/)

{$(arch_hdrdir)/ruby}.m.asm:
	$(ECHO) translating $(<:\=/)
	$(Q) $(CC) $(CFLAGS) $(CPPFLAGS) -Fa$(@) -c $(CSRCFLAG)$(<:\=/)

{$(hdrdir)/ruby}.m.obj:
	$(ECHO) compiling $(<:\=/)
	$(Q) $(CC) $(INCFLAGS) $(CFLAGS) $(CPPFLAGS) $(COUTFLAG)$(@) -c $(CSRCFLAG)$(<:\=/)

{$(hdrdir)/ruby}.m.asm:
	$(ECHO) translating $(<:\=/)
	$(Q) $(CC) $(CFLAGS) $(CPPFLAGS) -Fa$(@) -c $(CSRCFLAG)$(<:\=/)

.m.obj:
	$(ECHO) compiling $(<:\=/)
	$(Q) $(CC) $(INCFLAGS) $(CFLAGS) $(CPPFLAGS) $(COUTFLAG)$(@) -c $(CSRCFLAG)$(<:\=/)

.m.asm:
	$(ECHO) translating $(<:\=/)
	$(Q) $(CC) $(CFLAGS) $(CPPFLAGS) -Fa$(@) -c $(CSRCFLAG)$(<:\=/)

$(TARGET_SO): $(DEFFILE) $(OBJS) Makefile
	$(ECHO) linking shared-object racc/$(DLLIB)
	-$(Q)$(RM) $(@:/=\)
	$(Q) $(LDSHARED) -Fe$(@) $(OBJS) $(LIBS) $(LOCAL_LIBS) -link $(DLDFLAGS) -implib:$(*F:.so=)-$(arch).lib -pdb:$(*F:.so=)-$(arch).pdb -def:$(DEFFILE)
	$(Q) @if exist $(@).manifest $(RUBY) -run -e wait_writable -- -n 10 $(@)
	$(Q) @if exist $(@).manifest mt -nologo -manifest $(@).manifest -outputresource:$(@);2
	$(Q) @if exist $(@).manifest $(RM) $(@:/=\).manifest



$(DEFFILE): 
	$(ECHO) generating $(@:\=/)
	$(Q) (echo EXPORTS && echo $(TARGET_ENTRY)) > $@

$(OBJS): $(HDRS) $(ruby_headers)
