# Huawei AI Chip Revenue Claim — Analytics Investigation
**Analyst:** Igusti Agung Vadayogi Raharja
**Date started:** May 4, 2026
**Purpose:** Validate Huawei's claim of 60% AI chip revenue growth to ~$12B in 2026 using public data and triangulation. Documents both the analytical process and findings for potential LinkedIn content.

---

## The Claim (Source: Financial Times, April 30, 2026)

> Huawei expects revenue from its AI chips to jump at least 60% in 2026 to approximately **$12 billion**, up from **$7.5 billion in 2025**, based on orders already received — driven by DeepSeek V4 adoption and tightening U.S. export restrictions on Nvidia.

**Key sub-claims to stress-test:**

| # | Sub-Claim | Status |
|---|---|---|
| 1 | $7.5B 2025 baseline is from official Huawei reporting | ❌ Unverified — anonymous FT sources |
| 2 | 60% growth is order-book-driven, not market projection | ✅ Confirmed |
| 3 | Huawei market share gain = Nvidia market share loss | ✅ Broadly supported |
| 4 | Nvidia's China decline is verifiable | ✅ Confirmed from Nvidia filings |
| 5 | DeepSeek V4 directly caused the demand surge | ✅ Directionally confirmed |

---

## Analytical Framework

**Approach:** Since Huawei doesn't publicly break out AI chip revenue, direct verification is impossible. The method is triangulation — build the case from multiple imperfect but independent data points to determine whether the claim is **plausible, implausible, or inflated**.

**5-Step Process:**
1. Decompose and verify sub-claims → ✅ Complete (see below)
2. Identify data sources and assess reliability → ✅ Complete (see below)
3. Bottom-up unit × ASP revenue model → ✅ Complete (see below)
4. Cross-validate via competitor (Nvidia) data → ✅ Complete (see below)
5. Stress-test the DeepSeek V4 demand driver → ✅ Complete (see below)

---

## Step 1 — Decompose the Claim: What to Verify

### Finding 1.1 — Is the $7.5B 2025 baseline from official Huawei reporting?

**Verdict: ❌ No — anonymous sourcing, not confirmed in filings**

The 60% AI chip revenue surge projection for 2026 is based on anonymous sources, not Huawei's official filings.

- Huawei's 2025 Annual Report (released March 31, 2026) reports total revenue of **CNY 880.9 billion (~$127.8 billion)** with **no breakdown or forecast for specific AI chip (Ascend) revenue segments**.
- The 60% growth to ~$12B from $7.5B was first reported by the **Financial Times on April 30, 2026**, citing *"sources familiar with the matter"* — echoed by Reuters and others without independent verification.
- Huawei has issued official statements only confirming Ascend SuperNode support for DeepSeek V4 models (via Weibo).
- No Q1 2026 earnings have been released as of May 4, 2026 to confirm forward guidance.

**Analytical implication:** The $7.5B baseline cannot be independently confirmed from public filings. This is the single weakest link in the entire claim chain — everything downstream (the 60% growth, the market share projections) is built on a figure that originates from anonymous sourcing.

---

### Finding 1.2 — Is the 60% growth order-book-driven or a general market projection?

**Verdict: ✅ Order-book-driven — more credible than a market estimate**

- The Financial Times (April 30, 2026) reported that Huawei bases its forecast on **orders already received** for Ascend 950PR chips — not on market modeling.
- Demand is attributed to Chinese tech giants (Alibaba, ByteDance, Tencent) accelerating purchases amid DeepSeek V4's launch and Nvidia shipment delays.
- Morgan Stanley separately projects overall China AI chip market at ~$21B domestic supply in 2026 — Huawei's figure is specifically tied to confirmed backlog, making it a **demand-side reality check, not an aspiration**.

**Analytical implication:** Order-book-driven projections are stronger than analyst market estimates. The mechanism (specific buyers, specific chips, specific trigger) is credible — but the 60% still depends on the $7.5B unverified baseline from Finding 1.1.

---

### Finding 1.3 — Does Nvidia's market share decline = Huawei's gain?

**Verdict: ✅ Broadly supported — the math largely holds**

- In H1 2025: Nvidia held **62% of China's AI server chip market** ($16B total); domestic chips (led by Huawei) captured **35%**.
- By early 2026: Chinese chips reached **41% share** amid U.S. export curbs blocking Nvidia H200/H20 shipments — Huawei Ascend orders from Alibaba, ByteDance, Tencent accelerating.
- Morgan Stanley projects China's 2026 AI chip market at ~$21B domestic supply, where **Huawei's ~50% share = ~$10.5B** — aligning closely with the FT-reported $12B (which includes exports).
- Huawei's 750,000-unit Ascend 950PR target represents 3–5% of Nvidia's global compute power but captures redirected Chinese demand.
- Nvidia CFO confirmed **zero China H200 revenue** — the supply vacuum is real.

**Analytical implication:** The competitive displacement story is the strongest pillar of this claim. The directional shift (Nvidia out, Huawei in) is unambiguous. The $10.5B domestic estimate vs. $12B total (including exports) is a reasonable gap.

---

### Finding 1.4 — Is Nvidia's China revenue decline verifiable?

**Verdict: ✅ Confirmed from official Nvidia filings**

- **Nvidia Q3 FY2026** (ended Oct 2025): China (including HK) revenue **dropped 63% YoY to $3 billion**, even as total Nvidia revenue surged 62% to $57B.
- Management expressed direct disappointment over export curbs blocking H20/H200 access.
- **Nvidia FY2025 full-year revenue:** $130.5B (up 114% YoY) — China-specific annual breakdown not detailed beyond quarterly drops.
- **Q1 FY2026** (ended Apr 2025): Revenue reached $44.1B (up 69% YoY), with no China recovery noted.
- H200 exports resumed March 2026 under U.S. licenses but face Beijing scrutiny favoring domestic chips.

