# STYLE_PREAMBLE · 上班族-抗炎饮食（F 套·雾蓝鼠尾草绿北欧）

> 新号「上班族-抗炎饮食」专属视觉风格定义。
> 跟老号「A-米白暖橙手绘水彩」**完全反方向**（冷色 vs 暖色 / 北欧 vs 治愈手绘），避免两号被算法判定为同主体。
> 这个文件由 [[xhs-image]] 的 STYLE_PREAMBLE 读取机制（账号→视觉映射）加载，作为每篇笔记图片生成的 prompt 前缀。

参考主页 mock：`候选/F-雾蓝·鼠尾草绿·北欧/主页mock.png`

## 定稿素材（2026-05-17 用户选定）

| 用途 | 文件 | 候选来源 |
|---|---|---|
| 头像（1:1）| `头像.png` | 候选 `F-雾蓝·鼠尾草绿·北欧/头像/avatar-02-Bauhaus几何.png`（鼠尾草绿圆 + 深蓝方 + 大「抗」字）|
| 名片（4:3）| `名片.png` | 候选 `F-雾蓝·鼠尾草绿·北欧/名片/card-01-编辑刊头.png`（左字右图早餐碗）|

未选用的候选保留在 `候选/F-雾蓝·鼠尾草绿·北欧/头像/` 和 `候选/F-雾蓝·鼠尾草绿·北欧/名片/` 下作历史记录。

---

## 色板（绝对禁止超出这套色板）

### 主色（每张必出）

| 用途 | 色 | Hex | 备注 |
|---|---|---|---|
| 主背景 1 | 雾蓝 | `#C5D5DC` | 偏冷调的低饱和蓝灰，**绝不要纯白**也**绝不要彩色饱和蓝** |
| 主背景 2 | 米杏白 | `#F0EEE8` | 跟雾蓝交替（一张里可两块底色拼接，或不同卡片交替）|
| 主点缀 | 鼠尾草绿 | `#88A285` | 用于标题、line illustration、border、icon——这是账号视觉签名色，必出 |
| 主文字 | 深海军蓝 | `#2C3E50` | 正文字色，**不要纯黑**——蓝调显得克制 |

### 扩展色（每张图最多挑 1-2 个）

| 用途 | 色 | Hex | 用在哪 |
|---|---|---|---|
| 深绿强调 | 森林绿 | `#3D5A40` | 关键数字 / 警告标签（用克制）|
| 浅卡其 | 燕麦色 | `#D4C9B3` | 谷物 / 木质 / 自然食材色 |
| 雾橙（克制） | 灰陶橙 | `#C97E4A` | **仅当画橙皮、胡萝卜、橙汁等橙色食物本身时**用，其余场合不出现（避免跟老号撞色）|

❌ **永久禁用色**：暖橙系（老号专属）、玫红、桃粉、樱花粉、纯白 #FFFFFF、纯黑 #000000、霓虹绿、亮蓝 #0066FF、彩虹渐变

❌ **不要饱和度拉满**——所有色都要低饱和、雾感、像北欧家居杂志的色调

---

## 笔触 / 渲染规则

- **扁平极简 + 几何对齐**（NOT 手绘水彩 / NOT 3D / NOT 写实摄影）
- **线稿食物 / 物体**：单色细线条画（鼠尾草绿或深海军蓝线条），不上色或只上 1 层雾感色
- **模块化布局**：圆角矩形 / 圆形 / 简单几何 panel，模块之间有清晰间距
- **印刷感字体**：思源宋体 + Helvetica 类的西式无衬线，字号层级清晰（大标题 + 小说明），字间距宽松
- 阴影：**不要 drop shadow**，需要分层用 panel 颜色对比表达
- 纸张感：可有极淡的纸纹理（不要颗粒胶片感）

❌ **禁用质感**：水彩晕染 / 油画感 / 蜡笔 / 涂鸦 / 复古胶片颗粒 / 故意「不完美」笔触

---

## 主体绘制约束

