#==============================================================================
# 
#        OpenSees -- Open System For Earthquake Engineering Simulation
#                Pacific Earthquake Engineering Research Center
#
#==============================================================================
target_sources(OPS_Material
  PRIVATE
    PyLiq1.cpp
    PySimple1.cpp
    PySimple1Gen.cpp
    PySimple2.cpp
    PySimple3.cpp
    QzLiq1.cpp
    QzSimple1.cpp
    QzSimple2.cpp
    ShallowFoundationGen.cpp
    TzLiq1.cpp
    TzSimple1.cpp
    TzSimple1Gen.cpp
    TzSimple2.cpp
)

target_include_directories(OPS_Material PUBLIC ${CMAKE_CURRENT_LIST_DIR})