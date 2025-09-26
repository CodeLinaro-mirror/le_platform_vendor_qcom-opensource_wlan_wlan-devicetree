dtbo-y += qcm6490-wlan-idb.dtbo
dtbo-y += qcm6490-wlan-rb3.dtbo

ifeq ($(TARGET_SUPPORT), sa535m)
M=$(PWD)
dtbo-y += sa535m-cnss.dtbo
endif
always-y        := $(dtb-y) $(dtbo-y)
subdir-y        := $(dts-dirs)
clean-files	:= *.dtb *.dtbo
