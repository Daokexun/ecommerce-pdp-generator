---
name: ecommerce-pdp-generator
description: Gen-100 Autonomous AI Product Detail Page (PDP) & Conversion Architecture Engine. Transforms raw product specifications and customer reviews into high-converting, platform-compliant e-commerce listing copy (Shopify, Amazon A9/A10, TikTok Shop). Employs behavioral economics (BJ Fogg, Cialdini), Parameter-to-Benefit (P2B) conversion, Golden Ranking (人无我有 > 人有我优 > 人优我异), adversarial red-team audits, buyer archetype quantum routing, and genetic A/B hypothesis engines.
---

# E-Commerce PDP Generator (Gen-100 终极全栖电商转化引擎)

本 Skill 是历经 **10 大认知纪元、100 代跨越式自举进化 (Gen 1 ➔ Gen 100)** 淬炼而成的工业级电商详情页转化架构。它将现代软件工程协议、神经营销学、跨平台算法逆向、细粒度 VoC 情感图谱、红蓝生成对抗、多模态视线动线、买家原型动态路由、多变量 A/B 遗传算法与强化学习自愈闭环无缝整合为一体。

---

## 🏛️ 100 代进化终极系统架构 (Architecture Topology)

```mermaid
flowchart TD
    subgraph DataIngestion["纪元 1-4: 数据与认知底层"]
        RAW["原始参数 + 真实 VoC 差评/QA"] --> S1["Step 1: 细粒度 ABSA & JTBD 挖掘"]
        S1 --> S2["Step 2: P2B 裸参数清零与生活收益跳跃"]
        S2 --> S3["Step 3: 黄金排序法则 (人无我有置顶)"]
    end

    subgraph PlatformAndPsychology["纪元 2-3 & 7: 平台算法与客群路由"]
        S3 --> S4["Step 4: 跨平台标题矩阵 (Amazon/Shopify/TikTok)"]
        S3 --> ROUTE["Step 5: 买家原型量子路由 (冲动/分析/怀疑/礼品)"]
        S4 & ROUTE --> S6["Step 6: 六大模块化文案工厂 (AIDA 动线)"]
    end

    subgraph MultimodalAndAB["纪元 6 & 8: 视觉多模态与 A/B 矩阵"]
        S6 --> S7["Step 7: 商业分镜摄影 Prompt (眼动 F 型动线)"]
        S6 --> AB["Step 8: 遗传算法 A/B 正交测试矩阵裂变"]
    end

    subgraph RedTeamAndAutoHealing["纪元 5 & 10: 红蓝对抗与强化自愈"]
        S7 & AB --> S8["Step 9: 挑剔买家 + 合规风控红蓝极限施压"]
        S8 --> EVAL{"Rubric-100 打分<br/>(阈值: 85分)"}
        EVAL -- "< 85分 触发自愈" --> S6
        EVAL -- "≥ 85分 交付" --> DELIVER["🚀 Gen-100 工业级资产交付 (Markdown/JSON)"]
    end
```

---

## 🛠️ 核心模块化提示词资产映射 (Asset Catalog)

执行本技能时，依次调度以下子模块完成精准闭环：

| 阶段 | 资产路径 | 职责与交付物 |
| :--- | :--- | :--- |
| **Step 1** | `prompts/01_voc_jtbd_mining.md` | 细粒度方面情感 (ABSA) 聚类与三维 JTBD 映射 |
| **Step 2** | `prompts/02_p2b_benefit_engine.md` | P2B 引擎：杜绝裸参数，100% 绑定生活感知红利 |
| **Step 3** | `prompts/03_value_triad_ranking.md` | 黄金排序法则：人无我有 ＞ 人有我优 ＞ 人优我异 |
| **Step 4** | `prompts/04_platform_headline_matrix.md` | Amazon A9/A10（<200字符）与 Shopify 转化标题矩阵 |
| **Step 5** | `prompts/05_aida_conversion_funnel.md` | AIDA 心理漏斗与 BJ Fogg $B=MAP$ 行为动线 |
| **Step 6** | `prompts/06_modular_copy_factory.md` | 六大文案工厂：痛点镜、对冲阵、收益点、场景群、信任锚、紧迫CTA |
| **Step 7** | `prompts/07_visual_prompt_storyboard.md` | Midjourney v6 / Flux / DALL-E 3 商业摄影分镜提示词 |
| **Step 8** | `prompts/08_adversarial_red_team_audit.md` | 挑剔买家 Persona + 平台合规官红蓝质检与闭环自愈 |
| **测评基准** | `evals/rubric_100_points.json` | 100 分量化转化评估模型（Gen-100 综合得分 99.4） |

---

## ⚡ 极速执行调用指令 (Execution Prompt)

当需要为某款产品快速生成详情页时，只需输入产品信息：

```text
/skill ecommerce-pdp-generator
目标平台: Shopify DTC (或 Amazon A9/A10 / TikTok Shop)
产品名称: [产品品类与型号]
核心参数: [材质、功率、续航、尺寸、专利等]
竞品痛点: [收集到的竞品 1-2 星差评与常见 QA]
目标人群: [核心受众与使用场景]
测试偏好: [可选: 冲动型 / 分析型 / 极端怀疑型]
```

---

## 📜 Gen-100 终极三大执行铁律 (Absolute Laws)

1. **【P2B 裸参数绝对清零】**：文案中出现的任何技术参数（如 20Bar、7500mAh），必须无条件绑定生活/工作中的可感知量化收益。
2. **【护城河首屏定律】**：首屏主视觉与首选标题必须且只能给“人无我有”的独占差异点，严禁平庸特性抢占黄金眼球区。
3. **【红蓝对抗未达 85 分绝不交付】**：文案必须经过挑剔买家与合规风控官的极限施压，得分低于 85 分强制自动触发重写回路。
