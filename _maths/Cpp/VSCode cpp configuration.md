---
title: Visual Studio Code configuration
layout: page
categories: cpp
---



# VSCode：搭建一个简易的 C++ 环境

>   status: update if needed;
>
>   description: 比如刷刷 LeetCode，就不需要特别多的配置，简单的环境就够了；

## 0x00

首先新建一个 Profile：

![image-20230822170442988](https://p.ipic.vip/1tii57.png)

比如这里明命名为`C++`:

![Screenshot 2023-08-22 at 17.05.36](https://p.ipic.vip/thhlam.png)

## 0x01

安装这些插件：

![Screenshot 2023-08-22 at 17.09.39](https://p.ipic.vip/67ywqu.png)

vim 看个人喜好，喜欢就用:

![Screenshot 2023-08-22 at 17.29.49](https://p.ipic.vip/h1e4iu.png)

## 0x02

如果他警告你，就需要修改 `clangd` 的设置；

![Screenshot 2023-08-22 at 17.11.05](https://p.ipic.vip/kb55bz.png)



设置：

![Screenshot 2023-08-22 at 17.12.21](https://p.ipic.vip/0z02zm.png)



搜索 `Fallback Flags`:

![Screenshot 2023-08-22 at 17.12.49](https://p.ipic.vip/uo14y1.png)

添加一个自己喜欢的标准：

![Screenshot 2023-08-22 at 17.13.45](https://p.ipic.vip/j1izut.png)

重启一下 VSCode，警告消失了；

![Screenshot 2023-08-22 at 17.15.20](https://p.ipic.vip/rlz6pz.png)



## 0x03

按下 `Ctrl + Option + N` 来运行代码：

![Screenshot 2023-08-22 at 17.16.54](/Users/kion/Desktop/Screenshot 2023-08-22 at 17.16.54.png)

Code Runner 默认不会使用 `-std=c++__`的参数，可以自己添加这一项来不让他警告：

设置：

![Screenshot 2023-08-22 at 17.20.29](https://p.ipic.vip/frit6u.png)

随便点一个 `Edit in settings.json`，或者按 `Shift + Command + P` 搜索 `settings.json`;

![Screenshot 2023-08-22 at 17.23.17](https://p.ipic.vip/tledlj.png)

搜索找到 `cpp` ：

![Screenshot 2023-08-22 at 17.26.42](https://p.ipic.vip/8g3tc5.png)

在 `g++` 后面增加 `-std=c++14` 或者自己想要的版本：

![Screenshot 2023-08-22 at 17.27.54](https://p.ipic.vip/60g0uh.png)

保存并退出；

![Screenshot 2023-08-22 at 17.28.35](https://p.ipic.vip/keddqu.png)

他就不警告我了.



## 0xff

最后附一个奇奇怪怪的图：

![Screenshot 2023-08-20 at 02.31.10](https://p.ipic.vip/f59mh5.png)