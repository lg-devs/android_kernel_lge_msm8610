ccflags-y += -Idrivers/media/platform/msm/camera_v2
ccflags-y += -Idrivers/media/platform/msm/camera_v2/sensor/io
obj-$(CONFIG_MSMB_CAMERA) += msm_led_flash.o
obj-$(CONFIG_MSMB_CAMERA) += msm_led_trigger.o
obj-$(CONFIG_BACKLIGHT_RT8542) += msm_led_i2c_trigger.o
obj-$(CONFIG_BACKLIGHT_RT8542) += rt8542.o
obj-$(CONFIG_MSMB_CAMERA) += msm_led_torch.o

# LG doesn't use a lot of variables, but keep them anyway
EXTRA_CFLAGS += -Wno-unused-variable
