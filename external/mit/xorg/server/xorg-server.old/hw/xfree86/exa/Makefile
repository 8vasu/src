#	$NetBSD: Makefile,v 1.1.1.1 2016/06/10 03:42:14 mrg Exp $

XMODULEDIR=	${X11USRLIBDIR}/modules

.include "../../../Makefile.serverlib"
.include "../../../Makefile.servermod"
.include "../../../exa/Makefile.exa"

LIB=	exa
MAN=	exa.4

.PATH:	${X11SRCDIR.xorg-server}/hw/xfree86/exa
.PATH:	${X11SRCDIR.xorg-server}/hw/xfree86/exa/man
SRCS+=	${SRCS.exa} examodule.c

.include <bsd.x11.mk>
LIBDIR=	${XMODULEDIR}
.include <bsd.lib.mk>
