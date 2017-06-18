### configure.ac					-*- Autoconf -*-

AC_PREREQ(2.62)

AC_INIT([xgboost],[0.6-3],[],[xgboost],[])

OPENMP_CXXFLAGS=""

OPENMP_CXXFLAGS="\$(SHLIB_OPENMP_CFLAGS)"
ac_pkg_openmp=yes


AC_SUBST(OPENMP_CXXFLAGS)
AC_CONFIG_FILES([src/Makevars])
AC_OUTPUT

