<!-- galshelf-releases: curated README (en). -->
<div align="center">

<img src="assets/icon.png" width="168" alt="GalShelf icon">

# 栞 · GalShelf

**A bookmark for every story.**

Your own galgame bookshelf　·　Windows desktop app　·　local-first

<sub>✦ The new icon arrives in the app with an upcoming update ✦</sub>

<br>

<a href="https://github.com/Harihi86/galshelf-releases/releases/latest"><b>▶ START</b></a>
　｜　<a href="#-load-game--install"><b>📂 LOAD</b></a>
　｜　<a href="#-config--updates-and-verification"><b>⚙ CONFIG</b></a>
　｜　<a href="https://galshelf.com"><b>✦ WEBSITE</b></a>
　｜　<a href="README.zh-CN.md"><b>🌐 简体中文</b></a>

</div>

<br>

> **【Shiori】**
>
> “Welcome back. You stopped at chapter 3 of *Summer Pockets* — and you said you'd finish Kamome's route tonight.<br>
> 　Your games, your playtime, your ratings and that half-written note — I kept them all safe for you.”
>
> <div align="right"><sub>▼</sub></div>

---

## ◆ Prologue · What is GalShelf?

**栞 (shiori)** means *bookmark*. GalShelf is a Windows bookshelf made for people who play galgames and visual novels.
It keeps the games on your drive, the new releases you're waiting for and the memories of every ending in one place:
it times your sessions when you launch from it, lets you rate works with dango, remembers where you stopped in one line,
turns screenshots into share cards, and lets you pick up the story on another PC.

No account is needed; accounts, Steam, cloud saves and the web shelf are optional and can be connected later.
The interface is available in Simplified Chinese and English.

---

## ◆ Common Route · What you'll use every day

