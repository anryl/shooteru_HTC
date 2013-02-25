#
# Makefile for the Linux Bluetooth RFCOMM layer.
#
EXTRA_CFLAGS += -fno-strict-aliasing
obj-$(CONFIG_BT_RFCOMM) += rfcomm.o

rfcomm-y			:= core.o sock.o
rfcomm-$(CONFIG_BT_RFCOMM_TTY)	+= tty.o
