<!-- galshelf-releases: curated README (zh-CN). -->
<a id="chinese"></a>

<div align="center">

<img src="assets/icon.png" width="148" alt="栞 GalShelf 图标">

# 栞 · GalShelf

**为每一个故事，留一枚书签。**

写给 Galgame / 视觉小说玩家的 Windows 书架：<br>
把游戏整理好，在游戏里截图、识别台词，把玩过的故事记下来，再做成一张分享卡。

<a href="https://github.com/Harihi86/galshelf-releases/releases/latest"><b>⬇ 下载最新版</b></a>
　·　<a href="#zh-install"><b>安装</b></a>
　·　<a href="#zh-updates"><b>更新与校验</b></a>
　·　<a href="https://galshelf.com"><b>官方网站</b></a>
　·　<a href="README.md#english"><b>🌐 English</b></a>

<sub>当前版本 0.2.6　·　Windows 10 / 11（64 位）　·　无需账号，数据保存在本机　·　简体中文 / English</sub><br>
<sub>✦ 页首是新设计的图标，之后的版本会在客户端里换上它；0.2.6 的界面仍显示原来的标志。</sub>

</div>

<br>

<a href="assets/screenshots/zh-CN/library.jpg"><img src="assets/screenshots/zh-CN/library.jpg" alt="游戏库：十四部作品的封面墙，带状态筛选和每部作品的游玩时长"></a>

> [!NOTE]
> **关于截图**　全部画面都来自已发布的 **GalShelf 0.2.6** 客户端，使用一份独立的演示数据：作品名称与封面来自公开资料库，状态、评分、游玩时长、票根、短评和阅读笔记都是为演示编写的，不属于任何真实用户。
>
> 截图时「插画程度」设为「不显示」，所以没有小助手立绘，左下角的小助手入口照常可用。游戏内的画面是用 GalShelf 自带插画制作的演示窗口，不是任何商业游戏的画面；游戏菜单一图由演示窗口和游戏菜单窗口两张真实截图，按屏幕上的实际位置拼合在纯色背景上。

---

## 📚 书架：把硬盘里的游戏收拾好

选一个游戏文件夹，栞会把每个子文件夹和 VNDB 等资料源比对（只发送作品名称），标出**高置信**、**需核对**和**未识别**，列出候选作品与游戏主程序——你确认之前，什么都不会写入书架。也可以导入本机 Steam 里的游戏，或者手动添加。

收好之后，按状态筛选，按会社、收藏夹或 Steam 系列分组，标题、原名、会社都能即时搜到。打开「整理」，一次选中几部，批量修改状态、加入收藏夹或移入回收站。

<table>
<tr>
<td width="50%"><a href="assets/screenshots/zh-CN/import.jpg"><img src="assets/screenshots/zh-CN/import.jpg" alt="添加作品：本机检查，扫描结果按置信度列出候选作品"></a></td>
<td width="50%"><a href="assets/screenshots/zh-CN/organize.jpg"><img src="assets/screenshots/zh-CN/organize.jpg" alt="整理模式：选中三部作品，准备加入新收藏夹"></a></td>
</tr>
<tr>
<td><sub><b>导入前先核对</b>　扫描出五个文件夹：一个高置信，其余四个等你确认作品和主程序。</sub></td>
<td><sub><b>整理模式</b>　选中三部作品，准备一起放进新收藏夹「周末想玩」。</sub></td>
</tr>
</table>

## 🎮 游戏中：不必切出游戏

从栞启动游戏就会自动计时。游戏运行时按 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>G</kbd>（可在设置中更改），游戏菜单会出现在游戏窗口旁边：截图和截图历史、窗口透明度与置顶、Magpie 画面缩放、手柄映射键盘，以及计时方式，都在这里。

截图会冻结当前画面，并直接在游戏窗口上打开编辑器：裁剪、打码、超分、擦除与抠图，还能用 Windows 自带的 OCR 在本机识别台词。识别可能出错，校对后点「确认台词」，这张截图和这句台词就能一起交给分享卡。

