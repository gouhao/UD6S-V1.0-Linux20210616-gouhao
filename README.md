# UD6S-V1.0-Linux20210616-gouhao
水星UD6S Linux驱动，适配了5.15

在5.15内核上，直接编译安装就可以用了。
```sh
make -j8 && sudo make install
sudo modprobe 8821cu
```
