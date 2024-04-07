# dynatalk-MicroBlocks

本仓库是 [Dynatalk](https://github.com/wwj718/Dynatalk) 的 MicroBlocks 客户端。

> Dynatalk 致力于对象之间的交流, 尤其关心不同语言/环境之间的互操作。 -- [Dynatalk](https://github.com/wwj718/Dynatalk)

## 开始

1. 运行一个 MQTT broker
   - 下载并运行 DynatalkHub
     - [MacOS](https://scratch3-files.just4fun.site/DynatalkHub-0.2.0-mac.zip)
     - [Windows](https://scratch3-files.just4fun.site/DynatalkHub-0.2.0-win.zip)
     - [Linux](https://github.com/wwj718/Dynatalk/tree/main/mqtt#FAQ)
2. [打开例子](https://microblocksfun.cn/run/microblocks.html?#project=https://wwj718.github.io/post/img/dynatalk-demo-20240331.ubp), 开始编程。

<!--
在 [MicroBlocks](https://microblocksfun.cn/run) 中打开 `dynatalk-demo.ubp`
-->

## 已知问题

- M5Stack Fire 会频繁断开 MQTT 连接, 其他的 ESP32 板子暂未发现存在这个问题

## FAQ


<!--
### 为何有时候板子连接不上本地的 MQTT 服务器?

现象: 本地的 dynatalk 客户端(Python, Snap!)可以连上, 但局域网中的 esp32 无法连接, 或者需要多次连接。

一种解决方案是, 确保本地计算机和 esp32 都连接在 2.4G 的 wifi 热点上(避免电脑连接在 5G 热点上)
-->