#	@(#)Makefile	8.1 (Berkeley) 5/31/93
#
# $DragonFly: src/games/ppt/Makefile,v 1.4 2006/10/08 16:22:36 pavalos Exp $
#

PROG=	ppt
NO_MAN=	noman

beforeinstall:
.if !exists(${BINDIR})
	mkdir -p ${BINDIR}
.endif

.include <bsd.prog.mk>

