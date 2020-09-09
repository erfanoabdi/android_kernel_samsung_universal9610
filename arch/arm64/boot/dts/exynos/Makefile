# SPDX-License-Identifier: GPL-2.0
ifneq ($(CONFIG_SOC_EXYNOS9610),y)
dtb-$(CONFIG_ARCH_EXYNOS) += \
	exynos5433-tm2.dtb	\
	exynos5433-tm2e.dtb	\
	exynos7-espresso.dtb
endif

dtb-$(CONFIG_SOC_EXYNOS9610) += \
	exynos9610.dtb

dtbo-$(CONFIG_MACH_SAMSUNG_GALAXY_A51) += \
	a51/exynos9611-a51_eur_open_00.dtbo	\
	a51/exynos9611-a51_eur_open_01.dtbo	\
	a51/exynos9611-a51_eur_open_03.dtbo

always		:= $(dtb-y) $(dtbo-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb*
