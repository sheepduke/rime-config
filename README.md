# 简介

本项目包含对 Rime 输入法五笔的配置，包括单字码表、自动上屏等。

# 如何使用

1. 将配置文件置于对应的路径下，在 Linux 发行版、iBus 框架下为
   `$HOME/.config/ibus/rime`。
2. 修改 `wubi86.custom.yaml` 文件以开启/关闭单字码表、自动上屏等功能。
3. 重新部署 Rime。如果没有开启系统通知栏，一个可行的办法是删除 `build/` 文件
   夹并运行 `ibus-daemon -rdx`。
