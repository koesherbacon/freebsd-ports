# Created by: chinsan <chinsan.tw@gmail.com>
# $FreeBSD$

PORTNAME=	lzf
PORTVERSION=	1.6.5
CATEGORIES=	archivers pear
DISTNAME=	${PORTNAME:tu}-${PORTVERSION}

MAINTAINER=	joneum@bsdproject.de
COMMENT=	Handles LZF de/compression

LICENSE=	PHP301

USES=		php:pecl

CONFIGURE_ARGS=	--enable-lzf
WRKSRC=		${WRKDIR}/${DISTNAME:tu}

OPTIONS_DEFINE=		BETTER_COMPRESSION
BETTER_COMPRESSION_DESC=	Better compression ratio
BETTER_COMPRESSION_CONFIGURE_ON=	--enable-lzf-better-compression

.include <bsd.port.mk>