<a href="assets/screenshots/zh-CN/game-menu.jpg"><img src="assets/screenshots/zh-CN/game-menu.jpg" alt="正在计时的演示场景窗口旁边打开了游戏菜单，显示游戏窗口、画面缩放和手柄映射设置"></a>

<sub><b>游戏菜单</b>　计时中的演示场景旁边，就是 0.2.6 的游戏菜单：窗口透明度与置顶、Magpie 画面缩放、手柄映射键盘；往上翻是截图与截图历史。</sub>

<table>
<tr>
<td width="50%"><a href="assets/screenshots/zh-CN/screenshot-editor.jpg"><img src="assets/screenshots/zh-CN/screenshot-editor.jpg" alt="截图编辑器：台词面板显示已校对的台词，下方是编辑工具栏"></a></td>
<td width="50%"><a href="assets/screenshots/zh-CN/share-card-dialogue.jpg"><img src="assets/screenshots/zh-CN/share-card-dialogue.jpg" alt="分享卡编辑器：截图和台词排进横版对白卡"></a></td>
</tr>
<tr>
<td><sub><b>截图编辑器</b>　识别出的台词校对后标为「已校对」，工具栏里是裁剪、打码、超分等工具。</sub></td>
<td><sub><b>交给分享卡</b>　截图与台词自动排进横版对白卡，角色名和对白都能再改。</sub></td>
</tr>
</table>

<sub>在 0.2.6 中，游戏菜单和截图编辑器只有中文界面；分享卡上预设的文字（状态、评分评语、单位、寄语等）和图层名称也只有中文，作品名、短评和台词按你填写的显示。</sub>

## 🍡 记录：玩过的故事，都有迹可循

每部作品都有「我的记录」：游玩状态、已通关 / 全结局、0–10 分的团子评分、短评、路线与进度、私人手记。每次游玩留下一张票根，时长精确到秒；在别的电脑上玩了，也可以手动补记一次，票根上会注明「补记」。

「阅读与路线」把正在读和正在重温的作品放在一起：一句话进度、下一步打算，以及最近一次从哪个入口启动。隔几天再回来，也知道从哪里接着读。

<table>
<tr>
<td width="50%"><a href="assets/screenshots/zh-CN/record.jpg"><img src="assets/screenshots/zh-CN/record.jpg" alt="作品的我的记录：全结局、团子评分 9.5 和五张游玩票根"></a></td>
<td width="50%"><a href="assets/screenshots/zh-CN/reading.jpg"><img src="assets/screenshots/zh-CN/reading.jpg" alt="阅读与路线：继续阅读的作品和各自的一句话进度"></a></td>
</tr>
<tr>
<td><sub><b>我的记录</b>　《白色相簿2》：全结局、9.5 分，五张票根合计 17 小时 20 分，其中一张是补记。</sub></td>
<td><sub><b>阅读与路线</b>　三部在读、一部重温中，各自写着停在哪里、下一步做什么。</sub></td>
</tr>
</table>

## 🎴 分享卡：把喜欢的故事拿给别人看

分享卡直接读取你的记录——状态、团子评分、游玩时长、一句话短评——排进玻璃、侧栏、海报、票根、手帐等版式。卡上的每个元素都是图层，可以拖动、改字、换字体、隐藏、调整层次，最后导出 1400×1750 或 1600×1000 的 PNG。

<a href="assets/screenshots/zh-CN/share-card-ticket.jpg"><img src="assets/screenshots/zh-CN/share-card-ticket.jpg" alt="分享卡编辑器：票根版式的白色相簿2分享卡，右侧是图层列表和一段手写寄语的属性"></a>

<sub><b>票根版式</b>　卡上的全结局、9.5 分、17.3 小时和短评都来自同一份记录；右侧面板正在编辑左上角的手写寄语，模板自带的「角色签名」图层已隐藏。</sub>

## 📺 大屏模式

专为电视和手柄设计：用方向键或摇杆移动焦点，选中的作品可以直接查看详情或修改状态，上次玩的作品按一下就能继续。

