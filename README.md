# AVaRICE
AVaRICE is a program which interfaces with the GNU Debugger GDB in order to debug AVR microcontrollers.

## Installation
```bash
cd AVaRICE/avarice/
./Boostrap
./configure
make
```

You need **libhidapi** to use (m)EDBG.
If you get `EDBG/CMSIS-DAP devices require libhidapi support`, install libhid and rerun the installation.
