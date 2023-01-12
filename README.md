<p align="center">
  <a href="https://v2.nonebot.dev/"><img src="https://zsy.juncikeji.xyz/i/img/mxy.png" width="150" height="150" alt="API管理系统"></a>
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
<a style="margin-inline:5px" target="_blank" href="https://github.com/mengxinyuan638/mxy-api-system">
	<img src="https://img.shields.io/badge/github-萌新源API管理系统-FDE6E0?style=flat&logo=github" title="萌新源API管理系统">
</a>
<a style="margin-inline:5px" target="_blank" href="https://gitee.com/meng-xinyuan-mxy/mxy-api">
	<img src="https://img.shields.io/badge/gitee-萌新源API管理系统-FDE6E0?style=flat&logo=gitee" title="萌新源API管理系统">
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

![](https://zsy.juncikeji.xyz/i/img/ysgg.png)

## 命令2：#原神公告+公告序号

## 返回：

![](https://zsy.juncikeji.xyz/i/img/ysgg0.png)

# 依赖

本插件依赖request库以及json库



# 安装

```bash
pip install nonebot_plugin_yuanshen_notice
```



# 配置

在`bot.py`中添加
```python
nonebot.load_plugin("nonebot_plugin_yuanshen_notice")
```