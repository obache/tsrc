# $NetBSD: Makefile,v 1.21 2018/07/18 00:06:10 joerg Exp $

DISTNAME=	mp3check-0.8.7
CATEGORIES=	audio
MASTER_SITES=	http://mp3check.googlecode.com/files/
EXTRACT_SUFX=	.tgz

MAINTAINER=	pkgsrc-users@NetBSD.org
#HOMEPAGE=	http://jo.ath.cx/soft/mp3check/
COMMENT=	Check MP3 files for consistency
LICENSE=	gnu-gpl-v2

GNU_CONFIGURE=	YES
USE_LANGUAGES=	c c++03
USE_TOOLS+=	gmake

BUILD_TARGET=	mp3check

INSTALLATION_DIRS=	bin ${PKGMANDIR}/man1

do-install:
	${INSTALL_PROGRAM} ${WRKSRC}/mp3check ${DESTDIR}${PREFIX}/bin
	${INSTALL_DATA} ${WRKSRC}/mp3check.1 ${DESTDIR}${PREFIX}/${PKGMANDIR}/man1

.include "../../mk/bsd.pkg.mk"
