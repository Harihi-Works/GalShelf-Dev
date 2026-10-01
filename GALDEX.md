<a id="chinese"></a>

# Galdex · 作品指纹与存档规则维护

[项目首页](README.md#chinese) · [GalShelf](GALSHELF.md#chinese) · [Galguard](GALGUARD.md#chinese) · [Galdrive](GALDRIVE.md#chinese) · [English](#english)

**为「本地这些文件属于哪部作品」提供可核验的依据。**

Galdex 是面向维护者的内部工具，负责作品指纹与存档位置规则。它不是另一个作品资料站，也不是玩家需要额外安装的游戏库客户端，而是把本地文件证据整理为经过审核、可以签名发布并由客户端验证的数据。

> **状态**：核心功能已基本完成。本页只介绍能力与分工，不提供内部工具下载。工具完成、正式数据覆盖和消费端接入是不同的进度，实际可用范围以相应数据发布与客户端版本为准。

## 让旧收藏不再只靠名字匹配

收藏多年的游戏可能经历重命名、移盘或重新整理，同一作品也可能有不同发行、汉化和补丁版本。只根据文件夹或 EXE 名称检索，容易遇到别名、同名、名称缺失与匹配歧义。

Galdex 将经核验的文件指纹与作品身份关联。面对已收录文件，客户端可利用内容证据辅助确认作品，而不只猜名字；对于未收录、已变化或存在歧义的文件，不强行给出确定结论。

## 文件证据与作品索引

作品身份沿用 **VNDB 作品编号**，不另外创建公共作品编号，也不替代 VNDB、NextMoe 等资料源。

文件证据包含 SHA-256、精确大小和在游戏中的角色等信息。维护时区分可用于识别作品的游戏文件，与不同游戏可能共用的运行库或辅助程序，避免把共用文件当作唯一身份依据。

同一作品可以关联不同文件证据，但不因此将所有发行、汉化或补丁视为同一版本，也不据此假定存档兼容。

## 存档位置规则

除了「它是哪部作品」，Galdex 也维护「这类游戏的存档可能在哪里」的规则与核验依据，供客户端在选择存档位置时参考。

规则是候选位置和适用依据，不是文件操作指令。客户端仍需核对实际目录、版本兼容性和用户授权。识别成功不能直接触发绑定、上传或恢复，也不能扩大允许写入的目录范围。

## 采集、审核与签名发布

**采集整理**：绑定作品身份，收集文件指纹，附上经核验的存档规则和证据，形成待审候选记录。

**审核确认**：提交候选不等于进入可信数据集。采集、审核与发布分别承担责任，正式结论须经过相应审核。

**签名发布**：确认后的记录形成签名数据集。客户端使用前检查签名、有效性和兼容性；验证失败或数据不再有效时，不能继续作为可信身份依据。

维护的是指纹、规则和关联证据，不是向玩家分发游戏本体、汉化包或个人存档。

## 与其他模块的关系

**GalShelf** 利用身份依据辅助本地作品关联，并结合自己的导入确认、书架索引与管理流程。

**Galguard** 可将经验证的身份作为来源证据，但安全判断仍由自己的完整性和扫描流程负责；指纹命中不能解除威胁阻止或自动接受新文件基准。

**Galdrive** 可结合作品身份与存档规则组织备份和恢复；实际位置、版本兼容性、冲突与写入许可仍由存档流程处理。

**身份识别不等于安全证明；工具完成不等于全库覆盖。** 可识别范围来自实际审核并发布的数据，不宣称覆盖全部作品或发行组合。普通玩家也不需要取得维护工作区、审核权限或签名密钥。

---

<a id="english"></a>

# Galdex · Work fingerprints and save-location rules

[Project overview](README.md#english) · [GalShelf](GALSHELF.md#english) · [Galguard](GALGUARD.md#english) · [Galdrive](GALDRIVE.md#english) · [简体中文](#chinese)

**Verifiable evidence for associating local files with the right work.**

Galdex is an internal maintainer tool for work fingerprints and save-location rules. It is not another metadata website or an extra library application for players. It organises file evidence into reviewed data that can be signed, published and verified by consumers.

> **Status**: core development is substantially complete. This page is not an internal-tool download. Tool completion, production corpus coverage and consumer integration are separate states; availability follows the relevant data and client releases.

## Identify existing collections by more than names

Collections may have been renamed, moved or reorganised. A work may have several editions, translations and patches. Folder and EXE names alone can be ambiguous, incomplete or unrelated to a database title.

Galdex associates verified fingerprints with work identity. Known files provide content-based evidence to assist identification. Unknown, changed or ambiguous files must not be forced into a definitive match.

## File evidence and the work index

Identity uses **VNDB work IDs**, not another public numbering system. Galdex does not replace VNDB, NextMoe or other metadata sources.

Evidence includes SHA-256, exact file size and the file's game role. Maintainers distinguish useful game identity anchors from shared runtimes and helper programs, which must not become unique identifiers merely because several games include them.

Multiple records can identify one work without implying identical editions, translations or patches, or interchangeable saves.

## Save-location rules

Galdex also maintains rules and supporting evidence for where a game's saves may be found, assisting a client's save-directory selection.

A rule is a location proposal, not permission to manipulate files. The client still checks the actual directory, edition compatibility and authorisation. An identity match must not itself bind a path, upload, restore or widen write access.

## Collection, review and signed publication

**Collect**: bind work identity, collect fingerprints, attach verified save rules and evidence, and prepare candidate records.

**Review**: submission does not make a candidate trusted. Collection, review and publication have separate responsibilities, and production records require the appropriate review.

**Publish**: accepted records form a signed data set. Consumers check signatures, validity and compatibility. Failed verification or invalid data must not remain a trusted identity source.

The records describe fingerprints, rules and associations; they are not a distribution channel for game binaries, translation packages or players' saves.

## Component relationships

**GalShelf** can use identity evidence alongside import confirmation, library indexing and management.

**Galguard** can show verified identity as provenance while retaining independent integrity and scanning decisions. A match does not clear a threat or accept a new baseline.

**Galdrive** can use identity and save rules to organise backups and restoration. Actual paths, compatibility, conflicts and write authority remain responsibilities of the save workflow.

**Identification is not proof of safety; a finished tool is not a complete catalogue.** Coverage comes from reviewed, published records. Players do not need a maintainer workspace, review privileges or signing keys.
