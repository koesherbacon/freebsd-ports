# $FreeBSD$

PORTNAME=	jose
PORTVERSION=	1.8.3
CATEGORIES=	security
PKGNAMEPREFIX=	elixir-

MAINTAINER=	vanilla@FreeBSD.org
COMMENT=	JSON Object Signing and Encryption (JOSE) for Elixir

LICENSE=	MPL

USES=		elixir
USE_GITHUB=	yes
GH_ACCOUNT=	potatosalad
GH_PROJECT=	erlang-jose
DOCSDIR=	${PREFIX}/share/doc/elixir-${PORTNAME}
NO_ARCH=	yes

MIX_BUILD_DEPS=	converters/erlang-base64url \
		security/erlang-jose
MIX_RUN_DEPS:=	${MIX_BUILD_DEPS}

.include <bsd.port.mk>
