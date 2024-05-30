[使用 Assembly 和 C 编写引导加载程序 - 第 1 部分 - CodeProject](https://www.codeproject.com/Articles/664165/Writing-a-boot-loader-in-Assembly-and-C-Part)

##### 20240530学习内容

###### 1 Bootable Devices可启动设备

BIOS：

- BIOS是嵌入在BIOS芯片中的特殊程序。
- 执行 BIOS 程序，然后执行以下任务。
- 运行 Power On 自检。
- 检查时钟和各种可用的总线。
- 检查CMOS RAM中的系统时钟和硬件信息
- 验证系统设置、预配置的硬件设置等，
- 从 RAM、磁盘驱动器、光驱、硬件驱动器等设备开始测试连接的硬件。
- 根据 BIOS 可启动设备信息中的预配置信息，它会根据设置中提供的信息搜索启动驱动器，并开始初始化它以继续操作。

1 可启动设备：如果一个设备包含一个启动的启动器或引导块，并且bios通过第一次将启动的启动器加载到内存（RAM）中进行执行，然后继续执行，那么该设备就是可引导的设备。

2 扇区是可启动磁盘的特定大小的分区。通常，扇区的大小为 512 字节。在接下来的章节中，我将向您解释更多关于如何测量计算机内存以及与之相关的各种术语。

3 引导扇区或引导块是可启动设备上的一个区域，其中包含计算机系统的内置固件在初始化期间要加载到 RAM 中的机器代码。它在软盘上有 512 个字节。

[参考链接]

1.[Awesome-Embedded](https://github.com/nhivp/Awesome-Embedded)

2.[MultiButton](https://github.com/0x1abin/MultiButton)

3.[MultiTimer](https://github.com/0x1abin/MultiTimer)

4.[EasyLogger](https://github.com/armink/EasyLogger)

5.[CodeBrick](https://gitee.com/moluo-tech/CodeBrick)

