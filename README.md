# 32Blit Snake

This is a simple Snake Game for the Pimoroni 32Blit Handheld.

It's based on the original `template` project from the 
[32Blit Beta](https://github.com/pimoroni/32blit-beta), with added asset
handling, and some tidying up to fit in with how I do things.

## Usage

[Use this template](https://github.com/32blit/32blit-boilerplate/generate) to
generate your own project.

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

Platform/Editor specific insctuctions [can be found in the main 32blit repo](https://github.com/pimoroni/32blit-beta#more-docs)
(For Visual Studio, you should follow the "Option 2" instructions, as the boilerplate does not contain a solution file)
