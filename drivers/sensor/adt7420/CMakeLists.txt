# SPDX-License-Identifier: Apache-2.0

zephyr_library()

zephyr_library_sources(adt7420.c)
zephyr_library_sources_ifdef(CONFIG_ADT7420_TRIGGER adt7420_trigger.c)
