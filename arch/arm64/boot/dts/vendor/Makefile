# SPDX-License-Identifier: GPL-2.0-only
# Copyright (C) 2018-2020 Oplus. All rights reserved.
vendor := $(srctree)/$(src)

#ifndef OPLUS_BUG_STABILITY
#ifneq "$(wildcard $(vendor)/qcom)" ""
#	subdir-y += qcom
#endif
#else
#subdir-y += qcom
# SM8250 (KONA)
ifeq ($(CONFIG_ARCH_KONA),y)
# 8
subdir-y += 19821
# 8 tmo
subdir-y += 19855
# 8 pro
subdir-y += 19811
# 8T
subdir-y += 19805
# 8T tmo
subdir-y += 20809
# 9R
subdir-y += 20828
# Find X3
subdir-y += 20061
# GT Master Explorer edition
subdir-y += 21615
# GT Neo 2
subdir-y += 21619
endif
# SM7250 / SM7225 (LITO / LAGOON)
ifneq ($(filter y,$(CONFIG_ARCH_LITO) $(CONFIG_ARCH_LAGOON)),)
# Nord
subdir-y += 20801
# Nord CE
subdir-y += 20813
# OPPO/Realme SM7250(SM7225) projects (ported from oplus_sm7250)
subdir-y += oplus
endif
#endif
