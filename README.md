# UD6S-V1.0-Linux20210616-gouhao
水星UD6S Linux驱动

> 注意: 本驱动是非官方驱动。因为官方驱动没有适配最新的内核，所以我自己适配了。**如果你使用我适配过的驱动，自己承担风险！**

## 安装方法
```sh
make -j8 && sudo make install
sudo modprobe 8821cu
```

## ChangeLog
### 2023-03-19
- 适配6.1内核

### 2023-01-07
- 适配了5.15内核
