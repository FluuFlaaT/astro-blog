---
title: "我的ThinkPad & Arch使用新的体验兼流水账"
description: "折腾ThinkPad X1 Carbon的经历"
publishDate: 2023-11-01 00:00:00 +0800
tags: 
    - ThinkPad
    - Linux
---

## 0. 我为什么喜欢ThinkPad

~~其实这个问题可能要称为：我为什么喜欢X1 Carbon~~

我的第一台ThinkPad就是我手上这一台X1 Carbon了。它够轻便、续航比我的游戏本长，看起来比较坚固，键盘手感也比Y9000X因为厚度而妥协的键盘要好。

不过似乎很多人都怀念以前ThinkPad的七行键盘。摸过之后觉得七行键盘的手感似曾相识。哦，是我人生第一台笔记本，联想F41的同款键盘。

还有一点就是，ThinkPad整个品牌对Linux就很友好，基本也不需要另外打驱动，并且之前联想也有发售预装Linux的ThinkPad。

## 1. 为什么我要拿来装 Linux 

原因是：Windows续航差、风扇常年满转速、X1C性能不足以支撑运行Windows。

或许听起来有点奇怪——为什么Wintel笔记本不适合装Windows。那只能说是微软有点问题在里面了。

可能最开始我也就只是把X1C当成一块试验田，或许当我在ThinkPad上能够用好Arch之后，我就会在Y9000X上安装Arch，但是Y9000X上的3060要驱动起来还是更为麻烦一点。

> 2023/12/31 Update:
> 已经装上了，但是NV的驱动对wayland的支持就是依托。懒得用。

## 2. Arch 给这台电脑和我的生活带来了什么

### 1. 回归原始的续航表现

X1C & Arch 的性能表现，我觉得是秒杀Windows的。静止状态下，电脑的单风扇基本是处于不运转的状态，CPU的利用率也不高，甚至可以说是**低**。

![htop的截图](https://s2.loli.net/2023/10/26/En1PwlNiL6thHRC.png)

这使得它的功耗也不高，电池电量可以从早八撑到下午四五点的样子。

### 2. 驱动不用太操心

由于联想在前几年就已经将自己的电源管理驱动合入了Linux内核，且X1C使用的都是Intel的核显及网卡，这台电脑在安装完成之后可以说是能够立即投入使用。

### 3. 在实体机中学习Linux

在此之前，我一直使用的是Windows Subsystem for Linux的Ubuntu 20.04。这也是我第一次尝试使用除Uuu之外的distro。除了安装界面很原始之外，其余都还是不错的。

我的常用软件，如Vivado和一些IDE,都提供且能够在Linux下完美运行，有的甚至是可以运行得更顺畅。

## 3. 我在Arch Linux 里面学到了什么东西

### 1. 系统是怎么装的 | 装系统是怎么个过程

在接触Arch Linux的这几个月里，我至少重装了三次这个系统。分区、挂载、pacstrap、chroot......现在已经是轻车熟路了。

### 2. 怎么上网排错 & 用英文搜索解决方案

现在的生活已经完全离不开StackOverflow、Arch Linux Wiki和Reddit了。我的赛博诊所。

**未完待续**