| Route | What it does |
| :-- | :-- |
| 📚 **Shelf** | Import by scanning a games folder or the Steam games on this PC; nothing is added until you confirm the matches. Group by company, collection or Steam series; instant search over titles, aliases, original titles, companies and VNDB ids. |
| ⏱ **Timer & play stubs** | Launch a game from GalShelf and it is timed automatically — one stub per session. The home page's last-7-days chart and the statistics show how long you spent with each story. |
| 🍡 **Dango rating & completion** | Rate from 0 to 10 in dango, mark *Completed / All endings / All CGs*, and leave a one-line review. |
| 🔖 **Reading & routes** | A one-line note of where you stopped and your next goal, so you always know which route comes next. |
| 🎮 **Big Picture** | Redesigned for TVs and controllers: move focus with the d-pad or stick and pick the next story from the couch. |
| 🖼 **Screenshots & share cards** | Press <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>G</kbd> in game to open the game menu, take a screenshot, edit it and turn it into a share card. |
| 🛠 **Game tools** | Locale-emulated launch (Locale Emulator), Magpie scaling, per-work window settings and controller-to-keyboard mapping. |
| 🌸 **Companion** | A companion character in the lower-left corner: change her look or size, or turn her off completely. |
| 🎨 **Two layouts & backgrounds** | Switch between A “Classic atmosphere” and B “Integrated layout”; backgrounds can be images, GIFs or MP4 videos, and work pages can play the OP. |
| 🗓 **Release calendar** | Tells VNDB-confirmed release dates apart from unconfirmed announcements, so new titles from the companies you follow don't slip by. |
| 🔍 **Work identification** | Anchored to the VNDB work id and SHA-256 file fingerprints, with quiet hints only when something deserves your attention. |
| 🛡 **GalShelf Guard** | An optional security companion: records a trusted file list per game, spots modified program files, and can quarantine or repair suspicious files. |
| ☁ **Cloud saves** | Once turned on, saves of VNDB-linked works are backed up and restored automatically to a sync folder, with optional end-to-end encryption; *Sync now*, *Upload backup* and *Download / restore* are one click away. |
| 🔄 **Web shelf** | Use a GalShelf account on [galshelf.com](https://galshelf.com); the web shelf and the desktop app sync your records field by field. |

---

## ◆ CG Gallery

> [!NOTE]
> **All screenshots below are a demo.** They were taken with the currently released GalShelf 0.2.6. The shelf holds
> real galgames, but every rating, playtime, progress note and review was made up to show the interface — none of it
> belongs to a real user.

<table>
<tr>
<td width="50%" align="center"><a href="assets/screenshots/en/home.jpg"><img src="assets/screenshots/en/home.jpg" alt="Home"></a><br><sub><b>Home</b> — continue the last story; the past week at a glance</sub></td>
<td width="50%" align="center"><a href="assets/screenshots/en/library.jpg"><img src="assets/screenshots/en/library.jpg" alt="Library"></a><br><sub><b>Library</b> — cover wall, status filters and grouping</sub></td>
</tr>
<tr>
<td align="center"><a href="assets/screenshots/en/my-record.jpg"><img src="assets/screenshots/en/my-record.jpg" alt="My record"></a><br><sub><b>My record</b> — dango rating, completion marks and play stubs</sub></td>
<td align="center"><a href="assets/screenshots/en/reading.jpg"><img src="assets/screenshots/en/reading.jpg" alt="Reading and routes"></a><br><sub><b>Reading & routes</b> — where you stopped and what's next</sub></td>
</tr>
<tr>
<td align="center"><a href="assets/screenshots/en/statistics.jpg"><img src="assets/screenshots/en/statistics.jpg" alt="Play statistics"></a><br><sub><b>Play statistics</b> — daily playtime and your most-played works</sub></td>
<td align="center"><a href="assets/screenshots/en/big-picture.jpg"><img src="assets/screenshots/en/big-picture.jpg" alt="Big Picture"></a><br><sub><b>Big Picture</b> — grab a controller and start from the couch</sub></td>
</tr>
</table>

---

## ◆ Load Game · Install

**You need** Windows 10 or 11 (64-bit) and the Microsoft Edge WebView2 Runtime (Windows 11 usually has it).
No Python, Node.js or administrator rights are required.

1. Download `GalShelf-Windows-<version>.zip` from the [latest release](https://github.com/Harihi86/galshelf-releases/releases/latest).
2. Extract the **whole** ZIP into a new folder and keep the `components` folder (aria2, Magpie, Locale Emulator) next to `GalShelf.exe`.
3. Start `GalShelf.exe` and follow the welcome tour.

> [!TIP]
> GalShelf has no installer and the executable is not code-signed, so Windows SmartScreen may ask you to confirm once.
> Your shelf, settings and records live in `%LOCALAPPDATA%\GalShelf`, not in the program folder — to upgrade, extract
> the new version into a new folder and remove the old one once you're happy; both read the same data.

---

## ◆ Config · Updates and verification

- The app checks for updates in-app by reading this repository's stable channel: `stable/latest.json` (the signed update manifest) and `stable/latest.json.sig` (its detached Ed25519 signature).
- An update is installed only when the manifest signature, the package size and its SHA-256 **all** match.
- `releases/v<version>/` keeps the manifest, checksums and release notes of every published version.
- Update manifests are signed with this public key (Ed25519, base64):

```
galshelf-update-2026-09: II1VyOQWGZphhHvY0bcjvqpuYkb1UjBmzb75h+VfuQc=
```

To check a download yourself, run this in PowerShell and compare the result with `SHA256SUMS.txt` in the same release:

```powershell
Get-FileHash .\GalShelf-Windows-<version>.zip -Algorithm SHA256
```

---

## ◆ Recollection · Release history

Release notes for every version are on the [Releases](https://github.com/Harihi86/galshelf-releases/releases) page
and in the [`releases/`](releases/) folder. Guides and FAQs live at [galshelf.com/docs](https://galshelf.com/docs).

---

## ◆ Staff · Special thanks

- Work details and covers come from public databases such as [VNDB](https://vndb.org).
- Third-party components shipped in the package keep their own licenses: [aria2](https://github.com/aria2/aria2) (GPL-2.0),
  [Magpie](https://github.com/Blinue/Magpie) (GPL-3.0) and [Locale Emulator](https://github.com/xupefei/Locale-Emulator) (LGPL-3.0).

<br>

> **【Shiori】**
>
> “The new icon will come to see you in an upcoming update.<br>
> 　Until then — here's to the next story.”
>
> <div align="right"><sub>～ FIN ～</sub></div>

<sub>Game titles and cover art shown in the screenshots belong to their respective owners and appear only to show the software's interface.</sub>
