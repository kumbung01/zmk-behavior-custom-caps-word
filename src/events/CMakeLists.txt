zephyr_include_directories(include)
zephyr_include_directories(${APPLICATION_SOURCE_DIR}/include)
zephyr_library()

zephyr_library_sources(caps_word_state_changed.c)