**Analytical implication:** This is the cleanest data point in the entire analysis — Nvidia's China collapse is confirmed, documented, and quantified. The ~$50B+ annual China opportunity vacuum is real and creates the market space that makes Huawei's claim structurally plausible even if the exact figures are unverified.

---

### Finding 1.5 — Did DeepSeek V4 directly trigger the demand surge?

**Verdict: ✅ Directionally confirmed — timing and analyst consensus align**

- **DeepSeek V4 launched April 24, 2026.** Huawei officially confirmed Ascend SuperNode support the same week.
- Reuters sources tied the model rollout directly to a *"surge in chip orders and inquiries"* from Alibaba, Tencent, and ByteDance for inference workloads.
- SMIC shares jumped **10%** on V4 news — a market signal reflecting Ascend 950PR manufacturing demand (SMIC manufactures the chip using its N+3 process).
- Huawei's 2026 shipment target of **750,000 Ascend 950 units** (revised upward from prior plans) reflects model-driven backlog.
- No exact order volumes were disclosed; the link is analyst consensus and timing correlation, not causal measurement.

**Analytical implication:** The causal chain (V4 launch → Huawei chip adaptation → orders surge) is plausible and directionally supported. The risk is assuming correlation equals causation — orders may have been building before V4. The 750,000-unit target and SMIC share jump are the most concrete quantitative signals.

---

## Step 1 — Summary

| Sub-Claim | Verdict | Confidence | Key Risk |
|---|---|---|---|
| $7.5B 2025 baseline is official | ❌ Unverified | Low | Entire claim built on anonymous sourcing |
| 60% growth is order-book-driven | ✅ Confirmed | High | Still depends on unverified baseline |
| Huawei gains = Nvidia losses | ✅ Broadly supported | High | $10.5B domestic vs $12B total is plausible |
| Nvidia China decline verifiable | ✅ Confirmed | Very High | Cleanest data point; no ambiguity |
| DeepSeek V4 drove demand surge | ✅ Directional | Medium | Correlation confirmed, causation assumed |

**Overall Step 1 Conclusion:**
The claim is **structurally plausible but not independently verifiable**. The strongest pillar is Nvidia's confirmed collapse in China creating a supply vacuum — the weakest pillar is the $7.5B baseline, which has no public documentation. The honest analytical output: Huawei reaching $10–12B in AI chip revenue in 2026 is credible, but the specific 60% growth figure cannot be confirmed or denied from public data.

---

## Step 2 — Data Source Reliability Mapping

**Objective:** Classify every data point used in this analysis by source type, reliability, and what it can and cannot confirm. This prevents mixing high-confidence and low-confidence data as if they carry equal weight.

**Reliability tiers used:**
- **Tier 1 — Official/Verified:** Public filings, SEC reports, audited financials, executive statements on record
- **Tier 2 — Credible Secondary:** Named analyst firms, independent market research, corroborated reporting
- **Tier 3 — Unverifiable:** Anonymous sourcing, unconfirmed orders, projections without disclosed methodology

---

### Source Map

| Data Point | Source | Tier | Confirms | Cannot Confirm |
|---|---|---|---|---|
| Huawei total revenue CNY 880.9B ($127.8B) in 2025 | Huawei 2025 Annual Report (March 31, 2026) | **1** | Total group revenue | AI chip revenue specifically |
| Huawei "computing" segment shift in annual report | Huawei 2025 Annual Report | **1** | Strategic pivot toward compute | Whether Ascend revenue is captured here, and how much |
| Huawei AI chip revenue $7.5B (2025) | FT, May 1, 2026 — anonymous sources | **3** | Nothing directly — unverified | Revenue figure, baseline, growth rate |
| Huawei AI chip revenue target $12B (2026) | FT, May 1, 2026 — anonymous sources | **3** | Nothing directly | Forward revenue; Reuters explicitly could not verify |
| Nvidia China revenue −63% YoY to $3B (Q3 FY2026) | Nvidia quarterly earnings (SEC filing) | **1** | China revenue collapse, magnitude | Where that demand went specifically |
| Nvidia China historical share ~25% of data center revenue | Nvidia filings + analyst commentary | **1–2** | Historical exposure level | Current or future share |
| Nvidia China AI chip share: 95% (peak) → 8% (2026 projected) | Bernstein analyst estimate | **2** | Direction of decline | Exact endpoint — 8% is a projection, not a filed result |
| Jensen Huang: leading-edge chip share in China "collapsed to 0%" | Public executive statement (on record) | **1** | High-end segment collapse | Whether this applies to all Nvidia China revenue |
| H200 blocked despite US export licenses — "regulatory stalemate" | Reuters / trade reporting | **2** | Supply-side blockage mechanism | Duration or resolution timeline |
| ByteDance $5.6B Ascend chip commitment | Cited in analysis sources | **2–3** | A large, named-buyer order exists | Whether this is confirmed publicly by ByteDance or Huawei |
| Alibaba, Tencent, ByteDance order surge (post-V4) | Reuters — sourced but not independently verified | **2** | Named buyers are actively ordering | Exact volumes, pricing, timelines |
| Huawei 750,000-unit Ascend 950 shipment target (2026) | Industry analysts / media reporting | **2** | Shipment ambition | Whether SMIC manufacturing capacity can fulfil this |
| SMIC share price +10% on DeepSeek V4 launch | Market data (verifiable) | **1** | Market signal of demand expectation | Actual order volumes — share price reflects sentiment, not contracts |
| DeepSeek V4 launched April 24, 2026 + Huawei Ascend support | DeepSeek official + Huawei Weibo (on record) | **1** | Product launch date, Huawei compatibility | Volume of inference demand this generates |
| Morgan Stanley: China AI chip domestic market ~$21B in 2026 | Morgan Stanley projection | **2** | Analyst market sizing | Actual market out-turn; projection methodology not fully disclosed |
| TrendForce: China high-end AI chip market +60% in 2026 | TrendForce market report | **2** | Direction and magnitude of market growth | Huawei's specific share within it |
| Huawei Ascend ecosystem: 4M+ developers | Huawei official statement | **1** | Ecosystem adoption scale | Conversion to revenue or chip demand |

