# zero_os
该项目为个人学习项目，使用Rust语言编写的可以在裸机上运行的程序，目标平台为x86_64位CPU

编译：cargo xbuild

创建镜像：cargo bootimage 成功后生成bootimage-zero_os.bin

运行方式 qemu-system-x86_64 -drive format=raw,file=bootimage-zero_os.bin

![图片](https://user-images.githubusercontent.com/6795484/139184792-0b81f294-d3b0-4435-9089-270481467238.png)
