cmake_minimum_required(VERSION 2.8.4)

install(
  DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR}/boost_beast/include
  DESTINATION "/usr"
  )

set(CPACK_GENERATOR DEB)
set(CPACK_PACKAGE_NAME boost-beast)
set(CPACK_PACKAGE_VERSION "1.0.1")
set(CPACK_PACKAGE_CONTACT davtyaneg@gmail.com)
include(CPack)