---

### Finding 2.1 — The Asymmetry Problem

The most important conclusion from this source map is a fundamental **asymmetry in data quality** between the two sides of this story:

**Nvidia's decline** rests almost entirely on Tier 1 sources — SEC filings, audited earnings, executive statements. The 63% China revenue drop, the executive "collapsed to 0%" admission, the H200 blockage — all verifiable, documented, on record.

**Huawei's gain** rests almost entirely on Tier 3 sources — two anonymous FT figures ($7.5B and $12B) that Reuters explicitly said it could not verify. Every other Huawei-positive data point (market share projections, unit targets, order surge) is Tier 2 at best, downstream of the Tier 3 baseline.

This means the analysis has a structurally lopsided evidentiary base: one side is solid, the other is built on inference.

---

### Finding 2.2 — The ByteDance $5.6B Anchor

One new specific data point from validation sources is significant: a **$5.6B ByteDance order commitment** for Ascend chips. If accurate, this alone accounts for nearly **47% of the $12B target** from a single named customer. This is the most concrete demand-side anchor in the entire claim chain.

However, this figure is Tier 2–3 — not confirmed publicly by ByteDance or Huawei in any official filing. Its credibility depends on whether it surfaces in ByteDance's own capex disclosures or supply chain reporting. Worth tracking as a key verification milestone.

---

### Finding 2.3 — The "Computing Segment" Grey Zone

Huawei's 2025 Annual Report does not break out AI chip revenue but does describe a strategic shift toward **"computing" and "intelligent automotive solutions"** as key growth segments. This raises an important analytical question: is Ascend revenue partially captured inside the "computing" segment?

If so, it may be possible to triangulate a partial AI chip revenue range by:
- Isolating the "computing" segment growth rate from the annual report
- Comparing it against the claimed $7.5B figure
- Checking whether the implied computing segment size is consistent with 880.9B yuan total

This is a grey zone — not a red flag, but an area where more official disclosure could partially close the verification gap.

---

### Finding 2.4 — Production Capacity as the Hidden Risk

Multiple sources note that the $12B figure is **order-book-driven** — demand is there, but fulfilment depends on SMIC's manufacturing capacity for the Ascend 950PR (N+3 process). This introduces a supply-side risk not captured in the revenue claim itself:

- **Risk:** Even if orders are real, revenue recognition depends on chip delivery
- **Signal to watch:** SMIC capacity announcements, N+3 process yield rates, Huawei delivery timelines
- **Implication for the claim:** $12B may be the demand ceiling, not the revenue guarantee — actual revenue could land lower if production bottlenecks materialise

---

### Step 2 — Summary

| Source Category | Data Points | Claim Support | Reliability |
|---|---|---|---|
| Nvidia filings (Tier 1) | China revenue decline, executive admissions | Indirect — confirms supply vacuum | Very High |
| Huawei official report (Tier 1) | Total revenue, "computing" segment | Partial — no AI chip breakout | High for what it covers |
| Analyst projections (Tier 2) | Market size, share estimates, unit targets | Directional — consistent with claim | Medium |
| FT anonymous sourcing (Tier 3) | $7.5B baseline, $12B target | Foundation of the claim | Low — unverifiable |
| ByteDance order (Tier 2–3) | $5.6B specific order | Strongest demand anchor yet | Medium — needs confirmation |

**Overall Step 2 Conclusion:**
The data source map exposes the claim's core vulnerability: the two most important numbers ($7.5B and $12B) sit on the weakest evidence tier (Tier 3 — anonymous sourcing). Everything credible in the analysis supports the *direction* of Huawei's growth but cannot confirm the *magnitude*. The ByteDance $5.6B figure and SMIC's production capacity are the two data points most worth watching for Step 3's bottom-up model.

---

## Step 3 — Bottom-Up Revenue Model: Units × ASP

**Objective:** Build a revenue estimate from physical inputs (units shipped × price per unit) and compare it against the $12B claim. Where the model lands tells us whether the claim is achievable, optimistic, or implausible.

This step was run using two independent data sources — analyst research (user-sourced) and independent web search — to identify where they agree and where they diverge before building the model.

---

### 3.1 — Data Comparison: Research vs. Independent Search

