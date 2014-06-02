COMMENT =		A generic touchscreen calibration program for X.Org

V =			0.7.5
DISTNAME =		xinput_calibrator-${V}
CATEGORIES =		x11

HOMEPAGE =		http://www.freedesktop.org/wiki/Software/xinput_calibrator
MASTER_SITES =		https://github.com/tias/xinput_calibrator/archive/
DISTFILES =		v${V}.tar.gz
PERMIT_PACKAGE_CDROM =	Yes
PERMIT_PACKAGE_FTP =	Yes

WANTLIB =		X11 Xext Xi Xrandr Xrender c m stdc++ xcb
BUILD_DEPENDS =		devel/autoconf/${AUTOCONF_VERSION} \
			devel/libtool

AUTOCONF_VERSION =	2.69
AUTOMAKE_VERSION =	1.14

CONFIGURE_ARGS =	${CONFIGURE_SHARED} \
			--with-gui=x11

pre-configure:
	@cd ${WRKSRC} && ${SETENV} \
		AUTOCONF_VERSION=${AUTOCONF_VERSION} \
		AUTOMAKE_VERSION=${AUTOMAKE_VERSION} \
		MKDIR_P="/bin/mkdir -p" \
		./autogen.sh


.include <bsd.port.mk>
