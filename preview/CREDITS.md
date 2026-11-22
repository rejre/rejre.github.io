# 风物志 · 图片来源与授权记录（CREDITS）

预览版（/preview/）全部图片逐张记录。规则：只用 Unsplash／Pexels／Pixabay 合规图库或站内既有素材；外链图全部经 `curl -sI` 验证返回 200、并下载缩略图目检内容后才使用（首轮验证 2026-11-23，R1 新增图同日验证）。
统一调色：外链与站内图均加 CSS 暖调滤镜（sepia .14 / saturate .88 / brightness 1.02），选图本身以暖调、低饱和摄影为准。
自托管状态：图片自托管迁移未做，外链图统一为 **CDN 直链，待令牌恢复后自托管**（下表 Unsplash 各条均同此状态，不再逐条重复）。

## 一、品牌商标（1 条）

| # | 用途 | 来源 | 作者 | 授权 |
|---|------|------|------|------|
| T1 | 全站导航、首页首屏衬牌、页脚、关于页品牌块的「风物志商标」原图（data:image/png 内嵌，与现行站点同一份数据，未做任何改绘） | 站长自有商标，现行站点 `new-site/index.html` 内嵌原图 | 站长（风物志） | 站长自有版权 |

## 二、站内既有素材（15 条，沿用现行站点，站长自有/站点已发布素材）

| # | 用途 | 来源文件 | 作者 | 授权 |
|---|------|----------|------|------|
| S1 | 首页「本季精选」小图、美食栏目页秋汤卡、文章页相关推荐（清汤碗） | 现行站点 `new-site/assets/soup-cover.webp` | 见来源页（站内素材） | 站内已发布素材 |
| S2 | 首页横向手账「治愈美食」卡（粗陶炖菜碗） | 现行站点 `new-site/index.html` 内嵌图 | 见来源页（站内素材） | 站内已发布素材 |
| S3 | 首页横向手账「居家质感」卡、首页「本季精选」大图、文章页相关推荐（陶器干花与暖灯） | 现行站点 `new-site/index.html` 内嵌图 | 见来源页（站内素材） | 站内已发布素材 |
| S4 | 首页档案柜外相关推荐、美食栏目页、文章页「下一篇」（鱼片便当） | 现行站点 `new-site/posts/fish-bento.html` 内嵌图 | 见来源页（站内素材） | 站内已发布素材 |
| S5 | 文章页主图、小雪新文「下一篇」卡（切片肉葱花热汤） | 现行站点 `new-site/posts/midnight-soup.html` 内嵌图 | 见来源页（站内素材） | 站内已发布素材 |
| S6 | 首页档案柜 No.01（米白针织帽） | 现行站点 `new-site/posts/beanie-warmth.html` 内嵌图 | 见来源页（站内素材） | 站内已发布素材 |
| S7 | 首页档案柜 No.02、居家栏目页卡（原木卧室） | 现行站点 `new-site/posts/wooden-bedroom.html` 内嵌图 | 见来源页（站内素材） | 站内已发布素材 |
| S8 | 首页档案柜 No.03、风光栏目页卡（远山白屋） | 现行站点 `new-site/posts/mountain-house.html` 内嵌图 | 见来源页（站内素材） | 站内已发布素材 |
| S9 | 首页档案柜 No.04、居家栏目页卡（一室微光） | 现行站点 `new-site/posts/quiet-room.html` 内嵌图 | 见来源页（站内素材） | 站内已发布素材 |
| S10 | 首页档案柜 No.05、居家栏目页卡（冥想雕塑） | 现行站点 `new-site/posts/meditation-sculpture.html` 内嵌图 | 见来源页（站内素材） | 站内已发布素材 |
| S11 | 首页档案柜 No.06、风光栏目页卡（青瓦院落） | 现行站点 `new-site/posts/stone-path-courtyard.html` 内嵌图 | 见来源页（站内素材） | 站内已发布素材 |
| S12 | 居家栏目页卡（灰色条纹床垫一角，R1 新增） | 现行站点 `new-site/posts/casper-wave.html` 内嵌图 | 见来源页（站内素材） | 站内已发布素材 |
| S13 | 居家栏目页卡（浅灰床垫侧面特写，R1 新增） | 现行站点 `new-site/posts/casper-nova.html` 内嵌图 | 见来源页（站内素材） | 站内已发布素材 |
| S14 | 居家栏目页卡（银灰空气净化器，R1 新增） | 现行站点 `new-site/posts/braun-air.html` 内嵌图 | 见来源页（站内素材） | 站内已发布素材 |
| S15 | 风光栏目页卡（青山白墙小院，R1 新增） | 现行站点 `new-site/posts/mountain-courtyard.html` 内嵌图 | 见来源页（站内素材） | 站内已发布素材 |

