PROJECT(PovRayIO)

INCLUDE_DIRECTORIES(${PovRayIO_SOURCE_DIR})

ADD_LIBRARY(ITKPovRayIO 
  itkPovRayDF3ImageIO.cxx
  itkPovRayDF3ImageIOFactory.cxx)

TARGET_LINK_LIBRARIES(ITKPovRayIO ${ITK_LIBRARIES})
