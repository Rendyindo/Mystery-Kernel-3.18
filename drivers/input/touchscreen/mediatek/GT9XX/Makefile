# Linux driver folder
ccflags-y += -I$(srctree)/drivers/input/touchscreen/mediatek/GT9XX/
ccflags-y += -I$(srctree)/drivers/input/touchscreen/mediatek/
ccflags-y += -I$(srctree)/drivers/input/touchscreen/mediatek/GT9XX/$(CONFIG_GT9XX_FIRMWARE)/
ccflags-y += -I$(srctree)/drivers/input/touchscreen/mediatek/GT9XX/$(CONFIG_GT9XX_CONFIG)/
ccflags-y += -I$(srctree)/drivers/misc/mediatek/include/mt-plat/
ccflags-y += -I$(srctree)/drivers/misc/mediatek/include/mt-plat/$(MTK_PLATFORM)/include/

obj-y	+=  gt9xx.o
obj-y	+=  goodix_tool.o
obj-y	+=  gt9xx_update.o

