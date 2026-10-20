# SPDX-License-Identifier: Apache-2.0

zephyr_include_directories(.)

zephyr_linker_sources_ifdef(CONFIG_OPENAMP_RSC_TABLE ROM_SECTIONS rsc_table.ld)
