# $NetBSD: Makefile,v 1.30 2021/04/21 08:04:14 wiz Exp $

DISTNAME=	libXg.utf.fonts
PKGNAME=	libXgFonts-1.0
PKGREVISION=	4
CATEGORIES=	fonts plan9
MASTER_SITES=	# ftp://ftp.ecf.toronto.edu/pub/plan9/matty/

MAINTAINER=	pkgsrc-users@NetBSD.org
COMMENT=	These are the UNICODE fonts for use with 9term and sam

WRKSRC=		${WRKDIR}
NO_BUILD=	yes

USE_TOOLS+=	bdftopcf gzip
FONTS_DIRS.x11=	${PREFIX}/share/fonts/X11/Xg
REQD_DIRS=	${PREFIX}/share/fonts/X11/Xg

.include "../../mk/bsd.pkg.mk"
