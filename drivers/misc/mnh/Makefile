#
# Makefile for MNH PCIE/DMA devices
#

obj-$(CONFIG_MNH_PCIE_HOST) += mnh-pcie.o
obj-$(CONFIG_MNH_SM_HOST) += mnh-sm.o mnh-sm-ion.o mnh-pwr.o mnh-mipi.o mnh-ddr.o mnh-clk.o
obj-$(CONFIG_MNH_THERMAL_HOST) += mnh-thermal.o mnh-efuse.o
obj-$(CONFIG_MNH_SIG) += mnh-crypto.o mnh-crypto-sysfs.o
# TODO: remove me b/62058353
subdir-ccflags-y += \
	-Wno-pointer-bool-conversion \


