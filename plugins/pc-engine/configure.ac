# When there are no modules to check, default to 'no', hence we need to
# force it to 'yes'.
#PKG_CHECK_MODULES(PC_ENGINE_PLUGIN, [
#], [enable_pc_engine_plugin=yes], [enable_pc_engine_plugin=no])
enable_pc_engine_plugin=yes

# Checks for programs.
AC_PROG_CXX
AC_PROG_CC
AC_PROG_CPP
AC_PROG_INSTALL
AC_PROG_LN_S
AC_PROG_MAKE_SET


AM_CONDITIONAL(ENABLE_PC_ENGINE_PLUGIN, test x$enable_pc_engine_plugin != xno)

AC_CONFIG_FILES([
	plugins/pc-engine/Makefile
])
