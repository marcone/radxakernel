# Overlays for the ROCK Pi 4 platform

dtbo-$(CONFIG_ARCH_ROCKCHIP) += \
	console-on-ttyS4.dtbo \
	console-on-ttyS2.dtbo \
	two-color-led.dtbo \
	at24c02.dtbo \
	devspi1.dtbo \
	devspi2.dtbo \
	pcie-gen2.dtbo \
	spi1-waveshare35c.dtbo \
	spi1-waveshare35b-v2.dtbo \
	spi1-flash.dtbo \
	spi1-mcp2515-can0.dtbo \
	hifiberry-dac.dtbo \
	hifiberry-dacplus.dtbo \
	raspberrypi-7-inch-lcd.dtbo \
	gt9xx.dtbo \
	cpufreq.dtbo \
	imx219.dtbo \
	ov5647.dtbo \
	w1-gpio4-30.dtbo

targets += dtbs dtbs_install
targets += $(dtbo-y)

always		:= $(dtbo-y)
clean-files	:= *.dtbo
