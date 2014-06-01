COMMENT =		Qt library for communicating with The Echo Nest

V =			2.2.0
DISTNAME =		libechonest-${V}
CATEGORIES =		audio

HOMEPAGE =		https://projects.kde.org/projects/playground/libs/libechonest
MASTER_SITES =		http://files.lfranchi.com/
DISTFILES =		libechonest-${V}.tar.bz2
PERMIT_PACKAGE_CDROM =	Yes
PERMIT_PACKAGE_FTP =	Yes

SHARED_LIBS +=		echonest		2.2	#.0

WANTLIB +=		m stdc++ QtCore QtNetwork

MODULES =		devel/cmake x11/qt4

.include <bsd.port.mk>
