PKG_NAME = xstow
PKG_VERS = 1.1.0
PKG_EXT = tar.bz2
PKG_DIST_NAME = $(PKG_NAME)-$(PKG_VERS).$(PKG_EXT)
PKG_DIST_SITE = https://github.com/majorkingleo/xstow/releases/download/${PKG_VERS}
PKG_DIR = ${PKG_NAME}-$(PKG_VERS)

DEPENDS =

HOMEPAGE = https://xstow.sourceforge.net/
COMMENT  = xstow is a symobolic link farm manager.
LICENSE  = GPLv2

GNU_CONFIGURE = 1
# CONFIGURE_ARGS  = --with-pmdir=\\\$\{prefix\}/usr/local/share/perl5/vendor_perl

include ../../mk/spksrc.cross-cc.mk
