# System Architecture & Technical Specifications

`PDP Studio` is an end-to-end autonomous conversion copywriting engine engineered for high-intent e-commerce platforms (Shopify, Amazon A9/A10/COSMO, and TikTok Shop).

---

## 🏗️ Core Pipeline

The engine executes a four-stage linear pipeline backed by continuous adversarial validation:

```
[Customer Reviews & Specs] 
       │
       ▼
1. VoC & Review Mining ──────▶ Aspect-Based Sentiment Analysis (ABSA) & JTBD Mapping
       │
       ▼
2. Value Hierarchy Engine ───▶ Parameter-to-Benefit (P2B) & Golden Ranking Filter
       │
       ▼
3. Multi-Platform Factory ───▶ Shopify Liquid, Amazon A9/COSMO & Social Copy Compilers
       │
       ▼
4. Adversarial Red-Team ─────▶ Skeptical Buyer Deliberation & Legal Compliance Audit
       │
       ▼
[High-Converting Listing Package]
```

---

## 1. Voice of Customer (VoC) Mining Engine
- **Aspect-Based Sentiment Extraction**: Deconstructs raw 1-star to 5-star customer feedback into granular product facets (ergonomics, thermal performance, maintenance friction, durability).
- **Jobs-to-be-Done (JTBD) Triad**: Classifies customer intent across Functional Jobs (problem solving), Emotional Jobs (anxiety reduction), and Social Jobs (status projection).

## 2. Parameter-to-Benefit (P2B) Transformation
- **Zero-Bare-Spec Rule**: Enforces an absolute constraint that no physical metric (e.g., `20Bar`, `7500mAh`) may appear without a quantified consumer benefit and emotional outcome.
- **Golden Ranking Protocol**:
  $$\text{Unique Advantage (人无我有)} \succ \text{Superior Performance (人有我优)} \succ \text{Distinct Positioning (人优我异)}$$

## 3. Platform-Specific Compilers
- **Amazon A9/COSMO**: Front-loads high-salience semantic search terms into <200 character titles; formats bullet points with capitalized hooks; strictly generates <249 byte comma-free backend search terms.
- **Shopify DTC**: Produces dual-sentence Buy-Box conversion hooks, AIDA mobile scroll-telling blocks, and Google `JSON-LD` Product structured data.

## 4. Adversarial Red-Team Verification
- **Skeptical Buyer Simulation**: Autonomous devil's advocate agent stress-tests every claim against common consumer objections.
- **Regulatory Guard**: Scans for FTC compliance risks, unsubstantiated medical/superlative claims, and marketplace policy violations.
