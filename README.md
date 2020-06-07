# BNHook (v1.1)
Author: **Grant Orndorff**
_Insert custom hooks_
## Description:

Write a hook in assembly and have it execute as part of your binary. See your hook added to the binary and reflected in the disassembly graph. The code segment of the binary is extended to make room for the hook. After insertion, Save Contents As and run the binary with your inserted code!

Currently supports x86 and x86_64 ELF executables. This tool uses the shellcode compiler within BinaryNinja to compile your assembly snippet. Which means you have the convenience and flexibility of the scc and do not need to worry about whether the code fits into the space. 

## Installation Instructions

### Windows

pip install filebytes or pip3 install filebytes

### Linux

pip install filebytes or pip3 install filebytes

### Darwin

pip install filebytes or pip3 install filebytes

## Usage

1. Right-click at the place you wish to insert a hook and select `Insert Custom Hook` from the menu. 
2. Give it a name you like. 
3. If you would like to type the assembly code, select `asm textbox` and click `OK`. If you have a prepared asm file, select `asm file` and click `OK`. 

## Minimum Version

This plugin requires the following minimum version of Binary Ninja:

 * 1407



## Required Dependencies

The following dependencies are required for this plugin:

 * pip - filebytes


## License

This plugin is released under a MIT license.
## Metadata Version

2
