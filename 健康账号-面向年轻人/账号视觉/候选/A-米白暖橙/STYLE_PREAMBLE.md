# STYLE_PREAMBLE · 健康账号-面向年轻人（A 套·米白暖橙手绘水彩）

> 老号「健康账号-面向年轻人 (JuankZ) / 朱朱的科学养生」专属视觉风格定义。
> 治愈系手绘水彩风，跟新号「F-雾蓝鼠尾草绿北欧」**完全反方向**（暖色 vs 冷色 / 治愈手绘 vs 北欧杂志），避免两号被算法判定为同主体。
> 这个文件由 [[xhs-image]] 的 STYLE_PREAMBLE 读取机制（账号→视觉映射）加载，作为每篇笔记图片生成的 prompt 前缀。

---

## 色板（绝对禁止超出这套色板）

### 主色（每张必出）

| 用途 | 色 | Hex | RGB | 备注 |
|---|---|---|---|---|
| 主背景 | 暖米白 / 奶油白 | `#F7EFE0` | RGB(247, 239, 224) | 整张图的底，**绝不要纯白 #FFFFFF** |
| 主点缀 | 暖橙 / 赭石橙 | `#D9763A` | RGB(217, 118, 58) | X 号、感叹号、下划线、小水滴、四角星、强调框边、标签角 |
| 强调底色 | 浅奶黄 | `#F3E2B8` | RGB(243, 226, 184) | 关键结论的色块底 |
| 描边 | 浅棕黑 | `#5A4738` | RGB(90, 71, 56) | 物体线稿（不要纯黑 #000）|
| 标题字 | 暖灰黑 | `#2C2725` | RGB(44, 39, 37) | 顶部毛笔粗字 |

### 扩展色（封面挑 3 个、副图挑 2-3 个）

| 用途 | 色 | Hex | RGB | 用在哪 |
|---|---|---|---|---|
| 叶菜 / 植物 | 橄榄绿 | `#9BB373` | RGB(155, 179, 115) | 蔬菜、绿叶（绝不要荧光绿/翠绿）|
| 暖褐 / 焦糖 | 焦糖 / 木质 | `#A0764A` | RGB(160, 118, 74) | 汤、咖啡、面包、饼干、木桌、谷物 |
| 桃粉 / 柔粉 | 樱花桃 | `#E8A88E` | RGB(232, 168, 142) | 水果切面、果肉、面颊红晕（绝不要玫红）|
| 奶油黄 | 蛋黄 / 蜂蜜 | `#F0CD7E` | RGB(240, 205, 126) | 蛋黄、蜂蜜、米饭高光、柠檬、香蕉 |
| 淡水蓝（克制）| 雾蓝 | `#A8C8D8` | RGB(168, 200, 216) | **仅画水/饮品/蓝色液体时**用 |

❌ 永久禁用色：**红色（撞小红书 logo）**、紫色、荧光绿、亮蓝、霓虹色、彩虹渐变、玫红、纯白 #FFFFFF、纯黑 #000000

❌ 跨号不混色：老号绝不用鼠尾草绿 / 雾蓝 / 深海军蓝（新号专属）

### 配色原则（防杂乱）

- 单张图色彩数量 = 1 个米白底 + 1-2 个暖橙点缀 + **2-3 个扩展色**（封面 3 个、副图 1-2 个），上限 6 种
- 所有色统一**低饱和 + 偏暖**——水彩颜料兑水的感觉，不是马克笔
- 扩展色之间必须有视觉间距（米白留白做分隔），不紧贴
- 主体之间用同一组色系（暖橙 / 橄榄绿 / 焦糖 / 桃粉 / 奶油黄随选 2-3 种），不要每个主体一种新色

---

## 笔触 / 渲染规则

- **手绘速写线稿 + 极淡水彩晕染**（loose ink sketch with light watercolor wash）
- 描边可见笔触、可见纸张颗粒纹理，线条不完全闭合、略抖动
- 物体下方淡淡水彩阴影，不要硬投影 / 不要 drop shadow
- 食物 / 物体上色保留留白，不要塑料感 / 不要 3D 渲染感
- ❌ 禁用：纯扁平 vector、flat illustration、studio composition、3D render、glossy、photorealistic

---

## 主体绘制约束

| 类别 | 必须做到 |
|---|---|
| 人物 | **不画完整真人**；需要人体时只画局部（手、脚、剪影、器官示意图），同样用线稿 + 水彩 wash。不刻画五官 |
| 食物 / 水果 | 单个或并排，每个独立轻水彩，留白不要全填满；颜色偏暖（米黄、橙、棕、浅绿少量），**不要鲜红的番茄 / 草莓**——换樱桃番茄用暖橙线条画 |
| 饮品 / 水 | 杯子线稿 + 内部 `#A8C8D8` 淡水蓝 wash；其它饮品（咖啡 / 茶）用暖棕色 wash |
| 器官 / 健身工具 | 解剖图风格线稿 + 极淡水彩，主色就是橙 / 棕，不要解剖书的红色 |
| 背景 | 始终是 `#F7EFE0` 米白底纸张感，禁止彩色背景、禁止渐变、禁止纯白 |
| 装饰 | 角落小橙水滴 / 四角星 / 波浪下划线，**每张图至少出现 1 个**——账号视觉签名 |

---

## 字体规则（版式严格锁定）

### 主标题大字（封面 hook 必有）

| 维度 | 锁定值 | 备注 |
|---|---|---|
| 字体 | **粗黑毛笔字感**（带轻微飞白）| 模型词：bold brush-stroke Chinese calligraphy, slight ink-bleed feel |
| 字色 | `#2C2725` 暖灰黑 | RGB(44, 39, 37) |
| 字号 | **96-120 pt**（在 1024×1365 画布上）| 数字强调字 × 1.3-1.5 |
| 位置 | 画面**上方 1/3 区域**，垂直中心在 18%-25% 处 | 占横向 75-85% + 纵向 22-28% |
| 字数 | **≤ 14 字**（推荐 8-12 字）| 行数 ≤ 2 行 |
| 数字强调 | 关键数字字号 × 1.3-1.5，字色改为 `#D9763A` 暖橙 | 例如「9点的咖啡」中「9」放大 |
| 装饰 | 可叠加暖橙描边 / 单波浪下划线 | 不要 drop shadow，不要倾斜 |

### 副 hook 小字（可选）

| 维度 | 锁定值 |
|---|---|
| 字体 | 手写黑色细体（feel of handwritten ink）|
| 字号 | **48-64 pt**（约主标题 1/2）|
| 字数 | **≤ 8 字**（推荐 4-6 字）|
| 位置 | 右上角 / 左上角 / 主标题正下方 |
| 形态 | 圆角橙色标签底（`#D9763A` 填充 + 白字）or 单波浪下划线 |

### 数字 / 单位（如 250ml / 6g）

- 字体：**等宽手写感**（NOT 印刷体 mono）
- 字色：`#D9763A` 暖橙 or `#2C2725` 暖灰黑
- 配橙色单波浪 / 直下划线

❌ 不要用：sans-serif 印刷体、衬线西文体、艺术体英文字、任何渐变字、纯黑 #000

---

## STYLE_PREAMBLE（每个 prompt 必须粘到最前）

### 英文版（gpt-image-2 / 多数模型用）

```
STYLE LOCK (mandatory, applies to every element in the image):
- background: warm off-white cream paper texture #F7EFE0 (RGB 247,239,224), NEVER pure white, NEVER colored, NEVER gradient
- core palette (must appear in every image): warm orange accent #D9763A (RGB 217,118,58), pale cream highlight #F3E2B8 (RGB 243,226,184), warm gray-black ink #2C2725 (RGB 44,39,37), warm brown outlines #5A4738 (RGB 90,71,56)
- expanded natural palette (pick 2-3 per image, 3 for covers): muted olive green #9BB373 (RGB 155,179,115) for vegetables; warm caramel brown #A0764A (RGB 160,118,74) for soup/coffee/bread/wood; soft peach pink #E8A88E (RGB 232,168,142) for fruit flesh; cream yellow #F0CD7E (RGB 240,205,126) for egg yolk/honey/rice. Pale cool blue #A8C8D8 (RGB 168,200,216) ONLY for water/blue liquid.
- saturation: ALL colors must be LOW saturation, WARM-leaning, watercolor-diluted — NEVER vivid red, NEVER neon green, NEVER hot pink, NEVER bright blue, NEVER pure white, NEVER pure black.
- color count: 1 cream background + 1-2 orange accents + 2-3 expanded colors, max 6 total. Separate colors with cream-paper whitespace.
- rendering: loose hand-drawn ink sketch with light watercolor wash, visible paper grain, slightly uneven lines, soft watercolor shadows. NEVER flat vector, NEVER 3D render, NEVER glossy, NEVER photorealistic.
- subjects: all in line-sketch + watercolor wash style, leaving white space. No saturated red. No full realistic humans — only silhouettes, body parts, stylized anatomy.

COVER TITLE TYPOGRAPHY LOCK (mandatory for cover images):
- main title font: bold brush-stroke Chinese calligraphy, slight ink-bleed feel
- main title color: #2C2725 (RGB 44,39,37)
- main title font size: 96-120 pt on 1024×1365 canvas
- main title position: upper 1/3 of canvas (vertical center at 18%-25% from top)
- main title coverage: 75-85% canvas width, 22-28% canvas height, with 7-12% left/right margin
- max 14 Chinese characters, max 2 lines
- number emphasis: any digit in title scaled to 1.3-1.5x of main font size, color changed to #D9763A (RGB 217,118,58)
- sub-hook (optional): 48-64 pt, max 8 characters, rounded-rectangle background filled with #D9763A
- NEVER drop shadow on title, NEVER tilt title, NEVER 3+ font sizes within title (one main + one number-emphasis is the cap)

- labels/numbers (body): handwritten feel with orange #D9763A wavy underline accents.
- decoration: at least one small orange droplet / four-point star / wavy line in a corner — account signature.
- forbidden: any platform logo, watermark, QR code, red badge, "小红书" mark, pure white background, colored background, flat vector look, sans-serif title, serif Latin title.
```

### 中文短版（豆包 seedream 用，太长会被截）

```
风格锁定：暖米白纸感底 #F7EFE0（RGB 247,239,224，绝不要纯白/彩色背景）+ 暖橙点缀 #D9763A（RGB 217,118,58）+ 浅奶黄 #F3E2B8。扩展色（单张挑 2-3 个、封面挑 3 个）：橄榄绿 #9BB373（蔬菜）、暖褐 #A0764A（汤/咖啡/木）、桃粉 #E8A88E（水果切面）、奶油黄 #F0CD7E（蛋黄/蜂蜜/米饭）、淡水蓝 #A8C8D8（仅水/饮品）。所有色低饱和、偏暖、水彩稀释感。手绘线稿 + 极淡水彩晕染，纸张颗粒，描边浅棕黑 #5A4738 略抖动。

【封面标题版式硬锁】主标题为画面上方 1/3 区域（垂直中心在 18%-25%），粗黑毛笔字感，字色 #2C2725，96-120pt（1024×1365 画布），≤14 字 ≤2 行，左右各留 7-12% 边距。关键数字放大 1.3-1.5 倍、字色改为 #D9763A 暖橙。副 hook 可选右上/左上角圆角橙底标签 48-64pt ≤8 字。不要 drop shadow，不要倾斜字。

角落放小橙水滴或四角星点缀。禁止：任何平台 logo、红色徽章、纯白底、真人写实、霓虹色、彩虹渐变、扁平 vector、印刷体标题。
```

---

## 风格自检（生图后必看）

每张图生成后，对照下面 6 项 + 封面 5 项，**任何一项不达标就重生**：

**全图通用**：
- [ ] 背景是暖米白 `#F7EFE0`，不是纯白、不是其它颜色
- [ ] 点缀色只有暖橙 / 浅奶黄系，没有出现红色 / 蓝色（除了水）/ 紫色
- [ ] 主体（人 / 食物 / 物体）是线稿 + 水彩 wash，不是 flat vector / 不是 3D / 不是写实摄影
- [ ] 角落出现至少 1 个橙水滴 / 四角星 / 波浪下划线（账号视觉签名）

**封面专属**（除以上 4 项外加查）：
- [ ] 主标题字是粗黑毛笔字感，位置在画面上方 1/3 区域
- [ ] 主标题字数 ≤ 14，行数 ≤ 2，左右边距 ≥ 7%
- [ ] 主标题字号视觉重量 = 画面纵向 22-28%
- [ ] 数字强调字明显大于其他字（≥ 1.3×），字色是暖橙 `#D9763A`
- [ ] 没有 drop shadow / 没有倾斜 / 没有 3 种以上字号

---

## 与新号视觉对比

| 维度 | 老号 A-米白暖橙 | 新号 F-雾蓝鼠尾草绿 |
|---|---|---|
| 主背景 | 暖米白 #F7EFE0 | 雾蓝 #C5D5DC + 米杏白 #F0EEE8 |
| 主点缀 | 暖橙 #D9763A | 鼠尾草绿 #88A285 |
| 笔触 | 手绘线稿 + 水彩晕染 | 扁平几何 + 单色线稿 |
| 字体 | 毛笔粗字 + 手写感 | 思源宋体 Bold + 等宽数字 |
| 氛围 | 治愈 + 温暖 + 个人手账 | 克制 + 清爽 + 杂志感 |
| 受众情感 | 想被治愈、想要陪伴 | 想要专业、想要实操 |

两号视觉调性几乎对立，确保用户无法把它们识别为「同一人开的两个号」。
