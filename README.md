## LAB4-0 建立caravel SOC simulation 環境

### **安裝步驟**
https://github.com/bol-edu/caravel-soc_fpga

安裝 RISC-V GCC Toolchains for Linux 詳解
https://github.com/stnolting/riscv-gcc-prebuilt

### **確認安裝成功**
```
$ riscv32-unknown-elf-gcc -v
Using built-in specs.
COLLECT_GCC=riscv32-unknown-elf-gcc
COLLECT_LTO_WRAPPER=/opt/riscv/libexec/gcc/riscv32-unknown-elf/12.1.0/lto-wrapper
Target: riscv32-unknown-elf
Configured with: /tmp/rv_gcc/riscv-gnu-toolchain/gcc/configure --target=riscv32-unknown-elf --prefix=/opt/riscv --disable-shared --disable-threads --enable-languages=c,c++ --with-pkgversion=g1ea978e3066 --with-system-zlib --enable-tls --with-newlib --with-sysroot=/opt/riscv/riscv32-unknown-elf --with-native-system-header-dir=/include --disable-libmudflap --disable-libssp --disable-libquadmath --disable-libgomp --disable-nls --disable-tm-clone-registry --src=/tmp/rv_gcc/riscv-gnu-toolchain/gcc --disable-multilib --with-abi=ilp32 --with-arch=rv32i --with-tune=rocket --with-isa-spec=2.2 'CFLAGS_FOR_TARGET=-Os   -mcmodel=medlow' 'CXXFLAGS_FOR_TARGET=-Os   -mcmodel=medlow'
Thread model: single
Supported LTO compression algorithms: zlib
gcc version 12.1.0 (g1ea978e3066)
```
顯示如以下畫面 左邊的兩個資料都必須要有
![image](https://hackmd.io/_uploads/HkFmgbyL6.png)

