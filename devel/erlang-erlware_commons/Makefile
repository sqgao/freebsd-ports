# $FreeBSD$

PORTNAME=	erlware_commons
PORTVERSION=	0.22.0
PORTREVISION=	1
CATEGORIES=	devel
PKGNAMEPREFIX=	erlang-

MAINTAINER=	olgeni@FreeBSD.org
COMMENT=	Erlang project focused on all aspects of reusable components

LICENSE=	MIT

USES=		erlang:rebar
USE_GITHUB=	yes
GH_ACCOUNT=	erlware

ERL_BUILD_DEPS= devel/erlang-cf
ERL_RUN_DEPS:=  ${ERL_BUILD_DEPS}

.include <bsd.port.mk>