<p align="center"><a href="assets/screenshots/zh-CN/big-picture.jpg"><img src="assets/screenshots/zh-CN/big-picture.jpg" alt="大屏模式首页：继续游玩与最近游玩的作品，焦点停在其中一部上" width="720"></a></p>

---

## ✦ 更多功能

<details>
<summary><b>☁ 云存档与书架同步</b></summary>

<br>

云存档和书架同步是两件事：云存档备份的是**游戏存档文件**；书架同步只同步**作品记录**（状态、评分、通关与全结局、标签、短评、私人手记、每次游玩的日期与时长等）。

**云存档**
- 只对已关联 VNDB 作品编号的游戏生效，每部作品可以单独开关。在「设置 › 账号与同步」中开启一次后，确认过存档位置的作品会在启动前同步、退出后备份；可信且兼容的缺失存档会自动恢复。
- 作品页的云存档卡片有三个操作：「立即同步」按安全方向对比并同步；「上传备份」只保存这台电脑的进度；「下载 / 恢复」只恢复明确的云端版本，替换本地有改动的存档前会先确认，并保留本地安全快照。
- 两台电脑分别离线游玩产生分歧时，两份进度都会保留，由你选择继续哪一份；每部作品默认保留 10 个版本。
- **存放位置**：公开版可以选择一个同步文件夹（例如由网盘客户端同步的本地文件夹）。直接连接 Google Drive 与 OneDrive 的功能已经实现，但连接所需的应用注册没有随公开版提供，目前还不能直接连接这两项服务。
- 可选端到端加密；口令遗失后无法找回。不加密时，同步文件夹的安全程度取决于你的网盘与磁盘。开启云存档时，对话框里还有三个联网选项：在线查询指纹、贡献指纹、在仅自己可见的网站页面显示备份状态，都可以取消勾选。

