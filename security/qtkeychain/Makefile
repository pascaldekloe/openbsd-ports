COMMENT =		Platform-independent Qt API for storing passwords securely

V =			0.3.0
DISTNAME =		qtkeychain-${V}
CATEGORIES =		security

HOMEPAGE =		https://github.com/frankosterfeld/qtkeychain
MASTER_SITES =		https://github.com/frankosterfeld/qtkeychain/archive/
DISTFILES =		v${V}.tar.gz
PERMIT_PACKAGE_CDROM =	Yes
PERMIT_PACKAGE_FTP =	Yes

SHARED_LIBS +=		qtkeychain		0.3	#.0

WANTLIB +=		m stdc++ QtDBus

MODULES =		devel/cmake x11/qt4

.include <bsd.port.mk>
