# Caravel Wishbone Timings

## Setup

1. Install Sky130A PDK, set `PDK_ROOT` environment variable to the path of the installed PDK.
2. Clone caravel_user_project (mpw-9a tag), set `DESIGNS` environment variable to the path of the cloned caravel.
3. Clone mgmt_core_wrapper (mpw-9a tag), set `MCW_ROOT` environment variable to the path of the cloned mgmt_core_wrapper.
4. Set `CORE_VERILOG_PATH` to `"${MCW_ROOT}/verilog"`
5. Install riscv64-unknown-elf-gcc (https://github.com/sifive/freedom-tools/releases), set GCC_PATH to point to the bin directory of the installed toolchain.
6. `pip install -r requirements.txt`
