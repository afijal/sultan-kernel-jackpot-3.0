ccflags-y := -O3 -fgcse-lm -fgcse-sm -fsched-spec-load -fforce-addr -fsingle-precision-constant -mtune=cortex-a8 -marm -march=armv7-a -mfpu=neon -ftree-vectorize -mvectorize-with-neon-double

obj-$(CONFIG_VIDEO_MFC50) += mfc.o mfc_buffer_manager.o mfc_intr.o mfc_memory.o mfc_opr.o mfc_shared_mem.o

ifeq ($(CONFIG_VIDEO_MFC50_DEBUG),y)
EXTRA_CFLAGS += -DDEBUG
endif

#EXTRA_CFLAGS += -DMFC_REQUEST_TIME
