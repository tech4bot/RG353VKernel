build: \
`make ARCH=arm64 rk3566_optimized_with_wifi_linux_defconfig && make ARCH=arm64 KERNEL_DTS=rk3566 KERNEL_CONFIG=rk3566_optimized_with_wifi_linux_defconfig`
sudo apt install bison flex -y 