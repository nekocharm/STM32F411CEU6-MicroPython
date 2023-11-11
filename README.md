# STM32F411CEU6-MicroPython

使用 WeAct 的 STM32F411CEU6 Board

## How to build 如何编译

```
git clone https://github.com/micropython/micropython.git
cd micropython
git submodule update --init
cd mpy-cross
make
cd ../ports/stm32/boards
git clone https://github.com/nekocharm/STM32F411CEU6-MicroPython.git
cd ..
make BOARD=STM32F411CEU6-MicroPython
```

