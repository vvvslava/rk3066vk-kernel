Sources Kernel 3.0.36+ for MaxwellPlus

Toolchains:
git clone https://android.googlesource.com/platform/prebuilt
Para usar Toolchains:
export PATH=~/prebuilt/linux-x86/toolchain/arm-eabi-4.4.3/bin:$PATH

Para compilar:
make cyanogenmod_maxwellplus_defconfig
make o make kernel.img

Gracias a Kra1o5 