> 站内图在预览版中经等比缩放重编码为 JPEG data URI 内嵌（与现行站点同一做法），画面内容未做任何修改。

## 三、Unsplash 外链图（11 条，均为 CDN 直链，待令牌恢复后自托管）

CDN 直链格式：`https://images.unsplash.com/photo-<ID>?q=80&w=<宽度>&auto=format&fit=crop`（auto=format 由 CDN 按浏览器协商输出 WebP/AVIF；页面内以 srcset 提供多档宽度）。
作者说明：Unsplash 的 CDN 照片 ID 无法可靠反查作者页 slug，为避免误署，作者统一记「见来源页」，可在 Unsplash 站内以照片 ID 检索原页。

| # | 用途 | 照片 ID / 来源 | 作者 | 授权 |
|---|------|----------------|------|------|
| U1 | 首屏·春（樱花） | photo-1522383225653-ed111181a951 · Unsplash | 见来源页 | Unsplash License |
| U2 | 首屏·夏（林间小径） | photo-1441974231531-c6227db76b6e · Unsplash | 见来源页 | Unsplash License |
| U3 | 首屏·秋（红叶湖畔） | photo-1507371341162-763b5e419408 · Unsplash | 见来源页 | Unsplash License |
| U4 | 首屏·冬（雪山，默认首屏图 + preload） | photo-1418985991508-e47386d96a71 · Unsplash | 见来源页 | Unsplash License |
| U5 | 首页横向手账「远方风光」卡（山峦行者） | photo-1469474968028-56623f02e42e · Unsplash | 见来源页 | Unsplash License |
| U6 | 文章页（midnight-soup）正文图：清汤、切片肉与米粉（R1 换图） | photo-1582878826629-29b7ad1cdc43 · Unsplash | 见来源页 | Unsplash License |
| U7 | 文章页（midnight-soup）正文图：陶锅炖汤（R1 换图） | photo-1603105037880-880cd4edfb0d · Unsplash | 见来源页 | Unsplash License |
| U8 | 小雪新文正文图、首页「本季精选」小图、美食栏目页卡：红亮炖汤（R1 新增） | photo-1548943487-a2e4e43b4853 · Unsplash | 见来源页 | Unsplash License |
| U9 | 小雪新文主图：初冬雪原松林（R1 新增） | photo-1491002052546-bf38f186af56 · Unsplash | 见来源页 | Unsplash License |
| U10 | 小雪新文正文图：居室一角（R1 新增） | photo-1513694203232-719a280e022f · Unsplash | 见来源页 | Unsplash License |
| U11 | 风光栏目页小雪草稿卡：雪后街道（R1 新增） | photo-1477601263568-180e2c6d046e · Unsplash | 见来源页 | Unsplash License |

## 四、YouTube 官方封面（1 条）

| # | 用途 | 来源 | 作者 | 授权 |
|---|------|------|------|------|
| YT1 | 首页页脚「最新一集」卡封面（点击跳转该视频页，加载前不嵌 iframe） | `i.ytimg.com/vi/trS5Oy3kZjs/hqdefault.jpg`；视频为频道 @fengwuzhi 于 2026-11-21 发布的《350 个大气压、能在火星造燃料：猛禽的账算给你看（下）》，经频道官方 RSS 核实为最新一集（2026-11-23） | 风物志频道（站长自有） | 站长自有内容 |

## 五、R1 弃用记录

| 照片 ID | 原用途 | 弃用原因 |
|---------|--------|----------|
| photo-1546069901-ba9599a7e63c | 美食页图卡「清爽一碗」 | 假卡（指向列表页），随假卡一并删除 |
| photo-1504674900247-0877df9cc836 | 美食页图卡「酸辣之间」 | 假卡（指向列表页），随假卡一并删除 |
| photo-1547592180-85f173990554 | 美食页图卡「一蔬一饭」 | 假卡（指向列表页），随假卡一并删除 |
| photo-1547592166-23ac45744acd | midnight-soup 正文图（番茄浓汤） | 与「原汤肉汤」主题不符，换为 U6 |
| photo-1585032226651-759b368d7246 | midnight-soup 正文图（炒面） | 与「原汤肉汤」主题不符，换为 U7 |
| photo-1507371341162-763b5e419408 | 曾兼作页脚 YouTube 门面卡缩略图 | 门面卡改用真实视频封面（YT1）；该图仅保留首屏·秋用途（U3） |

## 六、字体与脚本库（非图片，一并记录）

- 字体：Google Fonts CDN — Noto Serif SC（600/700）、Noto Sans SC（400/500），display=swap。
- 脚本：GSAP 3.12.5 + ScrollTrigger（cdnjs）、Lenis 1.1.18（jsdelivr）。
