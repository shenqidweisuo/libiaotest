# libiaotest

## 测试参考

斯凯奇

优衣库

libiao

```plantuml
Title:git 镜像


github -> ubuntu:git clone --mirror
github -> ubuntu:git remote update
github <- ubuntu:git push

ubuntu -> windows:git clone
ubuntu -> windows:git pull
ubuntu <- windows:git push



```