**书架同步**
- 需要 [galshelf.com](https://galshelf.com) 账号，在「设置 › 账号与同步」中开启。网页书架与客户端按字段合并，离线修改会排队，冲突逐项选择。
- 同步不是备份：删除也会同步。游戏程序、文件夹、启动选项与存档不会上传；「阅读与路线」里的一句话进度和下一步只保存在本机。

</details>

<details>
<summary><b>🛡 GalShelf Guard 与作品识别</b></summary>

<br>

- **GalShelf Guard** 是可选的独立程序，目前是 0.1.0 预发布测试版：单独的安装程序，未做代码签名，安装时 Windows 可能请求管理员权限。可以在「设置 › 隐私与安全」中检查、下载、校验并安装。
- Guard 为每部已安装的作品记录可信文件清单，发现被修改、缺失或新增的程序文件，用自带规则分析；可疑文件可以移入可恢复的隔离区，也可以从已核验的本地副本修复。Microsoft Defender 只是可选的补充。
- **文件变化不等于中毒**：只有扫描器给出的结果才会被标记为威胁。不安装 Guard 时，客户端自己也会记录已确认的启动文件，在文件变化时提醒。
- **作品识别**以 VNDB 作品编号为准，按文件 SHA-256 与维护者签名的指纹数据集比对。身份匹配只说明文件属于哪部作品，不代表文件安全。首个维护者数据集尚未发布，所以 0.2.6 中还不会有来自数据集的识别结果。联网查询与贡献都是可选的，贡献与账号关联，并非匿名。

</details>

<details>
<summary><b>🛠 启动与游戏工具</b></summary>

<br>

- 作品页的「游戏工具」可以设置启动文件、转区启动（Locale Emulator，仅适用于 32 位程序）、Magpie 缩放与窗口设置；计时方式可选前台计时、进程计时或「前台 + 有操作」。
- 游戏菜单只对栞正在计时的游戏打开。截图保存在本机，编辑结果另存为新文件，不会改动原始截图。
- 识别台词使用 Windows 自带的 OCR，在本机完成，需要系统装有对应语言（中文、日文或英文）的 OCR 组件。

</details>

<details>
<summary><b>🎨 外观、发现与小助手</b></summary>

<br>

- 背景可以是图片、GIF 或 MP4 视频，可调整焦点、适配方式、透明度与模糊。作品页的「OP 与影像」可以播放或下载 OP、预告片，视频默认静音，游戏运行时自动暂停。
- 「发现」可以跨多个资料源搜索作品；发售月历区分 VNDB 已确认的日期与仅来自 NextMoe 的消息；相似作品推荐按系列、制作人员、开发商与题材排列。角色与生日需要在「设置 › 账号与同步」中关联 galbd；以图识图只在你点击开始后发送所选图片。
- 左下角的小助手可以更换形象、调整立绘大小，也可以在设置中完全关闭。

</details>

---

<a id="zh-install"></a>

## ⬇ 安装

**需要**：Windows 10 / 11（64 位），以及 Microsoft Edge WebView2 Runtime（Windows 11 通常已自带）。不需要 Python、Node.js 或管理员权限。

1. 在 [Releases](https://github.com/Harihi86/galshelf-releases/releases/latest) 下载 `GalShelf-Windows-<版本>.zip`（0.2.6：[GalShelf-Windows-0.2.6.zip](https://github.com/Harihi86/galshelf-releases/releases/download/v0.2.6/GalShelf-Windows-0.2.6.zip)，约 350 MB）。
2. 把**整个** ZIP 解压到一个新文件夹，让 `components` 文件夹（aria2、Magpie、Locale Emulator、Real-ESRGAN）和 `GalShelf.exe` 放在一起。
3. 运行 `GalShelf.exe`，首次启动有中英双语的引导。

> [!TIP]
> 栞没有安装程序，程序也未做代码签名，Windows SmartScreen 可能会请你确认一次。
>
> 书架、设置和记录保存在 `%LOCALAPPDATA%\GalShelf`，不在程序文件夹里——升级时可以把新版本解压到新文件夹，确认没问题再删掉旧的，两边读取的是同一份数据。

<a id="zh-updates"></a>

## 🔏 更新与校验

- 客户端在应用内检查更新：它读取本仓库最新 Release 中的 `latest.json`（内含 Ed25519 签名的更新清单）。只有清单签名、安装包大小和 SHA-256 **全部一致**时才会安装更新；游戏运行时不会安装更新。
- `releases/v<版本>/` 保存每个已发布版本的清单、校验值和更新说明；`stable/latest.json` 是当前稳定版清单的副本，`stable/latest.json.sig` 是它的独立签名，供手动核对。
- 更新清单使用以下公钥签名（Ed25519，base64）：

```
galshelf-update-2026-09: II1VyOQWGZphhHvY0bcjvqpuYkb1UjBmzb75h+VfuQc=
```

想自己核对下载的安装包，可以在 PowerShell 中运行，并与同一 Release 里的 `SHA256SUMS.txt` 对照：

```powershell
Get-FileHash .\GalShelf-Windows-<版本>.zip -Algorithm SHA256
```

## 📜 版本记录

每个版本的更新说明都在 [Releases](https://github.com/Harihi86/galshelf-releases/releases) 页面，也保存在 [`releases/`](releases/) 目录中。使用说明与常见问题见 [galshelf.com/docs](https://galshelf.com/docs)。

## 💐 致谢与许可

- 作品资料与封面来自 [VNDB](https://vndb.org) 等公开资料库。
- 安装包随附的第三方组件各自遵循其许可证：[aria2](https://github.com/aria2/aria2)（GPL-2.0）、[Magpie](https://github.com/Blinue/Magpie)（GPL-3.0）、[Locale Emulator](https://github.com/xupefei/Locale-Emulator)（LGPL-3.0）、[Real-ESRGAN-ncnn-vulkan](https://github.com/xinntao/Real-ESRGAN-ncnn-vulkan)（MIT）。

<sub>截图中出现的游戏名称与封面，版权归各自的权利人所有，仅用于展示软件界面。</sub>
