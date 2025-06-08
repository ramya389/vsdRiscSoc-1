# vsdRiscSoc
1. Toolchain Installation & Verification
Unpack the RISC-V toolchain using tar -xzf riscv-toolchain-rv32imac-x86_64-ubuntu.tar.gz

Add to PATH by editing ~/.bashrc: export PATH=$HOME/riscv/bin:$PATH

Verify with riscv32-unknown-elf-gcc --version and similar commands

COMMANDS:
tar -xzf riscv-toolchain-rv32imac-x86_64-ubuntu.tar.gz
export PATH=$HOME/riscv/bin:$PATH
echo 'export PATH=$HOME/riscv/bin:$PATH' >> ~/.bashrc

Verification:
riscv32-unknown-elf-gcc --version
riscv32-unknown-elf-objdump --version
riscv32-unknown-elf-gdb --version
