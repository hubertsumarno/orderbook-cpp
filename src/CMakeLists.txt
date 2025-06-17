add_library(orderbook_lib
  orderbook.cpp
)

target_include_directories(orderbook_lib
  PUBLIC ${CMAKE_SOURCE_DIR}/include
)

