# python3.11


```bash
tar xzf Python-3.10.0.tgz
```

编译Python源码

进入解压后的文件夹内，进行选项配置

```bash
cd Python-3.10.0

./configure --enable-optimizations

#--enable-optimizations为优化性能选项，其余类似的还有 --prefix=PATH 指定安装目录……，可根据需要进行选择。
#默认安装路径为 /usr/local/bin
```

安装Python 3.11

```bash
make altinstall
```
