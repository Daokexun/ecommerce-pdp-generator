# Step 7: Visual Storyboard & AI Photography Prompt Engine

## 🎯 任务目标
电商转化靠“七分图三分文”。好的产品图片绝不是白底图的单调排列，而是能视觉化兑现卖点的**叙事分镜（Visual Storyboard）**。本模块负责将前述场景与卖点，转化为可直接喂给 Midjourney、Flux 或 ChatGPT DALL-E 3 的高质量商业摄影提示词。

---

## 🎨 商业静物与场景生图规范
1. **真实度保护**：采用专业摄影棚参数（85mm lens, f/2.8, Hasselblad, soft studio lighting, clean background, photorealistic, 8k resolution）。
2. **构图留白 (Copy Space)**：提示词中明确包含 "ample negative space on top/side for e-commerce typography"（预留排版文案空间）。
3. **消除 AI 塑料感**：加入细微材质纹理描述（brushed aluminum, fine grain matte texture, water droplets, natural fabric folds）。

---

## 🧠 提示词核心逻辑 (Prompt)

```text
你是一位获得国际红点大奖的电商视觉总监与商业摄影师。请针对本产品的“人无我有”核心卖点及 5 大生活场景，设计一套完整的 7 张产品详情页分镜画面方案，并输出对应的中英文 AI 生图提示词（支持 Midjourney / Flux / DALL-E 3）。

### 分镜规划矩阵：
1. **Hero Shot (主屏首图)**：白底或纯净极简浅灰背景，产品 45 度立体悬浮或立于大理石台面，精致光影，无杂物。
2. **Feature Zoom-In (核心技术微距拆解图)**：特写镜头（Macro photography），展示精密工艺细节与高级材质质感。
3. **Problem vs Solution (痛点对比概念图)**：画面分割或直观动作，体现“使用前的手忙脚乱 vs 使用后的优雅从容”。
4. **Lifestyle Morning / Office (生活场景图 A)**：融入现代北欧风家居或极简办公桌，自然晨光透过百叶窗，展现生活格调。
5. **Lifestyle Outdoor / Travel (生活场景图 B)**：真实户外/通勤使用状态，动态手部交互，展现轻巧便携。
6. **Scale & Ergonomics (手持与尺寸感知图)**：真实人手自然握持，或者置于随身背包旁，形成直观尺寸比例参照。
7. **Packaging & What's In The Box (全家福开箱图)**：产品及所有配件整齐排列（Knolling flat-lay style），精致礼盒包装，传递高级送礼心智。

---

### 📤 输出格式要求：

对每一张分镜图，输出：
- **画面编号与作用**：如【Shot 01: 首屏高质感主图】
- **中文视觉指导与构图设计**
- **Midjourney v6 英文提示词 (Prompt)**：包含主体、场景、光影、镜头参数、宽高比（如 `--ar 1:1` 或 `--ar 4:5`）与风格设定。
- **排版建议 (Typography Space)**：文字放在左侧/右侧，推荐搭配哪一句话术。
```
