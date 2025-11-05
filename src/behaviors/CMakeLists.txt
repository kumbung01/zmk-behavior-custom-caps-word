# Copyright (c) 2025 The ZMK Contributors
# SPDX-License-Identifier: MIT

zephyr_library()

zephyr_library_sources( behavior_caps_word_custom.c )
zephyr_include_directories(${APPLICATION_SOURCE_DIR}/include)
zephyr_library_include_directories(.)
zephyr_library_link_libraries(zmk)