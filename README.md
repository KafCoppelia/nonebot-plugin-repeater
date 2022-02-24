<div align="center">

# Repeater

<!-- prettier-ignore-start -->
<!-- markdownlint-disable-next-line MD036 -->
_📻 复读机 📻_
<!-- prettier-ignore-end -->

</div>

<p align="center">
  
  <a href="https://github.com/KafCoppelia/nonebot-plugin-repeater2/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-informational">
  </a>
  
  <a href="https://github.com/nonebot/nonebot2">
    <img src="https://img.shields.io/badge/nonebot2-2.0.0beta.2-green">
  </a>
  
  <a href="">
    <img src="https://img.shields.io/badge/release-v0.1.0-orange">
  </a>
  
</p>

</p>

## 版本

v0.1.0

⚠ 适配nonebot2-2.0.0beta.2；

## 安装

1. 通过`pip`或`nb`安装，版本请指定`0.1.0`；

2. 在原版基础上修改了配置，**默认所有群支持复读**，通过`REPEATER_OFF_GROUP`设置关闭的群：

    ```python
    REPEATER_OFF_GROUP=["123456789", "987654321"]
    REPEATER_MINLEN=1 # 触发复读的文本消息最小长度（表情和图片无此限制）
    ```

## 功能

当群里开始+1时，机器人也会参与其中。

包括普通消息，QQ表情，还有图片（表情包）。

## Fork from

[ninthseason-nonebot-plugin-repeater](https://github.com/ninthseason/nonebot-plugin-repeater)