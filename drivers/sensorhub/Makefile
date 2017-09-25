#
# Makefile for the sensor hub.
#
ifneq ($(CONFIG_SENSORS_SSP_DREAM),y)
obj-$(CONFIG_SENSORS_SSP_BBD)	+= brcm/
else
obj-$(CONFIG_SENSORS_SSP_BBD)	+= brcm_dream/
endif
obj-$(CONFIG_SENSORS_SSP_STM)	+= stm/
obj-$(CONFIG_SENSORS_SSP_ATMEL)	+= atmel/
