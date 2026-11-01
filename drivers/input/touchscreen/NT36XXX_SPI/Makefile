# Makefile for the Novatek NT36xxx touchscreen driver.
ccflags-$(CONFIG_DRM_MEDIATEK_V2) += -I$(srctree)/drivers/gpu/drm/mediatek/mediatek_v2/
obj-$(CONFIG_TOUCHSCREEN_NT36xxx_HOSTDL_SPI) += nvt_36xxx.o
nvt_36xxx-y += nt36xxx.o
nvt_36xxx-y += nt36xxx_fw_update.o
nvt_36xxx-y += nt36xxx_ext_proc.o
