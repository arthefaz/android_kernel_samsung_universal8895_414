obj-$(CONFIG_ARCH_EXYNOS)       += exynos-el3_mon.o
obj-$(CONFIG_ARCH_EXYNOS)       += exynos-smc.o

# CAL
obj-$(CONFIG_CAL_IF)		+= cal-if/

obj-$(CONFIG_ECT)		+= ect_parser.o

obj-$(CONFIG_EXYNOS_PMU)	+= exynos-pmu.o
obj-$(CONFIG_EPX)             += epx.o

#FSYS0 TCXO
obj-$(CONFIG_ARCH_EXYNOS)	+= exynos-fsys0-tcxo.o

obj-$(CONFIG_EXYNOS_PMU_ARM_DRIVERS)	+= exynos3250-pmu.o exynos4-pmu.o \
					exynos5250-pmu.o exynos5420-pmu.o
obj-$(CONFIG_EXYNOS_BCM_DBG)    += exynos-bcm_dbg.o exynos-bcm_dbg-dt.o
obj-$(CONFIG_EXYNOS_BCM_DBG_DUMP)       += exynos-bcm_dbg-dump.o

obj-$(CONFIG_EXYNOS_CHIPID)	+= exynos-chipid.o

# ACPM
obj-$(CONFIG_EXYNOS_ACPM)       += acpm/

obj-$(CONFIG_EXYNOS_RGT)        += exynos-rgt.o
obj-$(CONFIG_EXYNOS_FLEXPMU_DBG)        += exynos-flexpmu-dbg.o

obj-$(CONFIG_EXYNOS_REBOOT)     += exynos-reboot.o

# DEBUG
obj-$(CONFIG_EXYNOS_DEBUG)      += debug/
# DVFS
obj-$(CONFIG_EXYNOS_DVFS_MANAGER)	+= exynos-dm.o

# PD
obj-$(CONFIG_EXYNOS_PD)        += exynos-pd.o exynos-pd-dbg.o
obj-$(CONFIG_EXYNOS_PM_DOMAINS) += pm_domains.o
#CPUHOTPLUG
obj-$(CONFIG_ARCH_EXYNOS)	+= exynos-cpuhp.o

# CPU Topology
#obj-$(CONFIG_ARCH_EXYNOS)	+= exynos-topology.o

# OCP
obj-$(CONFIG_EXYNOS_OCP)	+= exynos-ocp.o

# CP
ifneq ($(CONFIG_CP_PMUCAL), y)
obj-$(CONFIG_EXYNOS_MODEM_IF) += pmu-cp.o
endif

#CPU Power Management
obj-$(CONFIG_EXYNOS_PM)		+= exynos-cpupm.o

#PM
obj-$(CONFIG_EXYNOS_PM)		+= exynos-powermode.o
obj-$(CONFIG_EXYNOS_PM)		+= exynos-pm.o

# Exynos Secure Log
obj-$(CONFIG_EXYNOS_SECURE_LOG)	+= exynos-seclog.o

# HDCP
obj-$(CONFIG_EXYNOS_HDCP2)  += exynos-hdcp/

# SDM
obj-$(CONFIG_EXYNOS_SDM) += exynos-sdm.o

# USI
obj-$(CONFIG_USI) += usi.o

# USI_V2
obj-$(CONFIG_USI_V2) += usi_v2.o

# secmem
obj-$(CONFIG_ARCH_EXYNOS)       += secmem.o

# HIU
obj-$(CONFIG_EXYNOS_HIU)	+= exynos-hiu.o

# HAFM & HAFM-TB
obj-$(CONFIG_EXYNOS_PSTATE_HAFM)	+= exynos-hafm.o
obj-$(CONFIG_EXYNOS_PSTATE_HAFM_TB)	+= exynos-hafm-tb.o

obj-$(CONFIG_EXYNOS_MODEM_IF) += cpif/

obj-$(CONFIG_SAM_ABOX_CP_SHMEM_RESERVE) += sam-abox-cp-shmem-reserve.o

# GNSS interface driver
obj-$(CONFIG_EXYNOS_GNSS_IF) += gnssif/

# Exynos PPMPU fail detector
obj-$(CONFIG_EXYNOS_PPMPU_FAIL_DETECTOR)	+= exynos-ppmpu.o

# Exynos TZASC fail detector
obj-$(CONFIG_EXYNOS_TZASC_FAIL_DETECTOR)	+= exynos-tzasc.o

# Exynos CPU Performance
obj-$(CONFIG_EXYNOS_CPU_PERF)	+= exynos_cpu_perf/
