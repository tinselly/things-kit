cmake_minimum_required ( VERSION 3.19.0 )

project (
  things-kit
    VERSION 
      0.0.0
    DESCRIPTION
      ""
    HOMEPAGE_URL
      "https://github.com/tinselly/things-kit"
    LANGUAGES
      CXX
)

set ( THINGS_KIT_INCLUDE_DIR "${CMAKE_SOURCE_DIR/include}" )

add_subdirectory ( src )

