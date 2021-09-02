# 文件目录结构
bochsConfig目录放置bochs配置文件
wayne-os目录放置系统代码
hd.img为磁盘文件
hd.info为磁盘信息

# 运行

```shell
# 直接运行Bochs
./run

# 运行Bochs汇编调试
./rundbg

# 运行Bochs gdb调试
./run gdb
# 同时打开gdb，输入target remote localhost:1234
gdb target remote localhost:1234
```

