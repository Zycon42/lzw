#
# CMakeLists.txt
# author: Jan Du�ek <dus3k1an@gmail.com>

set(MUL13_LIB_HEADERS
	arithmcodec.h
	arithmencoder.h
	arithmdecoder.h
	bitstream.h
	lzwencoder.h
	lzwdecoder.h
	lzwcommon.h
	utils.h
)

set(MUL13_LIB_SOURCES
	arithmcodec.cpp
	arithmencoder.cpp
	arithmdecoder.cpp
	lzwencoder.cpp
	lzwdecoder.cpp
	utils.cpp
)

add_library(mul13 ${MUL13_LIB_HEADERS} ${MUL13_LIB_SOURCES})
target_link_libraries(mul13)