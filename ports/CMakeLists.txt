add_subdirectory(${AIA_CLOCK_FOLDER} ${CMAKE_CURRENT_BINARY_DIR}/Clock)
add_subdirectory(${AIA_COMMON_FOLDER} ${CMAKE_CURRENT_BINARY_DIR}/Common)
add_subdirectory(${AIA_CRYPTO_FOLDER} ${CMAKE_CURRENT_BINARY_DIR}/Crypto)
add_subdirectory(${AIA_STORAGE_FOLDER} ${CMAKE_CURRENT_BINARY_DIR}/Storage)
add_subdirectory(${AIA_HTTP_FOLDER} ${CMAKE_CURRENT_BINARY_DIR}/HTTP)
add_subdirectory(${AIA_MEMORY_FOLDER} ${CMAKE_CURRENT_BINARY_DIR}/Memory)
add_subdirectory(${AIA_IOT_FOLDER} ${CMAKE_CURRENT_BINARY_DIR}/IoT)
add_subdirectory(${AIA_LWA_FOLDER} ${CMAKE_CURRENT_BINARY_DIR}/LWA)
add_subdirectory(${AIA_BUTTON_FOLDER} ${CMAKE_CURRENT_BINARY_DIR}/Button)
add_subdirectory(${AIA_MICROPHONE_FOLDER} ${CMAKE_CURRENT_BINARY_DIR}/Microphone)
add_subdirectory(${AIA_REGISTRATION_FOLDER} ${CMAKE_CURRENT_BINARY_DIR}/Registration)
add_subdirectory("source")

install(DIRECTORY include/ DESTINATION ${CMAKE_INSTALL_INCLUDEDIR}/aiaconfig)
