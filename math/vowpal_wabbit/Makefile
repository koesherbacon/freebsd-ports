# Created by: Dmitry Sivachenko <demon@FreeBSD.org>
# $FreeBSD$

PORTNAME=	vowpal_wabbit
PORTVERSION=	7.10
PORTREVISION=	4
CATEGORIES=	math

MAINTAINER=	demon@FreeBSD.org
COMMENT=	Fast out-of-core learning system

LIB_DEPENDS=	libboost_thread.so:devel/boost-libs

BROKEN_powerpc64=	Does not build

USES=		compiler:c++11-lang libtool
GNU_CONFIGURE=	yes
USE_LDCONFIG=	yes
USE_GITHUB=	yes
GH_ACCOUNT=	JohnLangford

CONFIGURE_ARGS=	--enable-shared=no --with-boost=${LOCALBASE}

.include <bsd.port.mk>
