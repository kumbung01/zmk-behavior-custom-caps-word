# Copyright (c) 2025 The ZMK Contributors
# SPDX-License-Identifier: MIT

zephyr_library()

zephyr_library_sources( behavior_caps_word_custom.c )
zephyr_include_directories(${APPLICATION_SOURCE_DIR}/include)
add_dependencies(app zmk_app)
zephyr_library_include_directories(.)
