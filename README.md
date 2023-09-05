<p align="center">
  <a href="https://v2.nonebot.dev/"><img src="https://camo.githubusercontent.com/0ef71e86056da694c540790aa4a4e314396884d6c4fdb95362a7538b27a1b034/68747470733a2f2f76322e6e6f6e65626f742e6465762f6c6f676f2e706e67" width="200" height="200" alt="nonebot" data-canonical-src="https://v2.nonebot.dev/logo.png" style="max-width: 100%;"></a>
</p>
<div align="center">
    <h1 align="center">✨原神公告</h1>
</div>
<p align="center">
<!-- 插件名称 -->
<img src="https://img.shields.io/badge/插件名称-原神公告-blue" alt="python">
<!-- Python版本 -->
<img src="https://img.shields.io/badge/-Python3-white?style=flat-square&logo=Python">
<!-- 插件名称 -->
<img src="https://img.shields.io/badge/Python-3.8+-blue" alt="python">
<a style="margin-inline:5px" target="_blank" href="http://blog.juncikeji.xyz/">
	<img src="https://img.shields.io/badge/Blog-个人博客-FDE6E0?style=flat&logo=Blogger" title="萌新源的小窝">
</a>
<!-- 萌新源API -->
<a style="margin-inline:5px" target="_blank" href="https://api.juncikeji.xyz/">
	<img src="https://img.shields.io/badge/API-萌新源-blue?style=flat&logo=PHP" title="萌新源API">
</a>
<!-- CSDN博客 -->
<a style="margin-inline:5px" target="_blank" href="https://blog.csdn.net/m0_66648798">
	<img src="https://img.shields.io/badge/CSDN-博客-c32136?style=flat&logo=C" title="CSDN博客主页">
</a>
<!-- QQ群 -->
<a style="margin-inline:5px" target="_blank" href="https://jq.qq.com/?_wv=1027&k=5Ot4AUXh">
	<img src="https://img.shields.io/badge/QQ群-934541995-0cedbe?style=flat&logo=Tencent QQ" title="QQ">
</a>
<img src="https://img.shields.io/badge/license-MIT-blue" alt="MIT">
</p>




# 使用教程

## 命令1：原神公告

## 返回：官网最新20条公告标题列表

![](https://zsy.mxycn.cn/i/img/ysgg.png)

## 命令2：#原神公告+公告序号

## 返回：

![](https://zsy.mxycn.cn/i/img/ysgg0.png)

# 依赖

本插件依赖httpx库以及json库



# 安装

```bash
pip install nonebot_plugin_yuanshen_notice
```



# 配置

在`bot.py`中添加
```python
nonebot.load_plugin("nonebot_plugin_yuanshen_notice")
```