| Data Point | User Research File | Independent Web Search | Verdict |
|---|---|---|---|
| Base chip ASP (DDR version) | $6,900 (50,000 yuan) | $6,900–$7,200 | ✅ Consistent |
| Premium chip ASP (HBM version) | $9,600 (70,000 yuan) | $9,600–$10,000 | ✅ Consistent |
| Hyperscale blended ASP | $16,000 per unit | $16,000 per unit | ✅ Exact match |
| 2026 shipment target | 750,000 units | 750,000 units (950PR); 1.6M dies total Ascend line | ✅ Consistent + new context |
| SMIC yield rate | ~40% | 60–70% (general 7nm); 40% confirmed for Ascend 910C | ⚠️ Divergence — see note |
| Primary production bottleneck | Wafer fab capacity | HBM supply (per SemiAnalysis) | ⚠️ Different constraint |
| ByteDance order | $5.6B / ~350,000 units | $5.6–5.7B / ~350,000 units | ✅ Confirmed across multiple sources |
| Combined buyer orders (all named) | Alibaba + Tencent "hundreds of thousands" | ByteDance + Alibaba + Tencent >500,000 units combined | ✅ Consistent + more precise |
| New capacity expansion | Two new wafer fabs H2 2026 | 7nm capacity doubling planned; SMIC 45K→60K wspm | ✅ Consistent |
| ByteDance total compute spend | Not noted | $14B total in 2026, of which $5.6B is Huawei | 🆕 New context |
| CUDA compatibility | Not noted | Ascend 950PR can run CUDA workloads | 🆕 New context — adoption driver |
| Mass production start | Not specified | April 2026 | 🆕 New context |

**Two meaningful divergences:**

**Yield rate (40% vs. 60–70%):** The user's file cites ~40%, consistent with early-stage reports and confirmed for the older Ascend 910C. Independent search finds general SMIC 7nm yields have improved to 60–70% — but the 950PR is newer and more complex. Conservative assumption (40%) is used for the model; 60% used for the optimistic case. This is the most consequential divergence for the model output.

**Bottleneck identification:** User's file points to wafer fab capacity as the constraint. Independent search (SemiAnalysis) identifies **HBM (High Bandwidth Memory) supply** as the actual bottleneck — a harder constraint because HBM comes from SK Hynix and Samsung, both subject to US export pressure on advanced memory. If HBM supply is the real ceiling, adding new wafer fabs doesn't solve the problem.

---

### 3.2 — Input Assumptions

**Units shipped range:**

| Scenario | Units Shipped | Basis |
|---|---|---|
| Conservative | 500,000 | Yield rate 40%, HBM supply constrained, fabs not yet online |
| Base | 625,000 | Yield rate 55%, partial HBM supply resolved, H2 fabs partial ramp |
| Bull | 750,000 | Full target met — yields at 60%+, HBM supply secured, both fabs online H2 |

**ASP range:**

| ASP Scenario | Price | Basis |
|---|---|---|
| Low | $9,600 | Chip-only HBM unit pricing — buyer takes chip without full cluster integration |
| Mid | $13,000 | Blended mix of chip-only sales and hyperscale cluster deployments |
| High | $16,000 | Full hyperscale blended ASP — all units deployed at cluster scale by major buyers |

---

### 3.3 — Three-Scenario Revenue Model

**Formula:** Revenue = Units Shipped × ASP

| Scenario | Units | ASP | Implied Revenue | vs. $12B Claim |
|---|---|---|---|---|
| Conservative | 500,000 | $9,600 | **$4.8B** | −60% below claim |
| Conservative | 500,000 | $13,000 | **$6.5B** | −46% below claim |
| Base | 625,000 | $13,000 | **$8.1B** | −33% below claim |
| Base | 625,000 | $16,000 | **$10.0B** | −17% below claim |
| Bull | 750,000 | $13,000 | **$9.75B** | −19% below claim |
| **Bull** | **750,000** | **$16,000** | **$12.0B** | **= Claim exactly** |

**Reverse calculation (what the $12B requires):**

| If units shipped = | Then required ASP = | Is this plausible? |
|---|---|---|
| 750,000 | $16,000 | ✅ Yes — only at full hyperscale blended rate |
| 625,000 | $19,200 | ⚠️ Unlikely — exceeds HBM chip pricing, approaches Nvidia H20 range |
| 500,000 | $24,000 | ❌ No — this would price above Nvidia H100/H200 |

**Key finding:** The $12B target is only achievable in the single most optimistic scenario — where all 750,000 units are shipped AND all are sold at the full $16,000 hyperscale cluster ASP. Any shortfall in either variable pushes the outcome materially lower. The realistic base case lands at $8–10B.

---

### 3.4 — ByteDance Unit Allocation Check

This is the most concrete anchor in the model, because ByteDance's $5.6B commitment is the most sourced and corroborated figure in the entire analysis.

```
ByteDance commitment:    $5,600,000,000
÷ Hyperscale ASP:        $16,000
= Implied units:         350,000 units
= % of 750K target:      46.7%
```

**Remaining capacity after ByteDance:** 400,000 units

Named additional buyers and their implied scale:
- Alibaba Cloud + Tencent Cloud: combined "hundreds of thousands" — independently sourced as >150,000 units
- GPU cloud/rental market: growing demand, no volume disclosed
- Other enterprise buyers: unquantified

**Conservative allocation for remaining buyers:**

| Buyer | Implied Units |
|---|---|
| ByteDance | 350,000 |
| Alibaba Cloud | ~100,000 |
| Tencent Cloud | ~75,000 |
| GPU rental + others | ~75,000+ |
| **Total demand** | **~600,000+** |
| Production target | 750,000 |
| Buffer | ~150,000 units |

**Finding:** Demand appears to be real and approaching the production ceiling, but the named committed orders alone (~600K implied units) suggest Huawei may be supply-constrained before demand-constrained — meaning the $12B is a ceiling set by manufacturing, not by buyer appetite. If the HBM bottleneck limits output to 500–600K units, revenue lands at $8–9.6B regardless of how large the order book is.

---

