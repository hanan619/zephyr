# SPDX-License-Identifier: Apache-2.0

zephyr_library()

zephyr_library_sources_ifdef(CONFIG_PCIE_BRCMSTB pcie_brcmstb.c)
