#--------------------------------------------------------
# The CMakeLists.txt for:                       pHazardPath
# Author(s):                              Zach & Kristen
#--------------------------------------------------------

SET(SRC
  HazardPath.cpp
  HazardPath_Info.cpp
  main.cpp
)

ADD_EXECUTABLE(pHazardPath ${SRC})

TARGET_LINK_LIBRARIES(pHazardPath
   ${MOOS_LIBRARIES}
   apputil
   mbutil
   m
   pthread)

