obj-y += timer.o io.o devices.o iomux.o clock.o rk29-pl330.o dma.o gpio.o ddr.o sram.o memcpy_dma.o reset.o
obj-y += tests.o memtester.o
obj-y += early_printk.o
ifndef CONFIG_DEBUG_LL
obj-y += ../kernel/debug.o
endif
obj-$(CONFIG_RK29_LAST_LOG) += last_log.o
obj-$(CONFIG_USB_GADGET) += usb_detect.o
obj-$(CONFIG_PM) += pm.o
obj-$(CONFIG_CPU_FREQ) += cpufreq.o
obj-$(CONFIG_RK29_VPU) += vpu_mem.o
obj-y += spi_sram.o
obj-$(CONFIG_RK29_VPU_SERVICE) += vpu_service.o
obj-$(CONFIG_RK29_VPU_OLD) += vpu.o
obj-$(CONFIG_RK29_PWM_INSRAM) += pwm_sram.o
obj-$(CONFIG_MACH_RK29SDK) += board-rk29sdk.o board-rk29sdk-key.o board-rk29sdk-rfkill.o board-rk29sdk-power.o
obj-$(CONFIG_MACH_RK29_P91) += board-rk29-p91.o board-rk29-p91-key.o board-rk29sdk-rfkill.o board-rk29sdk-power.o
obj-$(CONFIG_MACH_RK29SDK_DDR3) += board-rk29-ddr3sdk.o board-rk29sdk-key.o board-rk29sdk-rfkill.o board-rk29sdk-power.o
obj-$(CONFIG_MACH_RK29WINACCORD) += board-rk29-winaccord.o board-rk29sdk-key.o
obj-$(CONFIG_MACH_RK29_MALATA) += board-malata.o board-rk29malata-key.o board-rk29sdk-rfkill.o
obj-$(CONFIG_MACH_RK29_PHONESDK) += board-rk29-phonesdk.o board-rk29-phonesdk-key.o board-rk29-phonesdk-rfkill.o
obj-$(CONFIG_MACH_RK29FIH) += board-rk29-fih.o board-rk29-fih-key.o board-rk29sdk-rfkill.o board-rk29sdk-power.o
obj-$(CONFIG_MACH_RK29_A22) += board-rk29-a22.o board-rk29-a22-key.o board-rk29-a22-rfkill.o
obj-$(CONFIG_MACH_RK29_PHONEPADSDK) += board-rk29phonepadsdk.o board-rk29phonepadsdk-key.o board-rk29phonepadsdk-rfkill.o board-rk29phonepadsdk-power.o
obj-$(CONFIG_MACH_RK29_newton) += board-rk29-newton.o board-rk29-newton-key.o board-rk29sdk-rfkill.o board-rk29sdk-power.o