### 3.5 — The HBM Bottleneck: Why It Matters More Than Wafer Fabs

This is the divergence that most changes the risk picture. New wafer fabs can increase the number of chips Huawei produces — but HBM memory must be attached to each chip to make it functional for AI workloads, and HBM comes from:
- **SK Hynix** (South Korea) — subject to US export controls on advanced memory to China
- **Samsung** (South Korea) — same constraint
- **CXMT / domestic China** — ramping, but not at sufficient scale or spec for 2026

If HBM supply is the binding constraint, the new fab announcements don't move the revenue needle as much as they appear to. The real question for Step 5 will be whether Huawei has secured HBM supply in sufficient quantity for 600K+ units.

---

### Step 3 — Summary

| Model Output | Revenue Range | Confidence |
|---|---|---|
| Conservative case | $4.8B – $6.5B | High confidence this is the floor |
| Base case | $8.1B – $10.0B | Most probable outcome |
| Bull case | $9.75B – $12.0B | Achievable only under optimal conditions |
| Claim ($12B) | Requires 750K units + $16K blended ASP | Low-to-medium probability |

**Overall Step 3 Conclusion:**
The $12B claim is physically achievable on paper but requires every variable to land at its optimistic extreme simultaneously — full production, full yield resolution, HBM supply secured, and all units sold at hyperscale cluster pricing. The most probable revenue outcome based on this model is **$8–10B** — still a significant achievement, but meaningfully below the headline claim. The ByteDance anchor gives the demand side credibility; the HBM supply constraint is the single variable most likely to prevent the bull case from materialising.

---

## Step 4 — Competitor Cross-Validation: Nvidia China P&L

**Objective:** Use Nvidia's publicly reported China revenue — the cleanest data in this entire analysis — to cross-validate whether the scale of Huawei's claimed gains is consistent with the scale of Nvidia's confirmed losses. If the numbers don't add up across both sides, something is wrong with one of them.

---

### 4.1 — Nvidia China Revenue: Quarterly Breakdown (FY2026)

All figures from Nvidia official earnings releases (SEC filings).

| Quarter | Period Ended | Total Revenue | China Data Center Revenue | Notes |
|---|---|---|---|---|
| Q1 FY2026 | Apr 27, 2025 | $44.1B | ~$4.6B (H20) then blocked | $4.5B inventory charge taken; $2.5B additional couldn't ship |
| Q2 FY2026 | Jul 27, 2025 | $46.7B | ~$0 (estimated) | H20 sales fully blocked; ~$8B revenue impact disclosed |
| Q3 FY2026 | Oct 26, 2025 | $57.0B | **~$50M** | Confirmed near-zero; described as "essentially nothing" |
| Q4 FY2026 | Jan 25, 2026 | $68.1B | Not disclosed | Forward guidance: zero China data center assumed |
| **FY2026 Full Year** | | **$215.9B** | **Approaching zero** | China dropped from ~20–25% to ~9% of revenue |

**Executive admissions (on record):**
- Jensen Huang: Nvidia's leading-edge chip share in China "has collapsed to 0%"
- CFO: "Yet to generate any revenue" from China H200 sales as of March 2026
- Nvidia stated it is **not assuming any data center revenue from China** in forward guidance

**Inventory charge context:** The $4.5B Q1 FY2026 charge represents H20 chips manufactured but unable to be shipped — this is a direct, audited dollar figure attached to the China exit. It's one of the most concrete financial consequences of the policy in any public filing.

---

### 4.2 — The Scale of the Market Vacuum

The critical question for cross-validation: how large is the revenue space Nvidia left behind?

**Pre-restriction baseline:**
- China historically accounted for ~20–25% of Nvidia's data center revenue
- At Q4 FY2026 data center run rate of $62.3B/quarter → annualised $249B
- 20–25% China share would imply **$50–62B in annual China data center revenue** at full-run unrestricted access

That figure is far larger than $12B — meaning the market space Nvidia vacated is more than sufficient to accommodate Huawei's entire claimed gain multiple times over. The demand vacuum is not the constraint. The constraint is domestic supply (manufacturing, HBM, yield) as identified in Step 3.

**More realistic pre-restriction baseline (using FY2025 actuals):**
- FY2025 total revenue: $130.5B; data center: ~85% = ~$111B
- China at 20–25%: **~$22–28B annual** at FY2025 run rates
- Still far larger than the $12B Huawei target

**Finding:** The supply vacuum Nvidia left is 2–3× the size of Huawei's claimed revenue target. From a market-opportunity standpoint, $12B is entirely plausible — the constraint is Huawei's own manufacturing capacity, not available demand.

---

### 4.3 — China Market Share: What the Numbers Actually Show

| Period | Nvidia China AI Chip Share | Domestic Chips Share | Source |
|---|---|---|---|
| Pre-sanction peak | ~95% | ~5% | Jensen Huang / analyst consensus |
| 2024 | ~66% | ~34% | Bernstein estimate |
| 2025 | ~55% | ~41% | Multiple market research firms |
| 2026 (projection) | ~8% | ~85%+ | Bernstein / Bernstein analyst projection |

**Total China AI chip units in 2025:** ~4 million units delivered across all vendors
- Nvidia: 55% → ~2.2M units
- Chinese domestic (all vendors): 41% → ~1.65M units delivered
- **Huawei specifically: ~812,000 AI chips shipped in 2025** (across all Ascend variants)

This 812,000-unit figure for 2025 is a critical new data point — it's a **real baseline**, not an anonymous projection.

---

### 4.4 — The 2025 Baseline Reconciliation (Key Finding)

