## 以下是原版PCL CE的说明文件（同样适用）所谓的Plain-Craft-Launcher-Clock是二次修改版
**简体中文** | [English](README-EN.md) | [繁體中文](README-ZH_TW.md)

<div align="center">

<img src="Plain Craft Launcher 2/Images/icon.ico" alt="Logo" width="80" height="80">

# PCL Community Edition

[![Stars](https://img.shields.io/github/stars/PCL-Community/PCL-CE?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZlcnNpb249IjEiIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiI+PHBhdGggZD0iTTggLjI1YS43NS43NSAwIDAgMSAuNjczLjQxOGwxLjg4MiAzLjgxNSA0LjIxLjYxMmEuNzUuNzUgMCAwIDEgLjQxNiAxLjI3OWwtMy4wNDYgMi45Ny43MTkgNC4xOTJhLjc1MS43NTEgMCAwIDEtMS4wODguNzkxTDggMTIuMzQ3bC0zLjc2NiAxLjk4YS43NS43NSAwIDAgMS0xLjA4OC0uNzlsLjcyLTQuMTk0TC44MTggNi4zNzRhLjc1Ljc1IDAgMCAxIC40MTYtMS4yOGw0LjIxLS42MTFMNy4zMjcuNjY4QS43NS43NSAwIDAgMSA4IC4yNVoiIGZpbGw9IiNlYWM1NGYiLz48L3N2Zz4=&logoSize=auto&label=stars&labelColor=444444&color=eac54f)](https://github.com/PCL-Community/PCL-CE/)
![GitHub Release](https://img.shields.io/github/v/release/PCL-Community/PCL-CE?label=release&logo=github&style=for-the-badge)
![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/PCL-Community/PCL-CE/build-test.yml?style=for-the-badge)

[![Issues](https://img.shields.io/github/issues/PCL-Community/PCL-CE?style=for-the-badge&label=issues&labelColor=444444&color=1F883D&logo=github)](https://github.com/PCL-Community/PCL-CE/issues)
[![Pull requests](https://img.shields.io/github/issues-pr/PCL-Community/PCL-CE?style=for-the-badge&label=pull%20requests&labelColor=444444&color=1F883D&logo=github)](https://github.com/PCL-Community/PCL-CE/pulls)
![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/PCL-Community/PCL-CE/total?style=for-the-badge)
[![哔哩哔哩](https://img.shields.io/badge/动态-bilibili-00A4DB?style=for-the-badge&labelColor=444444&logo=bilibili)](https://space.bilibili.com/3546847192811755/dynamic) <br />

<a href="https://trendshift.io/repositories/21800?utm_source=trendshift-badge&amp;utm_medium=badge&amp;utm_campaign=badge-trendshift-21800" target="_blank" rel="noopener noreferrer"><img src="https://trendshift.io/api/badge/trendshift/repositories/21800/weekly?language=C%23" alt="PCL-Community%2FPCL-CE | Trendshift" width="250" height="55"/></a>
<a href="https://trendshift.io/repositories/21800" target="_blank" rel="noopener noreferrer"><img src="https://trendshift.io/api/badge/repositories/21800" alt="PCL-Community%2FPCL-CE | Trendshift" style="width: 250px; height: 55px;" width="250" height="55"/></a>

[社区版下载](https://github.com/PCL-Community/PCL-CE/releases/latest) |
[上游存储库](https://github.com/Meloong-Git/PCL)

[提交问题](https://github.com/PCL-Community/PCL-CE/issues/new/choose) |
[贡献指南](https://github.com/PCL-Community/PCL-CE/wiki/开发指南)

</div>

PCL CE 是基于 PCL 开源代码二次开发的社区版本，包括了主线暂未制作的功能和改进！

社区版的版本号与主线并非严格对应关系，也请不要向官方仓库反馈社区版问题。

欢迎大家来用用看！



## 💻 支持平台

| 操作系统 | 支持情况 | 环境要求 |
|---|---|---|
| Windows 10 1809 (17763) 或更高 | ✅ 完整支持 | [.NET 10 Desktop Runtime](https://get.dot.net/10) |
| Windows 8 - Windows 10 1809 (17763) | ⚠️ 理论能跑，酌情提供社区支持 | [.NET 10 Desktop Runtime](https://get.dot.net/10) |
| Windows 7 或更低版本 | ❌ 不支持 | / |
| macOS / Linux / 其他操作系统 | ⚠️ 仅跨平台开发支持（交叉编译） | [.NET 10 SDK](https://get.dot.net/10) |

**✅ 完整支持**：尽可能提供一切相关支持，但必须确保启动器为最新版本。

**⚠️ 理论能跑，酌情提供社区支持**：PCL CE 应该可以在这些平台上运行，但不保证功能完全可用。你可能需要升级到完整支持的系统版本以获得进一步社区技术支持。

**❌ 不支持**：PCL CE 在这些平台的可用性较低，甚至压根打不开。请升级操作系统以使用 PCL CE。

**⚠️ 仅跨平台开发支持（交叉编译）**：PCL CE 的源代码可以在 macOS 与 Linux 平台编译，但无法直接运行。作为开发者，你可以在这些平台上进行开发，然后将编译产物转移到 Windows 系统测试。

**注**：    
社区仅对最新版本的启动器提供支持。    
取决于部分问题的特殊性（如系统不完整），有时你仍然必须升级操作系统以继续获得支持。    
PCL CE 始终建议使用最新版本的操作系统以获得最佳体验。    
你仍然可以尝试在不受支持的系统上使用 PCL CE，但可能会遇到很多额外问题。

## 🔒 许可证

- `Plain Craft Launcher 2/` 使用 [自定义许可证](https://github.com/PCL-Community/PCL-CE/blob/dev/Plain%20Craft%20Launcher%202/LICENCE)
- `其余所有目录` 使用 [Apache License 2.0](https://github.com/PCL-Community/PCL-CE/blob/dev/LICENSE)


## 正式说明页
 **项目名称**：Plain Craft Launcher Clock
- **原作者**：龙腾猫跃，https://afdian.com/a/LTCat
- **开源义务**：本仓库代码完全公开，任何修改、分发必须同样遵守上述许可证条款。
- **非官方性**：不得以任何方式暗示原作者为您背书或认可此修改版。
- ## 免责声明

代码可能存在错误，也不保证运行稳定。使用风险自负
温馨提示：请不要在别的网站下载PCL或PCL CE！！！有盗号风险。
PCL下载地址：https://afdian.com/a/LTCat
PCL CE下载地址：https://pclce-web.demo.fis.ink/
如果你也喜欢Minecraft，不妨购买正版和伙伴们一起游玩吧
## 不是原版的PCL CE/PCL是修改版！
## 它只是为原来的PCL CE 添加了jar服务器启动的功能
This is a project to add brand-new features to the Plain Craft Launcher (PCL CE)! It’s designed to launch servers or any executable .jar files, and it integrates server startup directly into PCL.
