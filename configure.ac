AC_PREREQ(2.57)

AC_INIT(shared-color-targets, 0.0.1, richard@hughsie.com)
AM_INIT_AUTOMAKE(AC_PACKAGE_NAME, AC_PACKAGE_VERSION)
AM_CONFIG_HEADER(config.h)

AC_PROG_CC
AC_PROG_LN_S

AC_OUTPUT([
Makefile
targets/Makefile
targets/wolf_faust/Makefile
targets/wolf_faust/reflective/Makefile
targets/wolf_faust/transmissive/Makefile
tools/Makefile
])

echo "
                        shared-color-targets $VERSION
                     =========================
        prefix:                                     ${prefix}
        datadir:                                    ${datadir}
"
