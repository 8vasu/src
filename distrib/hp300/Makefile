#	$NetBSD: Makefile,v 1.18 2008/06/23 02:16:53 matt Exp $

.include <bsd.own.mk>
.include "${NETBSDSRCDIR}/distrib/common/Makefile.distrib"

SUBDIR=		ramdisk .WAIT instkernel cdroms
TARGETS+=	release

release: check_RELEASEDIR .WAIT HP-IB.geometry
	${RELEASE_INSTALL} ${.CURDIR}/HP-IB.geometry \
	    ${RELEASEDIR}/${RELEASEMACHINEDIR}/installation/misc

iso_image:
	${MAKEDIRTARGET} cdroms iso_image

.include <bsd.subdir.mk>
