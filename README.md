# openwrt-packages
国内常用OpenWrt软件包源码合集，每天自动更新，建议使用lean源码

## 食用方式（三选一）：
`还是建议按需取用，不然碰到依赖问题不太好解决`
1. 先cd进package目录，然后执行
```bash
 git clone https://github.com/1287329/openwrt-packages
```
2. 或者添加下面代码到feeds.conf.default文件
```bash
 src-git liuran001_packages https://github.com/1287329/openwrt-packages
```
3. 先cd进package目录，然后执行
```bash
 svn co https://github.com/1287329/openwrt-packages/branches/packages
```
