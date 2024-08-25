# SPDX-License-Identifier: GPL-2.0
dtb-$(CONFIG_ARCH_EXYNOS) += \
	exynos5433-tm2.dtb	\
	exynos5433-tm2e.dtb	\
	exynos7-espresso.dtb

dtb-$(CONFIG_SOC_EXYNOS8895) += \
	exynos8895-dream2lte.dtb	\
	exynos8895-dreamlte.dtb	\
	exynos8895-greatlte.dtb

dtb-$(CONFIG_SOC_EXYNOS9610) += exynos9610-erd9610.dtb

dtb-$(CONFIG_SOC_EXYNOS9810) += \
	exynos9810-star2lte.dtb	\
	exynos9810-starlte.dtb	\
	exynos9810-crownlte.dtb

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb
