# Aegis Arc Academy (AAA) — Design System Whitepaper
# 圣盾天弧书院 · 新古典奥术科技设计系统白皮书 (v1.0.0)

## 1. 核心设计哲学与受众平衡公式 (Design Philosophy)

Aegis Arc Academy (AAA) 的视觉语言定义为 **新古典奥术科技风 (Neo-Classical Arcane-Tech)**。
该风格旨在打破传统应试教育的枯燥沉闷，同时摒弃浮夸低幼的商业网游感，通过严格的 **70 / 20 / 10 黄金构成法则** 穿透三方受众：

- **70% 古典学阀骨架 (说服家长)**：大面积采用深曜石黑底、沉稳石板灰与拉丝黄铜微蚀刻，结合经典欧洲学术衬线体，营造名门学府的深厚学术底蕴；
- **20% 现代全息科技 (抓牢 Gen Alpha)**：融入半透明毛玻璃拟态 (Glassmorphism)、冷青/琥珀全息悬浮 HUD 与平滑粒子动效，打造高维知识探索终端的未来潮感；
- **10% 工程级规范标注 (通过督学)**：严格遵循安省无障碍法规 (AODA 4.5:1 高对比度)，以等宽航天级字体清晰标注课程代码、GS 四维能力维度与 110 学时数据，确保绝对的教育合规性。

---

## 2. 基础设计变量与色彩体系 (Design Tokens & Color Palette)

### 2.1 基础中性底色 (70% Base Neutrals)
- `--bg-obsidian`: `#0b0f19` (深曜石黑，主背景基底)
- `--bg-slate`: `#1e293b` (石板冷灰，卡片与面板基础底色)
- `--panel-glass`: `rgba(15, 23, 42, 0.75)` (毛玻璃半透明浮层，配合 blur 16px)
- `--border-brass`: `#c5a059` (古典拉丝黄铜金，主要边框与机械卡榫)
- `--border-brass-glow`: `rgba(197, 160, 89, 0.35)` (黄铜微光扩散晕染)

### 2.2 全息科技微光 (20% Cyber-Hologram Accents)
- `--holo-cyan`: `#38bdf8` (全息冷青，主交互焦点与悬浮文字)
- `--holo-cyan-glow`: `rgba(56, 189, 248, 0.30)` (全息呼吸光环)
- `--holo-amber`: `#fbbf24` (远古奥术暖金，用于稀有度与火漆印章)
- `--holo-violet`: `#a855f7` (以太高维紫，用于高阶跨学科连携)

### 2.3 九大元素学派功能色 (The 9 Elemental Hues)
- 💧 **Aqua (表达力)**: `#0284c7` (深海靛蓝)
- 🔥 **Pyra (数理力)**: `#ea580c` (真理烈焰)
- ⚙️ **Machina (构建力)**: `#0d9488` (极客青绿)
- 🌿 **Terra (实证力)**: `#16a34a` (原初翡翠)
- ⚡ **Volt (社会力)**: `#eab308` (秩序金黄)
- 💰 **Aurus (价值力)**: `#d97706` (美第奇琥珀)
- 🎨 **Lumen (创思力)**: `#ec4899` (光谱棱镜粉)
- 🛡️ **Corpus (身心力)**: `#dc2626` (坚毅深红)
- 🗣️ **Verba (多语力)**: `#8b5cf6` (巴别星轨紫)

---

## 3. 字体排印规范 (Typography Hierarchy)

- **主标题与校名 (Headings & Brand)**:  
  `font-family: 'Cinzel', serif;` (字重 700/900，大写，Letter-spacing 0.05em–0.2em)
- **通用正文与叙事剧本 (Body & Narrative)**:  
  `font-family: 'Plus Jakarta Sans', sans-serif;` (字重 300/400/600，行高 1.7)
- **工程数据、状态与课标指标 (Metadata & Stats)**:  
  `font-family: 'JetBrains Mono', monospace;` (字重 400/600，严格等宽，全大写)

---

## 4. 核心组件规格 (Component Specifications)

### 4.1 全息古卷卡牌结构 (Card Anatomy — 标准 3:4 比例)
- **外框 (The Slate Frame)**: 哑光深曜石切面，四角内嵌 1px 拉丝黄铜咬合卡榫；
- **内芯 (The Holo-Parchment)**: 悬浮半透明冷光羊皮纸，鼠标悬停时产生 2.5D 物理倾斜透视 (`transform: perspective(1000px) rotateX(...) rotateY(...)`)；
- **中央画幅 (The Etching Window)**: 手绘工笔版画插图，周围环绕旋转的微细全息同心环与动态文字粒子流；
- **状态标头 (Status Header)**:  
  顶部规整标注 `[ENG3U // AQUA]`，底部显示 `SEAL: COMM-03 | MASTERY: 88% (LEVEL 4)`；
- **对战属性表达**: 严禁出现传统掉血 HP，统一采用 **【立论信服度与真理护盾 (Coherence & Conviction Shield)】**。

### 4.2 克洛诺斯全息时间环 (110-Hour Chronos Energy Gauge)
- **定位**: 满足安省教育部 Appendix G 视察的有效学时仪表盘；
- **视觉表现**: 外环为古希腊黄铜刻度盘，内环为流动呼吸的冷青光晕；每完成一节课件研读与任务，光环填充一格并跳出等宽合规提示。

### 4.3 学者编年史展示墙 (Hall of Chronicles)
- **定位**: 面向公众展示学生终极项目（如改写《麦克白》命运剧本）的公开平台；
- **视觉表现**: 哥特石拱柱长廊背景，配以悬浮发光的羊皮纸展台与真实受众点赞光流。

---

## 5. 无障碍合规准则 (Accessibility & AODA Compliance)

- **对比度要求**: 正文文本与背景对比度严格大于 4.5:1，重要标题与状态标签大于 7:1；
- **非单纯色彩编码**: 所有状态提示必须同时具备**“文字说明 ＋ 形状/符文图标 ＋ 颜色”**三重标识，杜绝仅靠颜色区分信息；
- **动效减弱适配**: 提供 `@media (prefers-reduced-motion: reduce)` 适配，允许用户关闭 2.5D 倾斜和粒子动效。
