#	@(#)Makefile	8.1 (Berkeley) 5/31/93
# $DragonFly: src/games/primes/Makefile,v 1.3 2006/10/08 16:22:36 pavalos Exp $

PROG=	primes
SRCS=	pattern.c pr_tbl.c primes.c
NO_MAN=	noman
DPADD=	${LIBM}
LDADD=	-lm

beforeinstall:
.if !exists(${BINDIR})
	mkdir -p ${BINDIR}
.endif

.include <bsd.prog.mk>
