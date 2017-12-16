set(sources main.cpp
	HttpClient.cpp)
add_executable(stock ${sources})
target_link_libraries(stock curl)
