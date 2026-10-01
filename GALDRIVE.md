<a id="chinese"></a>

# Galdrive · 存档备份与多设备同步

[返回 GalShelf 首页](README.md#chinese) · [Galdex](GALDEX.md#chinese) · [Galguard](GALGUARD.md#chinese) · [English](#english)

**换一台电脑，也能找回自己选择继续的那份进度。**

Galdrive 是专注游戏存档的独立工具，围绕备份、版本、同步、冲突和恢复组织操作。它不是整部游戏的云盘，也不替代 GalShelf 的作品资料、书架管理和游玩记录。

> **状态**：核心功能已基本完成，独立下载暂未开放。真实云账号、发布环境和跨应用联动的可用范围以对应版本验收与发布说明为准。GalShelf 0.2.6 原有云存档仍保留，不需要先安装独立 Galdrive。

## 按作品组织存档

备份不应只是一堆难以辨认的文件夹。存档流程围绕作品身份、存档位置和备份版本展开，便于知道保存的是哪部作品、哪一份进度，以及恢复会影响哪些文件。

与 GalShelf 衔接时以 VNDB 作品编号关联。文件夹改名不应产生另一部作品；但同一作品的不同发行、汉化或补丁版本，仍需要检查存档兼容性。

## 上传、同步与恢复

**上传备份**：保存当前设备进度，不为了上传而先下载覆盖本地，也不把旧进度强行覆盖到云端较新的分支上。

**同步**：比较本地与远端内容和版本关系，在方向明确时处理差异；相同内容不应因为来自不同电脑就反复产生重复备份，出现分歧则进入冲突处理。

**下载与恢复**：明确选择目标版本，核对位置和兼容性后恢复。读取状态与写入操作分开，刷新远端状态不应悄悄改写本地存档。

## 版本历史与多设备冲突

两台电脑分别离线游玩后，可能各自拥有值得保留的新进度。冲突处理保留分歧，由玩家选择继续哪份，不只凭设备时钟或文件修改时间决定覆盖方向。

备份按版本组织，以便找回进度和处理误操作。在新备份尚未安全完成时，不应为了腾出空间而牺牲唯一可用副本。

## 恢复保护

恢复关注游戏是否正在使用存档、目录是否正确、内容是否完整，以及替换结果是否可确认。对将被替换的本地进度保留安全副本，并通过恢复与回滚流程处理失败或中断。

指纹库的作品关联或存档位置提示只是检查依据，不能代替恢复时的授权、安全条件和版本兼容性判断。

## 当前存储后端

| 后端 | 使用方式 | 需要注意 |
| --- | --- | --- |
| **本地目录 / 同步文件夹** | 保存到指定目录，需要时由用户自己的同步客户端传输 | 本地写入完成不代表外部网盘已经上传；跨设备传输由所用客户端完成 |
| **OneDrive** | 直接连接用户授权的云存储 | 依赖应用注册、账号授权与网络条件；适配实现与公开版可连接状态分开说明 |
| **Google Drive** | 直接连接用户授权的云存储 | 同样依赖应用注册、账号授权与网络可达性，实际范围以发布说明为准 |

本页不将 WebDAV、其他国内网盘、S3 兼容存储或官方托管云列为已支持后端，也不提供官方存储空间。

## 与其他模块的关系

**GalShelf** 管理游戏库、作品资料与游玩体验。独立 Galdrive 与 GalShelf 已有云存档相关但并非同一个产品范围，不能将一个版本的功能或界面直接当作另一个版本的承诺。

**Galdex** 提供经核验的身份和存档规则数据，存档流程仍要根据实际本地文件判断可用性、兼容性和写入范围。

**Galguard** 负责文件安全与完整性。安全发现不能因为身份匹配成功或同步需求而被绕过。跨应用共享状态和文件占用协调以对应版本的联调结果为准。

Galdrive 关注存档备份，不自动将游戏程序、整部游戏或任意个人目录上传。用户选择存储位置，容量、流量与账号限制由实际后端决定。独立安装包开放后，将在本仓库发布说明中列明适用版本和可用连接方式。

---

<a id="english"></a>

# Galdrive · Save backup and multi-device synchronisation

[GalShelf home](README.md#english) · [Galdex](GALDEX.md#english) · [Galguard](GALGUARD.md#english) · [简体中文](#chinese)

**Continue on another PC with the progress you choose to keep.**

Galdrive is a separate tool for game saves: backup, version history, synchronisation, conflicts and restoration. It is not storage for entire games and does not replace GalShelf's metadata, library management or play records.

> **Status**: core development is substantially complete; a standalone download is not available yet. Real-account, release-environment and cross-application availability follows the relevant acceptance and release notes. GalShelf 0.2.6 retains its existing cloud saves without requiring the separate application.

## Organise saves by work

Backups should not be an unrecognisable collection of folders. The workflow uses work identity, save location and backup version so players know which progress a backup represents and which files a restore will affect.

Interoperation with GalShelf uses VNDB work IDs. Renaming a folder should not invent another work, but editions, translations and patches still require save-compatibility checks.

## Upload, synchronise and restore

**Upload backup** saves this device's progress, without downloading over local saves first or forcing older progress over a newer remote branch.

**Synchronisation** compares content and version relationships, processing differences when the direction is clear. Identical content should not duplicate backups merely because it comes from another PC; divergent progress requires conflict handling.

**Download and restore** selects a specific version and checks its destination and compatibility. Reading status is separate from writing and must not quietly replace local saves.

## History and multi-device conflicts

Two PCs played offline can both hold progress worth preserving. Keep the divergent versions and let the player choose instead of deciding solely from device clocks or modification times.

Version history supports recovery and mistakes. A new backup must not sacrifice the only usable copy before it has safely completed.

## Restoration protection

Restoration checks whether the game is using the saves, whether the directory is correct, whether the content is complete and whether the result can be confirmed. Retain a safety copy of local progress being replaced and use restoration and rollback handling for interruption or failure.

Identity evidence and save-location proposals do not replace authorisation, safety conditions or compatibility checks.

## Current storage backends

| Backend | Usage | Important distinction |
| --- | --- | --- |
| **Local directory / sync folder** | Write to a chosen directory, optionally transferred by the user's sync client | A completed local write does not prove an external cloud upload has finished |
| **OneDrive** | Connect directly to user-authorised cloud storage | Requires app registration, account authorisation and connectivity; implementation and public availability are separate |
| **Google Drive** | Connect directly to user-authorised cloud storage | Also depends on registration, authorisation and network access; actual availability follows release notes |

WebDAV, additional mainland-China drives, S3-compatible storage and officially hosted storage are not listed as supported here. This page does not offer hosted storage space.

## Component relationships

**GalShelf** handles the library, metadata and playing experience. Its existing cloud saves and independent Galdrive are related but distinct; one release's features or interface should not be presented as another's guarantee.

**Galdex** supplies verified identity and save rules. The save workflow still decides applicability, compatibility and write scope against actual local files.

**Galguard** handles file safety and integrity. A successful identity match or a sync request must not bypass a security finding. Shared state and file-use coordination depend on integration acceptance for the relevant versions.

Galdrive focuses on saves, not automatically uploading executables, entire games or arbitrary personal folders. Users choose storage; capacity, traffic and account rules depend on the backend. Standalone release notes in this repository will identify compatible versions and usable connection methods when downloads open.