| 类别 | 必须做到 |
|---|---|
| 人物 | **不画完整真人**；需要时用极简单色剪影 / 抽象图标（无表情、无五官） |
| 食物 / 饮品 | 单色线稿 + 1 层低饱和雾感色 wash，留白；**不要饱和番茄红 / 不要鲜艳橙**——用 #D4C9B3 燕麦或 #88A285 鼠尾草绿 |
| 餐具 / 杯子 | 几何线条画，符合北欧家居杂志的克制感 |
| 数据 / 图表 | 鼠尾草绿单色 bar / pie / line chart，几何对齐，**不要装饰性元素** |
| 背景 | 雾蓝 #C5D5DC 或米杏白 #F0EEE8 二选一，可拼接但不要渐变 |
| 装饰 | 圆形小色块 / 单色 line icon / 短直线分隔符——**每张图 ≤ 2 个装饰**，避免杂乱 |

---

## 字体规则（版式严格锁定）

### 主标题大字（封面 hook 必有）

| 维度 | 锁定值 | 备注 |
|---|---|---|
| 字体 | **思源宋体 Bold / Noto Serif CJK SC Bold** | 模型词：bold serif Chinese, generous letter spacing |
| 字色 | `#2C3E50` 深海军蓝 | RGB(44, 62, 80) |
| 字号 | **96-120 pt**（在 1024×1365 画布上）| 数字强调字 × 1.3-1.5 |
| 位置 | 画面**上方 1/3 区域**，垂直中心在 18%-25% 处 | 占横向 75-85% + 纵向 22-28% |
| 字数 | **≤ 14 字**（推荐 8-12 字）| 行数 ≤ 2 行 |
| 数字强调 | 关键数字字号 × 1.3-1.5，字色改为 `#3D5A40` 森林绿 | 用 IBM Plex Mono 等宽字 |
| 装饰 | 可叠加鼠尾草绿描边 / 圆点 | 不要 drop shadow，不要倾斜 |

### 副 hook 小字（可选）

| 维度 | 锁定值 |
|---|---|
| 字体 | 思源黑体 Bold / PingFang SC Bold |
| 字号 | **48-64 pt**（约主标题 1/2）|
| 字数 | **≤ 8 字**（推荐 4-6 字）|
| 位置 | 右上角 / 左上角 / 主标题正下方 |
| 形态 | 圆角鼠尾草绿底（`#88A285` 填充 + 白字）or 鼠尾草绿单波浪下划线 |

### 正文小字 / byline

- **正文小字**：思源黑体 Regular / PingFang Regular，颜色 `#2C3E50` 或 `#88A285`
- **强调数字 / 单位**：等宽英文字（IBM Plex Mono 风），颜色 `#3D5A40` 深绿
- **英文 byline / 装饰**：Helvetica / Inter，小字号
- ❌ 不要用：艺术体、毛笔字、手写体、广告体英文字、任何渐变字、纯黑 #000

---

## STYLE_PREAMBLE（每个 prompt 必须粘到最前）

### 英文版（gpt-image-2 / 多数模型用）

```
STYLE LOCK (mandatory, applies to every element in the image):
- background: foggy cool blue #C5D5DC OR soft cream #F0EEE8 (may use both in one image as panels), NEVER pure white, NEVER warm-orange, NEVER pink, NEVER gradient
- core palette: sage green #88A285 as the signature accent (titles, line illustrations, borders, charts), deep navy #2C3E50 as body text, oat beige #D4C9B3 as natural-food tone, forest green #3D5A40 as emphasis numbers
- saturation: ALL colors must be LOW saturation, COOL-leaning, foggy, restrained — like a Scandinavian interior magazine. NEVER saturated red, NEVER neon green, NEVER pink, NEVER warm orange (that belongs to the SISTER account, must avoid).
- rendering: flat minimalist geometric design. Modular rounded-rectangle panels, simple line illustrations of food and objects (single-line, no shading), generous whitespace between panels. NEVER watercolor, NEVER 3D render, NEVER photorealistic, NEVER glossy, NEVER hand-drawn imperfections, NEVER film grain.
- subjects (people / food / drinks / objects): all drawn in single-line illustration style with optional low-saturation wash. People as silhouettes only (no faces). Food in line-drawing + a single oat-beige or sage-green tint, leaving white space. NEVER saturated red tomatoes / strawberries / chili.
- typography: title in bold serif Chinese (Noto Serif CJK Bold feel), warm dark navy #2C3E50, generous letter spacing; body text in clean Chinese sans-serif (思源黑体 / PingFang), small size; emphasis numbers in monospace IBM Plex Mono in deep green #3D5A40. NO calligraphy, NO brush-stroke, NO display fonts.
- layout: IKEA-catalog modular grid, panels neatly aligned, breathing space between elements, ≤ 2 decorative elements per image (a small circle / a thin divider line / a small icon).
- mood: Scandinavian wellness magazine, IKEA Food, Aesop visual brand, Muji catalog — sophisticated minimalism, NOT cute, NOT cozy, NOT healing/治愈系.
- forbidden: warm orange, pink, red, watercolor, hand-drawn imperfections, film grain, glossy textures, 3D render, illustrated faces, decorative emoji icons, brush calligraphy, gradient backgrounds, drop shadows, any platform logo, watermark, QR code, red badge, 小红书 mark.
```

