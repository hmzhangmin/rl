project(rlRangeSensorDemo)

add_executable(
	rlRangeSensorDemo
	rlRangeSensorDemo.cpp
)

target_link_libraries(
	rlRangeSensorDemo
	rlhal
)
