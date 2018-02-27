obj-$(CPTCFG_VIDEO_TI_VPE) += ti-vpe.o
obj-$(CPTCFG_VIDEO_TI_VPE) += ti-vpdma.o
obj-$(CPTCFG_VIDEO_TI_VPE) += ti-sc.o
obj-$(CPTCFG_VIDEO_TI_VIP) += ti-vip.o
obj-$(CPTCFG_VIDEO_TI_VIP) += ti-vpdma.o
obj-$(CPTCFG_VIDEO_TI_VIP) += ti-sc.o

ti-vpe-y := vpe.o csc.o
ti-vpdma-y := vpdma.o
ti-sc-y := sc.o
ti-vip-y := vip.o

ccflags-$(CPTCFG_VIDEO_TI_VPE_DEBUG) += -DDEBUG

obj-$(CPTCFG_VIDEO_TI_CAL) += ti-cal.o

ti-cal-y := cal.o
