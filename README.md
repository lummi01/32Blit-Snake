# 32Blit Snake

This is a simple Snake Game for the Pimoroni 32Blit Handheld.

It's based on the original `template` project from the 
[32Blit](https://github.com/32blit/32blit-sdk).

## Usage

For 32Blit Snake build:
```
mkdir build.stm32
cd build.stm32
cmake .. -D32BLIT_DIR="/path/to/32blit/repo" -DCMAKE_TOOLCHAIN_FILE=/path/to/32blit/repo/32blit.toolchain
make
```

For local Snake build:
```
mkdir build
cd build
cmake -D32BLIT_DIR=/path/to/32blit-sdk/ ..
make
```