### 中文短版（豆包 seedream 用，太长会被截）

```
风格锁定：雾蓝 #C5D5DC 或米杏白 #F0EEE8 底（绝不要纯白 / 彩色 / 暖橙 / 粉色 / 渐变）+ 鼠尾草绿 #88A285 点缀（标题/线稿/边框/图表）+ 深海军蓝 #2C3E50 文字 + 燕麦色 #D4C9B3 自然食材色 + 森林绿 #3D5A40 强调数字。所有色必须低饱和、偏冷、雾感，绝不要饱和红/橙/粉/亮蓝。扁平极简几何风：圆角矩形 panel + 单色细线食物插画 + 大量留白，绝不要水彩 / 不要 3D / 不要写实 / 不要手绘不完美感 / 不要胶片颗粒。人物只画剪影（不画脸）。字体：思源宋体 Bold 标题 + 思源黑体正文 + 等宽数字。整体氛围：北欧家居杂志、IKEA / Aesop / Muji 视觉品牌——克制简约，NOT 治愈、NOT 卡通、NOT 暖意。禁止：任何平台 logo、红色徽章、暖橙、粉色、水彩、装饰 emoji、艺术字、渐变背景、drop shadow。
```

---

## 风格自检（生图后必看）

每张图生成后，对照下面 6 项，**任何一项不达标就重生**：
- [ ] 背景是雾蓝 `#C5D5DC` 或米杏白 `#F0EEE8`，不是纯白 / 不是暖橙 / 不是粉色
- [ ] 点缀色出现鼠尾草绿 `#88A285`（账号视觉签名色），不是其它绿
- [ ] 主体（食物/物体）是单色线稿 + 雾感色 wash，不是 flat vector / 不是 3D / 不是手绘水彩
- [ ] 字体是思源宋体 Bold 大标题 + 思源黑体小字（不是毛笔体、不是艺术字）
- [ ] 整体氛围是「北欧家居杂志」（克制、清爽、雾感），不是「治愈手账」、不是「都市夜归」
- [ ] 跟老号「A-米白暖橙」主页截图并排看，能一眼分辨这是两个账号

---

## 与老号视觉对比

| 维度 | 老号 A-米白暖橙 | 新号 F-雾蓝鼠尾草绿 |
|---|---|---|
| 主背景 | 暖米白 #F7EFE0 | 雾蓝 #C5D5DC + 米杏白 #F0EEE8 |
| 主点缀 | 暖橙 #D9763A | 鼠尾草绿 #88A285 |
| 笔触 | 手绘线稿 + 水彩晕染 | 扁平几何 + 单色线稿 |
| 字体 | 毛笔粗字 + 手写感 | 思源宋体 Bold + 等宽数字 |
| 氛围 | 治愈 + 温暖 + 个人手账 | 克制 + 清爽 + 杂志感 |
| 受众情感 | 想被治愈、想要陪伴 | 想要专业、想要实操 |

两号视觉调性几乎对立，确保用户无法把它们识别为「同一人开的两个号」。

---

## 后续视觉验证

每发 5 篇就用 chrome-devtools 截一次新号主页 + 老号主页并排看，确认「视觉差异度仍然清晰」。如果开始模糊（比如新号封面色板悄悄漂向暖色），回到本文件强化色板。