Step 1 flagged the $7.5B 2025 baseline as the weakest link — anonymous, unverified, the foundation of the entire 60% claim. Step 4 provides a way to partially validate it from a completely independent angle.

**Approach:** Use Huawei's actual 2025 unit shipments to back-calculate implied revenue and compare against the claimed $7.5B.

```
Huawei 2025 Ascend shipments:    ~812,000 units (across all variants)
Older model blended ASP:         ~$9,000–$10,000 (Ascend 910B/C, lower than 950PR)
Implied 2025 revenue:            $7.3B – $8.1B
Claimed 2025 baseline (FT):      $7.5B
```

**Result: Near-exact match.** The $7.5B anonymous figure is consistent with what the unit-volume data implies when using appropriate ASPs for 2025-era Ascend chips. This does not prove the figure is correct — but it removes the "obviously wrong" risk from Step 1.

This is what triangulation is designed to do: corroborate figures that can't be verified directly by approaching them from a different direction. The $7.5B now has a plausible unit-level explanation behind it.

---

### 4.5 — The H200 Re-entry Complication

In late February 2026, the US Commerce Department granted licenses allowing some H200 chip sales to China — a partial policy reversal that complicates the clean "Nvidia exits, Huawei fills the gap" narrative.

**What happened:**
- 400,000 H200 chips approved for sale to China's top AI firms
- Subject to a 25% revenue-sharing requirement with the US Treasury (unprecedented condition)
- Mass shipment of ~82,000 H200 units reported as being prepared

**Why this doesn't meaningfully change the analysis:**
- As of March 2026, Nvidia CFO confirmed zero H200 China revenue had been generated
- Beijing has not formally granted import approval — domestic chip preference policy remains active
- Chinese tech firms that have already committed capex to Huawei Ascend ($5.6B ByteDance, etc.) face switching costs
- The 25% revenue tax makes H200 economics worse vs. the already cost-competitive Ascend 950PR
- The Diplomat noted: *"Beijing isn't giving up on Huawei"* even as H200 re-entry begins

**Net effect on Huawei's $12B target:** Minimal in 2026. H200 re-entry may apply more competitive pressure in 2027 and beyond, but committed orders, domestic policy preference, and switching costs insulate Huawei's 2026 order book.

---

### 4.6 — Revenue Transfer Accounting

Can we account for where Nvidia's lost China revenue went?

**Nvidia China revenue lost in FY2026:** ~$10–15B (estimated based on historical 20–25% share at current run rates, minus near-zero actual)

**Known domestic chip revenue absorption:**
- Huawei: ~$7.3–8.1B implied (2025 actuals) → targeting $12B (2026)
- Cambricon, Biren, Hygon: remaining ~20% domestic share → ~$4–5B combined (rough estimate)
- **Total domestic absorption: ~$11–13B in 2025**, growing toward $20B+ in 2026

**Finding:** The domestic chip industry appears to be absorbing Nvidia's retreat almost entirely — not through stockpiling or reduced AI investment, but through direct substitution. The Chinese tech giants maintained or increased their AI infrastructure capex; they simply redirected it domestically. This fully supports the demand-side credibility of Huawei's order book.

---

### Step 4 — Summary

| Cross-Validation Check | Result | Implication |
|---|---|---|
| Nvidia China collapse confirmed | ✅ $50M Q3 data center; zero forward guidance | Supply vacuum is real and quantified |
| Scale of vacuum vs. $12B claim | ✅ Vacuum is 2–3× larger than $12B | Demand is not the constraint |
| Market share shift (Nvidia → domestic) | ✅ 95% → 55% confirmed; 41% domestic in 2025 | Directional shift unambiguous |
| $7.5B 2025 baseline plausibility | ✅ 812K units × ~$9K ASP = $7.3–8.1B | Anonymous figure now has unit-level support |
| H200 re-entry risk to 2026 | ⚠️ Partial — 400K approved but no revenue yet | Low risk to 2026 order book; higher risk 2027+ |
| Domestic revenue absorption | ✅ Broadly accounts for Nvidia's exit | Substitution, not reduction, in AI spend |

**Overall Step 4 Conclusion:**
Nvidia's publicly reported numbers provide the strongest independent validation of this analysis. The scale of the market vacuum (2–3× Huawei's target), the confirmed market share shift, and the 2025 unit-volume reconciliation collectively upgrade the assessment of the $12B claim from *"anonymous and unverifiable"* to *"directionally consistent with all available public data"*. The base case from Step 3 ($8–10B) remains the most probable outcome, but the upper end ($12B) now has more evidentiary support than Step 1 suggested. The critical remaining variable is the HBM supply constraint — which Step 5 will address through the DeepSeek V4 demand driver.

---

## Step 5 — DeepSeek V4 Demand Driver Stress Test

**Objective:** Determine whether DeepSeek V4 is the actual cause of Huawei's demand surge, or whether it is an accelerant layered on top of a structural shift already in motion. If V4 is the cause, the $12B claim is contingent on sustained V4 adoption. If V4 is an accelerant, the claim stands on its own structural foundation regardless of V4's trajectory.

---

### 5.1 — Q1: Causation vs. Correlation — Was the Surge Already Underway?

**Verdict: V4 is an accelerant, not the cause**

The timeline is unambiguous:
- **March 2026:** Mass production of the Ascend 950PR begins — *six weeks before V4 launched*
- **April 2026:** H20 export ban tightened, turning domestic chip procurement from "strategic preference" into "operational requirement"
- **April 24, 2026:** DeepSeek V4 launches with native Ascend support confirmed same day
- **Post-V4:** Order scramble "instantly ignites" among internet giants

