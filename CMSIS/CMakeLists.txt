# SPDX-License-Identifier: Apache-2.0

add_subdirectory_ifdef(CONFIG_HAS_CMSIS_CORE_M Core)
add_subdirectory_ifdef(CONFIG_HAS_CMSIS_CORE_A Core_A)
add_subdirectory_ifdef(CONFIG_HAS_CMSIS_CORE_R Core_R)
