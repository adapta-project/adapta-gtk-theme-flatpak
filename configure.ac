m4_define([adapta_fp_major_version], [3])
m4_define([adapta_fp_minor_version], [92])
m4_define([adapta_fp_micro_version], [2])
m4_define([adapta_fp_version], [adapta_fp_major_version.adapta_fp_minor_version.adapta_fp_micro_version])
m4_define([adapta_fp_git_url], [https://github.com/adapta-project/adapta-gtk-theme-flatpak])

AC_INIT(
	[Adapta-Flatpak ],
	[adapta_fp_version],
	[adapta_fp_git_url],
	[adapta-gtk-theme-flatpak]
)
AC_CONFIG_MACRO_DIR([m4])
AM_INIT_AUTOMAKE([
	-Wno-portability \
	no-dist-gzip \
	dist-xz \
	foreign \
	subdir-objects \
	1.9 \
	tar-ustar
])
AC_PREFIX_DEFAULT(/usr/share/runtime)
AM_SILENT_RULES([yes])

ADAPTA_FLATPAK_OPTION([DARK],    [dark],    [dark-variant-only],    [disable])
ADAPTA_FLATPAK_OPTION([COMPACT], [compact], [compact-variant-only], [disable])

AC_CONFIG_FILES([Makefile])
AC_OUTPUT
AC_MSG_RESULT([
        Adapta Gtk+ Theme $VERSION for Flatpak
        ===========================================================

         prefix:                 ${prefix}
         themerootdir:           ${datarootdir}/themes
         color variant:          DarkVariantOnly:    $ENABLE_DARK
         size variant:           CompactVariantOnly: $ENABLE_COMPACT

        -----------------------------------------------------------
        | Supported Gtk+ Version
        -----------------------------------------------------------

         Gtk+ 3.22:              always

        ===========================================================
                             =>> run 'make' and 'sudo make install'
])
