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

option ( BUILD_EXAMPLES_ENABLED "Enable the building of examples" ON )

set ( THINGS_KIT_INCLUDE_DIR "${CMAKE_SOURCE_DIR/include}" )

add_subdirectory ( src )

if ( BUILD_EXAMPLES_ENABLED )
  add_subdirectory ( examples )
endif ( )
