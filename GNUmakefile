############################################################ IDENT(1)
#
# $Title: Makefile for installing viosnoop $
# $Copyright: 2020 Devin Teske. All rights reserved. $
# $FrauBSD: viosnoop/GNUmakefile 2020-04-17 15:28:59 -0700 freebsdfrau $
#
############################################################ CONFIGURATION

DESTDIR=	
BINDIR=		$(DESTDIR)/usr/bin

############################################################ PATHS

CP_F=		cp -f
MKDIR_P=	mkdir -p
RM_F=		rm -f

############################################################ OBJECTS

PROG=		viosnoop

############################################################ TARGETS

all:
	@printf "Options:\n"
	@printf "\tmake install\tInstall viosnoop\n"
	@printf "\tmake uninstall\tUninstall viosnoop\n"

install:
	$(MKDIR_P) $(BINDIR)
	$(CP_F) $(PROG) $(BINDIR)/

uninstall:
	$(RM_F) $(BINDIR)/$(PROG)

################################################################################
# END
################################################################################
