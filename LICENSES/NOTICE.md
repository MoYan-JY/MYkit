# 第三方组件与许可证

杂货铺 MYkit 使用了以下第三方组件。本目录存放各许可证的完整条款副本。

## 组件清单

| 组件 | 用途 | 许可证 | 条款全文 |
|---|---|---|---|
| **jump3r** | LAME MP3 编码器的 Java 移植，用于视频转音频 | GNU LGPL 2.1 | [LGPL-2.1.txt](LGPL-2.1.txt) |
| **ML Kit** | Google 文字识别，用于 PDF 转 Word、图片取字 | Google APIs 服务条款 | [见下文](#google-apis-服务条款) |
| **Google Play services** | ML Kit 的运行依赖 | Google APIs 服务条款 | [见下文](#google-apis-服务条款) |
| **AndroidX** | FileProvider，用于应用内更新的安装包传递 | Apache License 2.0 | [Apache-2.0.txt](Apache-2.0.txt) |

## 关于 jump3r / LAME 的 LGPL 义务

jump3r 遵循 GNU Lesser General Public License。按 LGPL 的要求，本应用履行以下义务：

1. **提供源码获取途径** —— 上游项目：<https://sourceforge.net/projects/jump3r/>（LAME：<https://lame.sourceforge.io/>）
2. **提供许可证副本** —— 见本目录 [LGPL-2.1.txt](LGPL-2.1.txt)，应用内「设置 → 开源许可 → 查看 GNU LGPL 2.1 完整条款」也可查看全文
3. **不限制使用者对 LGPL 组件的权利** —— 使用者可为自身需要修改该组件，并可为调试目的对其进行逆向分析

## 关于 Google APIs 服务条款

ML Kit 与 Google Play services 遵循 Google APIs 服务条款：

- 条款原文：<https://developers.google.com/terms>
- ML Kit 附加条款：<https://developers.google.com/ml-kit/terms>

使用限制：不得将该服务用于武器、监控等受限领域。本应用为个人效率工具，不涉及此类用途。

## 本应用自身代码

本应用（杂货铺 MYkit）自身代码版权归作者所有，**未公开源代码**，未授予以任何其他方式使用、修改或分发的许可。

本目录仅用于履行第三方组件的许可证义务，不构成对本应用自身代码的授权。
