AC_PREREQ([2.71])

AC_INIT([Apertium English],[0.1.0],[apertium-stuff@lists.sourceforge.net],[apertium-eng],[https://wiki.apertium.org/wiki/Apertium-eng])
AM_INIT_AUTOMAKE

PKG_CHECK_MODULES(APERTIUM, apertium >= 3.6.0)
PKG_CHECK_MODULES(LTTOOLBOX, lttoolbox >= 3.5.0)
PKG_CHECK_MODULES(CG3, cg3 >= 1.3.0)

PKG_CHECK_MODULES(REGTEST, apertium-regtest >= 0.0.1, [],
                  [AC_MSG_WARN([Running tests requires apertium-regtest])])

AP_MKINCLUDE

AC_CONFIG_FILES([Makefile apertium-eng.pc])
AC_OUTPUT
