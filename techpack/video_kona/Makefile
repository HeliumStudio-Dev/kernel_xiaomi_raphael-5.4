# SPDX-License-Identifier: GPL-2.0-only

# auto-detect subdirs
ifeq ($(CONFIG_ARCH_KONA), y)
include $(srctree)/techpack/video_kona/config/konavid.conf
endif

ifeq ($(CONFIG_ARCH_KONA), y)
LINUXINCLUDE    += -include $(srctree)/techpack/video_kona/config/konavidconf.h
endif

ifeq ($(CONFIG_ARCH_SM8150), y)
include $(srctree)/techpack/video_kona/config/sm8150vid.conf
endif

ifeq ($(CONFIG_ARCH_SM8150), y)
LINUXINCLUDE    += -include $(srctree)/techpack/video_kona/config/sm8150vidconf.h
endif

# auto-detect subdirs
ifeq ($(CONFIG_ARCH_LITO), y)
include $(srctree)/techpack/video_kona/config/litovid.conf
endif

ifeq ($(CONFIG_ARCH_LITO), y)
LINUXINCLUDE    += -include $(srctree)/techpack/video_kona/config/litovidconf.h
endif

# auto-detect subdirs
ifeq ($(CONFIG_ARCH_BENGAL), y)
include $(srctree)/techpack/video_kona/config/bengalvid.conf
endif

ifeq ($(CONFIG_ARCH_BENGAL), y)
LINUXINCLUDE    += -include $(srctree)/techpack/video_kona/config/bengalvidconf.h
endif

LINUXINCLUDE    += -I$(srctree)/techpack/video_kona/include \
                   -I$(srctree)/techpack/video_kona/include/uapi

USERINCLUDE     += -I$(srctree)/techpack/video_kona/include/uapi

obj-y +=msm/
