obj-$(CONFIG_FB_ROCKCHIP) += rk_fb.o rkfb_sysfs.o
obj-$(CONFIG_FB_WIMO) +=wimo.o
obj-$(CONFIG_LCDC_RK30) += lcdc/rk30_lcdc.o 
obj-$(CONFIG_LCDC_RK2928) += lcdc/rk2928_lcdc.o
obj-$(CONFIG_LCDC_RK3066B) += lcdc/rk3066b_lcdc.o 
obj-$(CONFIG_RGA_RK30) += rga/
obj-$(CONFIG_RK_HDMI) += hdmi/
obj-$(CONFIG_RK_LVDS) += lvds/
ifneq ($(CONFIG_UMP),)
obj-m += disp_ump.o
EXTRA_CFLAGS += -Idrivers/gpu/ump/include
endif