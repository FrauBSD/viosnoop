############################################################ IDENT(1)
#
# $Title: Makefile for installing viosnoop $
# $Copyright: 2020 Devin Teske. All rights reserved. $
# $FrauBSD: viosnoop/GNUmakefile 2020-02-16 20:04:23 -0800 freebsdfrau $
#
############################################################ CONFIGURATION

DESTDIR=	
BINDIR=		$(DESTDIR)/usr/bin

############################################################ PATHS

CP_F=		cp -f
MKDIR_P=	mkdir -p
RM_F=		rm -f

############################################################ OBJECTS

VIOSNOOP=	viosnoop

############################################################ TARGETS

all:
	@printf "Options:\n"
	@printf "\tmake install\tInstall viosnoop\n"
	@printf "\tmake uninstall\tUninstall viosnoop\n"

install:
	$(MKDIR_P) $(BINDIR)
	$(CP_F) $(VIOSNOOP) $(BINDIR)/

uninstall:
	$(RM_F) $(BINDIR)/$(VIOSNOOP)

################################################################################
# END
################################################################################
