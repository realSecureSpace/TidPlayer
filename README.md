# TidPlayer — Offline Media Player
A **fully‑local offline** all‑in‑one media player for local music, local videos, and local EPUB e‑books. Everything works within one single app.

- No ads, no user accounts. **Zero network requests** except for App Store in‑app purchases.
- All media files, playback history, bookshelf data, bookmarks and settings are stored locally inside the device sandbox.
---

## Core Features
### Music
- Supports formats including MP3, M4A, FLAC, APE, WAV, OGG, OPUS, AAC, WMA, DTS, AC3, EAC3 and more
- List / Grid view modes; search by local file name
- Favorites, custom playlists, recently‑played tracks
- Persistent mini‑player bar; full‑screen player with vinyl‑style album artwork, **waveform progress bar**, playback speed from 0.5x‑2.0x, loop modes (single / all / shuffle), volume control, swipe left‑right to switch tracks
- Lock‑screen controls, notification‑panel controls, headset remote controls; toggle‑able background audio playback
- Automatically extracts embedded cover art, duration and other metadata during import
- Automatically remembers playback position

### Video
- Supports formats including MP4, MOV, MKV, AVI, FLV, WebM, MPEG / MPG, TS, WMV, 3GP and more
- Grid / List view, favorites, recently‑played videos; auto‑generate first‑frame thumbnails on import
- Full‑screen video player powered by media_kit / libmpv:
  - Gesture controls: adjust brightness on left side, adjust volume on right side, horizontal drag for seek with real‑time feedback
  - Double‑tap left / right region to rewind / fast‑forward 10 seconds with seek indicator
  - Auto‑hide UI controls after 3 seconds of inactivity
  - Playback speed adjustment, multi‑audio‑track selection, external subtitle auto‑matching (SRT / ASS / SSA), hardware / software decoding, loop modes
  - Picture‑in‑Picture (PiP) supported on Android
- Automatically remembers playback position

### E‑Book Library
- EPUB2 / EPUB3 format support
- Bookshelf with grid / list layouts; recently‑read items, reading‑progress indicators, bookmark manager
- Native EPUB reader built on cosmos_epub (no WebView):
  - Day / Sepia / Night display themes
  - Adjustable font size, line spacing and paragraph spacing; re‑paginate precisely after each setting change
  - Screen‑accurate pagination via TextPainter engine. Supports nested chapters, RTL text and page‑flip animations
  - Table‑of‑contents navigation, bookmarks, persistent reading progress synced with the bookshelf

### Management & Settings
- Three default media directories (Music / Video / E‑Books), plus user‑defined custom categories. Type‑based filtering during import prevents mis‑classification.
- Multi‑select mode: batch share and batch delete items
- Per‑file operations: rename, share, delete
- Light / Dark / System‑follows appearance themes
- Background playback toggle
- Reset App option (permanently erases all local application data)

---

# TidPlayer — 离线媒体播放器

一款 **本地离线** 的多媒体播放器：本地音乐、本地视频、本地 EPUB 电子书，一个 App 全搞定。

- 无广告、无账号，运行期间除商店内购外**无任何网络请求**
- 所有媒体文件、播放记录、书架、书签、配置均保存在设备本地沙盒
---

## 核心功能

### 音乐
- 支持 MP3、M4A、FLAC、APE、WAV、OGG、OPUS、AAC、WMA、DTS、AC3、EAC3 等格式
- 列表 / 网格两种视图，本地文件名搜索
- 收藏、自定义播放列表、最近播放
- 迷你播放条常驻；全屏播放器：黑胶唱片式封面、**波形进度条**、倍速 0.5x–2.0x、循环模式（单曲 / 全部 / 随机）、音量、左右滑动切歌
- 锁屏 / 通知栏 / 耳机线控，后台播放可开关
- 导入时自动提取内嵌封面与时长等元数据
- 自动记忆播放进度

### 视频
- 支持 MP4、MOV、MKV、AVI、FLV、WebM、MPEG / MPG、TS、WMV、3GP 等格式
- 网格 / 列表视图、收藏、最近播放；导入时自动生成首帧缩略图
- 全屏视频播放器（media_kit / libmpv）：
  - 手势：左侧调亮度、右侧调音量、水平拖拽进度（带实时反馈）
  - 双击左 / 右区域快退 / 快进 10 秒，显示 seek 反馈
  - 控件 3 秒自动隐藏
  - 倍速、音轨、字幕（SRT / ASS / SSA 外挂字幕自动匹配）、硬解 / 软解、循环模式
  - Android 支持画中画（PiP）
- 自动记忆播放进度

### 书库
- 支持 EPUB2 / EPUB3
- 书架网格 / 列表、最近阅读、阅读进度展示、书签列表
- 阅读器（cosmos_epub 原生文本排版，无 WebView）：
  - 日间 / 护眼 / 夜间主题
  - 字号、行间距、段间距调节，修改后自动重新精确分页
  - TextPainter 按屏幕尺寸精确分页，支持嵌套章节、RTL、翻页动画
  - 目录跳转、书签、阅读进度记忆（与书架联动）


### 管理与设置
- 三个默认媒体目录（音乐 / 视频 / 书库）+ 自建分类目录；目录内导入按类型过滤，防止导错分类。
- 多选模式：批量分享、批量删除
- 单文件操作：重命名、分享、删除
- 浅色 / 深色 / 跟随系统主题
- 后台播放开关
- 重置应用（销毁全部本地数据）

---
