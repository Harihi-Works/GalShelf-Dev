<!-- galshelf-releases: shared project overview (zh-CN). -->
<a id="chinese"></a>

# 栞 · GalShelf

**为每一个故事，留一枚书签。**

从硬盘里的旧收藏，到正在阅读的新故事：整理游戏、关联作品、记录游玩，并保护游戏文件与存档。**GalShelf 仍是面向玩家的主应用**，Galdex、Galguard 和 Galdrive 分别承担数据维护、安全检查与存档同步，不要求玩家安装全部组件。

[GalShelf 完整介绍](GALSHELF.zh-CN.md#chinese) · [Galdex](GALDEX.md#chinese) · [Galguard](GALGUARD.md#chinese) · [Galdrive](GALDRIVE.md#chinese) · [English](README.md#english)

[下载 GalShelf](https://github.com/Harihi-Works/GalShelf-Dev/releases/latest) · [官方网站](https://galshelf.com) · [安装](#zh-install) · [更新与校验](#zh-updates)

> [!NOTE]
> **项目状态 · 2026-10-01**：本仓库当前已发布版本为 **[GalShelf 0.2.7](https://github.com/Harihi-Works/GalShelf-Dev/releases/tag/v0.2.7)**。Galdex 与 Galdrive 的核心功能已基本完成，现统一介绍；开发完成度与公开发包、正式数据发布、集成验收分别管理。Galdex 仍是内部维护工具，Galdrive 的独立下载暂未开放。本次只更新说明，不改变安装包、更新清单或下载状态。

## 功能分页

| 模块 | 主要作用 | 详细介绍 |
| --- | --- | --- |
| **GalShelf** | 本地游戏导入、作品关联、书架检索、游玩记录、游戏内工具与分享卡 | [游戏库与游玩体验](GALSHELF.zh-CN.md#chinese) |
| **Galdex** | 作品指纹与存档规则的采集、核验、审核和签名发布；面向维护者 | [指纹与规则维护](GALDEX.md#chinese) |
| **Galguard / GalShelf Guard** | 文件完整性检查、异常变化提示、可恢复隔离与经核验的本地修复 | [安全与完整性](GALGUARD.md#chinese) |
| **Galdrive** | 存档备份、版本管理、多设备同步、冲突处理与恢复保护 | [存档备份与同步](GALDRIVE.md#chinese) |

配套模块页面均为纯文字介绍。GalShelf 原有的完整说明、演示截图、安装指引与许可信息保留在 [GalShelf 详情页](GALSHELF.zh-CN.md#chinese)。所有页面都在这个仓库内。

**详情页版本说明**：保留的 GalShelf 详情页与截图对应 **0.2.6**，页内版本限定的操作说明、下载示例与限制按该版本阅读，不代表当前版本状态。最新改动及安装包请查看 [0.2.7 发布说明](https://github.com/Harihi-Works/GalShelf-Dev/releases/tag/v0.2.7)。

## 让已有收藏也能接入

游戏不一定来自 App 下载。文件夹可能改过名字，同一作品也可能有不同发行、汉化或补丁版本。我们关注的是把这些已有文件与正确的作品条目联系起来，而不是让玩家重新下载或反复整理。

GalShelf 负责扫描、候选核对和书架管理；Galdex 维护可用于识别的文件指纹和存档规则；Galguard 独立处理安全与完整性；Galdrive 专注存档的备份和接续。

当前作品身份沿用 **VNDB 作品编号**，不另外建立一套公共作品编号。指纹识别范围取决于实际审核并发布的数据，不宣称覆盖全部作品或全部发行版本。**身份识别不等于安全证明，存档位置提示也不等于允许自动覆盖文件。**

<a id="zh-install"></a>

## 安装与使用

GalShelf 当前支持 **Windows 10 / 11（64 位）**，需要 Microsoft Edge WebView2 Runtime；本地使用无需账号，同步功能可选。

从 [Releases](https://github.com/Harihi-Works/GalShelf-Dev/releases/latest) 下载，完整解压后运行 `GalShelf.exe`，保留旁边的 `components` 文件夹。具体步骤与现有版本限制见 [完整安装说明](GALSHELF.zh-CN.md#zh-install)。

Galdex 不面向普通玩家提供下载。Galdrive 的介绍页不是安装包入口，独立发包另行公布。GalShelf 已有的云存档功能仍保留，不以安装独立 Galdrive 为前提。

<a id="zh-updates"></a>

## 更新与校验

现有发布继续使用本仓库的 Releases 与签名更新清单。安装包、签名、校验值和版本记录没有因说明分页而改变。参见 [更新与校验说明](GALSHELF.zh-CN.md#zh-updates)。

<a id="zh-open-source"></a>

## 开源与许可

GalShelf 仍处于灰度测试与快速迭代阶段，项目自身源码暂不公开，稳定版后的开源安排将在本仓库公布。公开功能介绍不等于开放内部工具或维护者权限。第三方组件继续遵循各自许可证，详见 [原有开源与许可说明](GALSHELF.zh-CN.md#zh-open-source)。
