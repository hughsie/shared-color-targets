AC_PREREQ(2.65)

AC_INIT([shared-color-targets],[0.1.6],[richard@hughsie.com])
AC_CONFIG_HEADERS([config.h])
AC_CONFIG_MACRO_DIR([m4])
AC_CONFIG_AUX_DIR([build-aux])
AM_INIT_AUTOMAKE([1.11 no-dist-gzip dist-xz tar-ustar])
AM_SILENT_RULES([yes])

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
