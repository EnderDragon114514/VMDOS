# VMDOS——一个基于MSDOS8.0(Windows Millium Edition的DOS版)的操作系统

### 这是一个BIOS启动的16位操作系统，无法在UEFI及启用了SafeBoot的电脑上使用

## Part 1 工作原理

启动原理:

MBR->MSDOS原版Command.com->驱动->autoexec->init.exe

编写语言:C++、ASM
## Part 2 适用电脑

1.VMware的DOS虚拟机

2.VirtualBox的DOS虚拟机

3.LimboX86和Qemu虚拟机

4.BIOS启动的实体机，16位以上，64位以下

# 最后希望大家点一下右上角的Star支持一下吧！

