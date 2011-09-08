AC_PREREQ(2.65)

AC_INIT([shared-color-targets],[0.0.2],[richard@hughsie.com])
AM_INIT_AUTOMAKE(AC_PACKAGE_NAME, AC_PACKAGE_VERSION)
AC_CONFIG_HEADERS([config.h])

AC_PROG_CC
AC_PROG_LN_S

AC_CONFIG_FILES([
Makefile
targets/Makefile
targets/wolf_faust/Makefile
targets/wolf_faust/reflective/Makefile
targets/wolf_faust/transmissive/Makefile
tools/Makefile
])
AC_OUTPUT

echo "
                        shared-color-targets $VERSION
                     =========================
        prefix:                                     ${prefix}
        datadir:                                    ${datadir}
"
