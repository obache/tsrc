# $NetBSD: Makefile,v 1.23 2014/10/09 14:06:32 wiz Exp $
#

.include "../../editors/ce/Makefile.common"

PKGNAME=		ce-x11-${VERSION}
PKGREVISION=		2
COMMENT+=		, X11 version

BUILD_TARGET=		xce
INSTALL_TARGET=		install-x11 man-install-x11

INSTALLATION_DIRS=	bin ${PKGMANDIR}/man1

BUILDLINK_DEPMETHOD.libXt?=	build

.include "../../mk/termcap.buildlink3.mk"
.include "../../x11/libX11/buildlink3.mk"
.include "../../x11/libXt/buildlink3.mk"
.include "../../mk/bsd.pkg.mk"