The production ramp and order building were clearly in motion before V4. The H20 export ban — not V4 — was the structural trigger that made domestic chip procurement mandatory rather than optional. V4 compressed the timeline and raised the intensity of the scramble, but the order book was already forming.

**Analytical implication:** The $12B revenue claim does not depend on DeepSeek V4 being adopted at scale. The structural demand (Nvidia restrictions + government self-sufficiency mandates) would have supported a strong order book regardless. V4 likely pulled forward demand that would have materialised in H2 2026 anyway — making the *timing* of the surge V4-dependent, but not the *existence* of it.

---

### 5.2 — Q2: Inference Compute Demand — What Does Running V4 at Scale Actually Require?

**Verdict: Demand is real and large, but efficiency limits the chip count**

V4's architecture creates a nuanced demand picture:
- **Model size:** 1.6 trillion total parameters (Mixture-of-Experts architecture)
- **Active parameters per inference:** 37 billion — only ~2.3% of parameters fire per query
- **Implication:** MoE architecture is significantly more compute-efficient for inference than a dense model of equivalent capability

The ByteDance $5.6B / 350,000-unit commitment is the best available proxy for what a single hyperscale V4 operator needs — but ByteDance is also running its own "Doubao" model family alongside V4, so the 350,000 units is not pure V4 inference demand.

**Key tension:** V4's MoE design is explicitly optimised for efficiency. This is partly *why* it runs well on Ascend — the architecture was rewritten to exploit Ascend's strengths rather than compensate for its weaknesses. But efficiency per query also means fewer chips needed per million daily active users than a dense model would require, which slightly dampens the inference demand multiplier.

---

### 5.3 — Q3: HBM Supply — Has Huawei Solved the Bottleneck?

**Verdict: Partially — Huawei has a plan, but execution risk remains**

This is the most important update from Step 5, overriding the risk assessment from Step 3.

Step 3 identified HBM supply as the binding constraint — Huawei dependent on SK Hynix/Samsung, both under US export controls. The validation data reveals Huawei's response:

| Technology | Spec | Application |
|---|---|---|
| **HiBL 1.0** (Huawei in-house HBM) | 128 GB | Ascend 950PR (current) |
| **HiZQ 2.0** (next-gen) | 144 GB | Ascend 950DT (upcoming) |

Huawei is not waiting for a geopolitical resolution — it is vertically integrating memory production. This changes the HBM risk from *"externally dependent and unresolvable"* to *"internally developing but scaling is hard"*.

**What changes in the model:**
- The bull case (750K units) becomes more achievable than Step 3 assessed — the bottleneck is now a domestic manufacturing ramp problem, not a foreign supply dependency
- However: sources explicitly note that scaling domestic HBM production "is as vital and as difficult as producing logic chips themselves" — the risk has not been eliminated, only internalised
- The new wafer fab capacity coming online H2 2026 now makes more sense as part of an integrated play (logic chips + memory) rather than just a wafer capacity story

**Revised HBM risk rating:** Reduced from High to Medium. Huawei has a credible path; execution timeline is the remaining uncertainty.

---

### 5.4 — Q4: The Prior DeepSeek Effect — Is V4 Incremental or Qualitatively Different?

**Verdict: V4 is qualitatively different — the first purpose-built Ascend showcase**

This is the key distinction that separates V4 from earlier DeepSeek models:

- DeepSeek **delayed V4 by months** specifically to rewrite its architecture for native Ascend and Cambricon operation — this was not an afterthought port
- V4 is described as the **first Tier-1 model fully co-optimised for Huawei hardware** — not merely compatible, but architecturally aligned
- The cooperation between DeepSeek and Huawei began during earlier version development cycles — meaning the demand wave was building during V3/R2 development, not just at V4's launch

**What this means for the demand narrative:** V4 is not "another model that happens to run on Ascend." It is a proof-of-concept that a globally competitive AI model can be built natively on Chinese hardware, without Nvidia at any stage. That signal — more than V4's specific capabilities — is what triggered the "instant ignition" of orders. The internet giants were not just buying chips to run V4; they were responding to the confirmation that domestic chips could support frontier AI development independently.

---

### 5.5 — Q5: CUDA Compatibility — Real or Marketing?

**Verdict: Real, and more significant than initially assessed**

The CANN Next framework is not a marketing claim:
- **Architecture:** Uses SIMT (Single Instruction, Multiple Threads) programming model — a direct mirror of CUDA's core paradigm, including thread blocks and warps
- **Code migration:** Designed as "near drop-in replacements" for CUDA operators — not full compatibility, but allowing migration of millions of lines of code without complete rewrites
- **Native kernels:** Includes optimised implementations of critical operators including FlashAttention
- **Measured result:** Hardware utilisation reached **85%+ on DeepSeek V4** — a figure that compares favourably even against Nvidia's own hardware utilisation rates for comparable models

**Switching cost implication:** "Near drop-in" rather than "perfect" means some engineering effort is still required — but the barrier is now measured in weeks of migration work rather than months of architectural rebuilding. For organisations already committed to domestic chips by policy mandate, this is sufficient. For organisations freely choosing, it substantially lowers the switching cost compared to what was assumed in Step 2.

---

### 5.6 — Q6: The Counterfactual — What Does Demand Look Like Without V4?

**Verdict: High but slower — V4 pulled forward 12–18 months of demand into 2026**

Three independent structural demand drivers exist regardless of V4:

