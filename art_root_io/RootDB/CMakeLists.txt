art_make_library(LIBRARY_NAME
  art_root_io_RootDB
  SOURCE
  SQLErrMsg.cc
  SQLite3Wrapper.cc
  TKeyVFSOpenPolicy.cc
  tkeyvfs.cc
  LIBRARIES
  art_Utilities
  canvas
  cetlib
  cetlib_except
  MF_MessageLogger
  ${CMAKE_DL_LIBS}
  ${ROOT_RIO}
  ${ROOT_CORE}
  ${SQLITE3})

install_headers()
install_source()