| Driver | Nature | Scale |
|---|---|---|
| Nvidia vacuum | Operational necessity — no alternative for frontier training | 2–3× Huawei's $12B target (per Step 4) |
| Government self-sufficiency mandates | Policy-enforced procurement from "Domestic Titans" | Ensures baseline demand floor regardless of commercial preference |
| Agentic commerce | New inference compute category valued at $1.7T opportunity | Adds structural demand beyond current AI workloads |

Without V4, the order book likely builds to similar levels by H2 2027 rather than H1 2026. V4 is best understood as a **demand accelerator with an 18-month pull-forward effect** — it did not create demand that would not have existed, but it concentrated it.

---

### Step 5 — Summary

| Research Question | Verdict | Impact on $12B Claim |
|---|---|---|
| V4 causation vs. correlation | V4 is accelerant; structural demand pre-exists | Claim stands without V4 — more robust than it appeared |
| Inference compute demand scale | Real and large; MoE efficiency slightly dampens multiplier | Neutral — demand is real but per-query efficiency limits amplification |
| HBM supply bottleneck | Partially resolved — Huawei developing HiBL 1.0 / HiZQ 2.0 in-house | Bull case ($12B) more achievable; risk reduced from High to Medium |
| V4 vs. prior DeepSeek models | V4 is qualitatively different — first purpose-built Ascend model | Strengthens demand narrative; not a repeating incremental pattern |
| CUDA compatibility | Real — 85%+ utilisation on V4; "near drop-in" not "perfect" | Switching costs lower than assumed; adoption barrier meaningfully reduced |
| Counterfactual without V4 | Strong structural demand remains; ~18-month pull-forward | $12B in 2026 is partly V4-dependent on timing; direction was inevitable |

**Overall Step 5 Conclusion:**
V4 is a genuine catalyst but not the foundation of the claim. The structural demand story — Nvidia's forced exit, government mandates, and the sheer scale of China's AI infrastructure investment — would have produced a strong Huawei order book regardless. V4 concentrated that demand into 2026 at higher intensity than would have occurred otherwise. The HBM bottleneck, identified as the critical risk in Step 3, is now partially mitigated by Huawei's in-house memory strategy — reducing the probability of the conservative scenario and increasing the probability of the base-to-bull case outcome.

---

## Overall Findings & Final Verdict

### How the Evidence Evolved Across 5 Steps

| Step | Starting Risk | What We Found | Verdict Shift |
|---|---|---|---|
| Step 1 | $7.5B baseline is anonymous — entire claim built on unverified foundation | Sub-claims 2–5 broadly confirmed; only baseline unverified | Claim plausible but fragile |
| Step 2 | Evidence quality asymmetry — Nvidia side solid, Huawei side Tier 3 | ByteDance $5.6B anchor identified; "computing" segment grey zone | Most credible pillar is Nvidia's confirmed exit |
| Step 3 | $12B only achievable in bull case; base case $8–10B | HBM identified as real binding constraint | Claim technically achievable but requires everything to go right |
| Step 4 | 2025 baseline ($7.5B) had no independent support | 812K units × ~$9K ASP = $7.3–8.1B — reconciles with FT figure | Baseline now has unit-level corroboration; claim materially stronger |
| Step 5 | V4 might be the critical demand driver — if V4 fails, does demand collapse? | V4 is accelerant not cause; HBM partially solved in-house; structural demand independent | Claim's structural foundation is more robust than headline suggests |

---

### Final Verdict

**Is Huawei's $12B AI chip revenue claim for 2026 credible?**

> **Yes — directionally credible, but the specific headline number represents the optimistic scenario, not the base case.**

| Scenario | Revenue | Probability (qualitative) |
|---|---|---|
| Conservative | $5–7B | Low — demand and unit data both point higher |
| **Base case** | **$8–10B** | **Most probable — consistent with unit data, market share, and HBM constraints** |
| Bull case | $10–12B | Possible — requires HiBL 1.0 scaling on schedule + full 750K shipment |
| Claim exactly ($12B) | $12B | Achievable but requires all variables at optimistic extreme simultaneously |

**What the analysis actually proved:**
- The Nvidia supply vacuum (2–3× the size of the $12B target) makes demand unambiguous ✅
- The 2025 baseline ($7.5B) is corroborated by unit-volume data despite being anonymous ✅
- The ByteDance $5.6B order alone accounts for ~47% of the target from one named buyer ✅
- HBM risk is real but Huawei has an in-house mitigation strategy ⚠️
- V4 is an accelerant that pulled forward 12–18 months of demand, not the structural cause ✅
- The $12B figure requires the bull case on both units (750K) and ASP ($16K) simultaneously ⚠️

**The honest analytical headline:**
*Huawei reaching $8–10B in AI chip revenue in 2026 is well-supported by independent data. $12B is achievable but optimistic. The 60% growth rate — while unverifiable from official filings — is consistent with everything the public data implies.*

---

## LinkedIn Post Draft

**Angle:** Business analytics case study — how to stress-test a big market claim when the primary source is anonymous

**Target audience:** Data analysts, business professionals, Indonesian tech/business community
**Tone:** Insight-driven, short, counterintuitive hook

---

A major tech company claims 60% revenue growth. The source? Anonymous.

Here's how I'd actually analyse that claim — and what five layers of data revealed.

Huawei's $12B AI chip projection for 2026 can't be verified from official filings. But triangulating from competitor earnings, unit shipment data, and named buyer commitments tells a clearer story than the headline does.

The base case the data actually supports: $8–10B. Still extraordinary. Still the biggest shift in AI hardware in a decade.

The lesson: when you can't verify a claim directly, build it from three independent directions. If they all point the same way, you have your answer.

---

*Document complete — May 4, 2026*
