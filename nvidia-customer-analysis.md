# NVIDIA Customer Concentration Analysis

## Executive summary

NVIDIA discloses customer concentration, but it does **not** name its largest direct customers in current filings. The useful approach is therefore to separate four evidence levels:

1. **SEC confirmed** — explicit NVIDIA or counterparty filing facts.
2. **Official disclosure** — company press releases, product pages, and deployment announcements.
3. **Mathematical inference** — arithmetic derived from disclosed revenue and concentration percentages.
4. **Analytical hypothesis** — mapping anonymous concentration fingerprints to likely customers such as Microsoft or AWS.

The core FY2027 H1 reconstruction is:

- Q1 revenue: **$81.615B**
- Q2 revenue: **$96.221B**
- H1 revenue: **$177.837B**
- Q1 top direct customers: **21%, 17%, 16%**
- Q2: only one direct customer was at or above 10%, at **16%**
- H1 top direct customers: **16%, 15%, 13%**

If the same three economic/direct-customer fingerprints persist across the half, the only clean mapping consistent with Q2 having a single >=10% customer is:

| Fingerprint | Q1 | H1 | Implied Q2 | Working identity |
|---|---:|---:|---:|---|
| D1 | 21% | 15% | ~9.9% | Microsoft / Azure hypothesis (~45%) |
| D2 | 17% | 13% | ~9.6% | Meta / another US CSP, unresolved |
| D3 | 16% | 16% | 16.0% | AWS hypothesis (~50%) |

This continuity is **not SEC-confirmed**. NVIDIA has explicitly warned in prior filings that letter labels such as Customer A/B/C may refer to different customers across periods.

---

## 1. What NVIDIA actually discloses

### SEC confirmed

NVIDIA's direct-customer universe includes:
- add-in-board partners and distributors,
- ODMs and OEMs,
- cloud service providers,
- AI model makers,
- system integrators.

NVIDIA also states that certain direct customers may use internal resources or third-party system integrators to complete a build.

This matters because a server can be physically assembled by Foxconn or Quanta while the invoice customer remains a US hyperscaler. Conversely, if the ODM owns the purchase order, NVIDIA may book the direct customer to Taiwan.

NVIDIA geography is based on the **headquarters of the direct customer**, and this can differ from the final end customer or shipping destination.

### Source
- NVIDIA FY27 Q2 10-Q: https://www.sec.gov/Archives/edgar/data/1045810/000104581026000075/nvda-20260726.htm
- NVIDIA FY27 Q1 10-Q: https://www.sec.gov/Archives/edgar/data/1045810/000104581026000052/nvda-20260426.htm
- NVIDIA FY26 10-K: https://www.sec.gov/Archives/edgar/data/1045810/000104581026000021/nvda-20260125.htm

---

## 2. FY27 customer-concentration math

### SEC confirmed

Revenue:
- Q1 FY27: **$81.615B**
- Q2 FY27: **$96.221B**
- H1 FY27: **$177.837B**

Customer concentration:
- Q1: **21%, 17%, 16%**
- Q2: **one direct customer at 16%**
- H1: **16%, 15%, 13%**

### Mathematical inference

Q1 anonymous-customer revenue equivalents:
- 21% = **~$17.14B**
- 17% = **~$13.87B**
- 16% = **~$13.06B**

Assuming continuity of the three largest fingerprints across H1:

**D1**
- Q1: 21% × $81.615B = **~$17.14B**
- H1: 15% × $177.837B = **~$26.68B**
- implied Q2 = ~$9.54B = **~9.9% of Q2**

**D2**
- Q1: 17% × $81.615B = **~$13.87B**
- H1: 13% × $177.837B = **~$23.12B**
- implied Q2 = ~$9.24B = **~9.6% of Q2**

**D3**
- Q1: 16% × $81.615B = **~$13.06B**
- H1: 16% × $177.837B = **~$28.45B**
- implied Q2 = ~$15.40B = **16.0% of Q2**

This is the unique clean permutation that leaves only one Q2 customer above the SEC's 10% disclosure threshold.

### Caveat

Do not reuse NVIDIA's own Customer A/B/C letters across periods as persistent identifiers. NVIDIA has explicitly disclosed that letter references may represent different customers than in prior periods.

Examples:
- FY2025 Q3 customer note: https://www.sec.gov/Archives/edgar/data/1045810/000104581024000316/R21.htm
- FY2026 Q3 10-Q: https://www.sec.gov/Archives/edgar/data/1045810/000104581025000230/nvda-20251026.htm

Therefore D1/D2/D3 are our own analytical fingerprints, not NVIDIA labels.

---

## 3. Geography elimination logic

### SEC confirmed

Q1 FY27 geography:
- US: **$63.769B**
- Taiwan: **$12.006B**
- China/HK: **$4.550B**
- Other: **$1.290B**

Source:
https://www.sec.gov/Archives/edgar/data/1045810/000104581026000052/R20.htm

### Mathematical inference

Each Q1 top-customer amount:
- D1 ~ $17.14B
- D2 ~ $13.87B
- D3 ~ $13.06B

Each exceeds **all Q1 Taiwan-headquartered revenue of $12.006B**.

Therefore none of the three largest Q1 direct customers can individually be a Taiwan-headquartered customer if the concentration amount and geographic classification refer to the same booking basis. China/HK and Other are even smaller.

The strongest geography conclusion is that the Q1 top-three direct customers were overwhelmingly likely to be **US-headquartered direct customers**.

### Q2 route shift

Q2 geography:
- US: **$60.074B**
- Taiwan: **$26.985B**
- China/HK: **$7.880B**
- Other: **$1.282B**

Taiwan therefore rose by roughly **$14.98B q/q**, while total company revenue rose by roughly **$14.61B**, and US revenue declined.

Interpretation: Q2 may have included a substantial booking/procurement-route shift toward Taiwan-headquartered direct customers or ODM entities, even while the economic end demand remained heavily US-driven.

This is an **interpretation**, not a disclosed causal explanation.

---

## 4. Accounts receivable cross-check

### SEC confirmed

Q1 total AR: **$40.710B**

Largest direct customers represented:
- 30%
- 18%
- 16%

Approximate AR equivalents:
- ~$12.21B
- ~$7.33B
- ~$6.51B

Q2 total AR: **$63.059B**, up roughly **55% q/q**.

Top five direct customers represented:
- 22%
- 14%
- 13%
- 11%
- 10%

Approximate AR equivalents:
- ~$13.87B
- ~$8.83B
- ~$8.20B
- ~$6.94B
- ~$6.31B

Top five combined = **70% of AR**.

Source:
https://www.sec.gov/Archives/edgar/data/1045810/000104581026000075/R14.htm

### Interpretation

AR grew much faster than revenue. That is consistent with a heavier late-quarter shipment or acceptance mix, though it does not prove one.

Do **not** mechanically map revenue rank to AR rank. Billing timing, shipment timing, payment terms, and acceptance all distort the ranking.

---

## 5. Candidate: Microsoft

### Counterparty SEC evidence

Microsoft disclosed:
- servers/network/software gross PP&E of **$190.883B** at Mar. 31, 2026 vs **$171.351B** at Dec. 31, 2025
- **+$19.532B q/q**
- at Jun. 30, 2026, servers/network/software gross PP&E of **$215.874B**
- PP&E purchases remaining in accounts payable:
  - Mar. 31, 2026: **$22.6B**
  - Jun. 30, 2026: **$26.7B**
- Jun. 30 commitments of **$34.6B** for construction/building improvements/leaseholds, primarily datacenters

Sources:
- https://www.sec.gov/Archives/edgar/data/789019/000119312526191507/msft-20260331.htm
- https://www.sec.gov/Archives/edgar/data/789019/000119312526323660/msft-20260630.htm

### Official NVIDIA / Microsoft evidence

NVIDIA announced Microsoft deployments of more than **100,000 Blackwell Ultra GPUs in GB300 NVL72 systems** globally.

Sources:
- https://blogs.nvidia.com/blog/nvidia-microsoft-ai-superfactories/
- https://azure.microsoft.com/en-us/blog/microsoft-azure-delivers-the-first-large-scale-cluster-with-nvidia-gb300-nvl72-for-openai-workloads/

### Analytical hypothesis

Microsoft is the best current candidate for **D1**:
- D1 Q1 revenue equivalent ~ **$17.1B**
- D1 appears front-loaded in Q1 and then falls just below 10% in Q2
- Microsoft's infrastructure additions and NVIDIA deployment scale are directionally compatible
- Azure also carries large OpenAI-related demand

Working confidence: **~45%**

Not SEC-confirmed.

---

## 6. Candidate: AWS

### Counterparty SEC evidence

Amazon disclosed:
- Q1 2026 cash capex: **$43.2B**
- Q2 cash capex: **$53.1B**
- H1 cash capex: **$96.3B**
- majority of technology-infrastructure investment supports AWS
- Q1 AWS PP&E net additions: **$41.516B**
- Q1 consolidated PP&E additions: **$54.757B**
- increase in PP&E acquired but not yet paid:
  - Q1: **$9.920B**
  - Q2 incremental: **$10.700B**
  - H1: **$20.620B**

Sources:
- https://www.sec.gov/Archives/edgar/data/1018724/000101872426000014/amzn-20260331.htm
- https://www.sec.gov/Archives/edgar/data/1018724/000101872426000026/amzn-20260630.htm

### Official NVIDIA / AWS evidence

AWS announced plans to add more than **1 million NVIDIA GPUs starting in 2026**, followed by an additional **2 million Blackwell Ultra / Rubin / Rubin Ultra GPUs in 2027-2028**.

Sources:
- https://investor.nvidia.com/news/press-release-details/2026/AWS-and-NVIDIA-to-Deliver-2-Million-Additional-GPUs-and-Next-Generation-Infrastructure-for-Agentic-and-Physical-AI/default.aspx
- https://aws.amazon.com/nvidia/project-ceiba/

### Analytical hypothesis

AWS is the best current candidate for **D3**:
- D3 is the most stable fingerprint: roughly $13.1B in Q1 → $15.4B in Q2
- H1 concentration remains at 16%
- AWS has the strongest official forward physical-deployment evidence among hyperscalers

Working confidence: **~50%**

AWS also deploys Trainium, so NVIDIA is not its only accelerator path.

---

## 7. Candidate: Meta

### Counterparty SEC evidence

Meta disclosed:
- Q1 PP&E purchases: **$19.0B**
- Q2 capex including finance leases: **$31.08B**
- H1 PP&E purchases: **$49.11B**
- 2026 capex forecast: roughly **$130B-$145B**
- unpaid PP&E:
  - Mar. 31: **$16.040B**
  - Jun. 30: **$19.502B**
- servers/network assets:
  - Dec. 2025: **$98.040B**
  - Jun. 2026: **$119.683B**
- construction in progress:
  - **$50.521B → $80.345B**
- contractual commitments:
  - Mar. 2026: **$237.67B**
  - Jun. 2026: **$349.31B**

Sources:
- https://www.sec.gov/Archives/edgar/data/1326801/000162828026028526/meta-20260331.htm
- https://www.sec.gov/Archives/edgar/data/1326801/000162828026050705/meta-20260630.htm

### Official NVIDIA evidence

NVIDIA described a Meta partnership involving **millions of Blackwell and Rubin GPUs**, NVIDIA CPUs, and Spectrum-X.

Source:
https://nvidianews.nvidia.com/news/meta-builds-ai-infrastructure-with-nvidia

### Why Meta is harder to map

Meta's economic NVIDIA exposure can be split across:
- direct hardware procurement,
- ODM procurement,
- third-party clouds such as CoreWeave,
- other AI-cloud arrangements,
- custom silicon such as MTIA,
- non-NVIDIA accelerators.

Therefore Meta may be a massive **economic customer** without appearing as one clean direct-customer fingerprint.

D2 remains the most plausible slot, but current confidence is lower than for D1/Microsoft or D3/AWS.

---

## 8. Alphabet / Google

### SEC confirmed counterparty evidence

Alphabet disclosed:
- Q1 capex: **$35.7B**
- H1 capex: **$80.6B**
- implied Q2 capex: ~**$44.9B**
- 2026 capex around **$180B**

Sources:
- https://www.sec.gov/Archives/edgar/data/1652044/000165204426000048/goog-20260331.htm
- https://www.sec.gov/Archives/edgar/data/1652044/000165204426000071/goog-20260630.htm

Google clearly buys NVIDIA GPUs, but its heavy TPU usage lowers the probability that it explains one of the very largest NVIDIA direct-customer fingerprints.

---

## 9. Oracle

### SEC / company evidence

Oracle disclosed:
- first nine months FY26 capex: **$39.17B**
- trailing-four-quarter capex: **$48.25B**
- FY26 Q4 RPO: **$638B**, up 363% YoY
- some AI contracts involved the customer prepaying Oracle for GPU purchases or supplying GPUs to Oracle
- prepaid/customer-supplied hardware portions totaled roughly **$75B**

Sources:
- https://www.sec.gov/Archives/edgar/data/1341439/000119312526101045/orcl-20260228.htm
- https://www.sec.gov/Archives/edgar/data/1341439/000119312526265848/orcl-ex99_1.htm

### Interpretation

Oracle can have huge NVIDIA **economic exposure** while the direct GPU invoice may sit with Oracle's customer or another procurement entity. That makes Oracle a weaker candidate for a single top NVIDIA direct-customer identity.

---

## 10. CoreWeave

### SEC confirmed

CoreWeave states that all GPUs used in its platform are NVIDIA GPUs.

Its 2025 supplier mix included three suppliers representing approximately **23%, 20%, and 17%** of purchases, with NVIDIA specifically identified at roughly **17%** in an earlier filing.

Sources:
- https://www.sec.gov/Archives/edgar/data/1769628/000176962826000191/crwv-20260422.htm
- https://www.sec.gov/Archives/edgar/data/1769628/000176962826000366/crwv-20260630.htm
- https://www.sec.gov/Archives/edgar/data/1769628/000176962826000044/crwv-20260123.htm

### Interpretation

CoreWeave is strategically important but its scale makes it unlikely to explain a NVIDIA direct-customer fingerprint worth roughly **$13B-$17B per quarter**.

---

## 11. ODM and procurement-route framework

The key mistake is to treat “who physically builds the server” as the same thing as “who NVIDIA recognizes as the customer.”

Keep these four identities separate:

1. **NVIDIA invoice customer** — entity on the NVIDIA PO/invoice.
2. **GPU economic owner** — entity ultimately funding the hardware.
3. **ODM/system assembler** — Foxconn, Quanta, Wistron, Wiwynn, etc.
4. **Compute consumer** — OpenAI, Anthropic, xAI, enterprise users, public sector, etc.

Example:

> NVIDIA GPU → Foxconn assembly → Microsoft datacenter → OpenAI workload

Possible booking outcomes:
- Microsoft owns the NVIDIA PO → US direct customer.
- Foxconn owns the NVIDIA PO → Taiwan direct customer.
- another integrator owns the PO → geography follows that integrator's HQ.

This framework explains why economic demand and NVIDIA's reported direct-customer geography can diverge sharply.

### Official NVIDIA supplier / builder evidence

NVIDIA has disclosed or officially referenced:
- foundries: TSMC, Samsung
- memory: SK hynix, Micron, Samsung
- contract manufacturing / integration relationships including Hon Hai/Foxconn, Wistron, Fabrinet
- system-builder ecosystem including Dell, HPE, Lenovo, Supermicro, ASUS, Foxconn, GIGABYTE, Pegatron, QCT, Wistron, Wiwynn, and others

Sources:
- https://www.sec.gov/Archives/edgar/data/1045810/000104581025000023/nvda-20250126.htm
- https://nvidianews.nvidia.com/news/dsx-infrastructure-ai-factory
- https://nvidianews.nvidia.com/news/nvidia-launches-vera-cpu-purpose-built-for-agentic-ai
- https://www.nvidia.com/en-us/made-in-usa/

---

## 12. Working ranking

| Candidate | Direct-customer fit | Evidence | Current view |
|---|---|---|---|
| Microsoft | High | large PP&E additions, >100k GB300 deployment, Azure/OpenAI demand | Best fit for D1, ~45% |
| AWS | High | largest forward NVIDIA GPU deployment evidence, massive AWS infra spend | Best fit for D3, ~50% |
| Meta | Medium-High economic / Medium direct | enormous capex + millions of GPUs, but route fragmented | plausible D2, unresolved |
| Google | Medium | huge capex, but TPU-heavy | lower top-direct probability |
| Oracle | Medium economic / Low-Medium direct | huge AI infra commitments, but customer-prepaid/supplied GPUs | weak direct mapping |
| CoreWeave | High NVIDIA dependency / lower scale | 100% NVIDIA GPU fleet | unlikely $13B-$17B/qtr direct customer |

---

## 13. What is not proven

The following should **not** be presented as confirmed facts:

- “Customer A = Microsoft” or any persistent A/B/C mapping.
- “D3 is definitely AWS.”
- “The Q2 16% customer is AWS.”
- “OpenAI is NVIDIA's named Q2 AI research/deployment customer.”
- “Taiwan revenue equals Foxconn/Quanta demand.”
- “Meta's total AI capex flows directly to NVIDIA.”

These remain hypotheses until one of the parties names the counterparty, a filing exposes a sufficient concentration relationship, or another hard disclosure closes the loop.

---

## 14. Bottom line

The strongest current reconstruction is:

- **D1**: front-loaded Q1 customer, 21% → implied Q2 9.9%; **Microsoft is the leading candidate**.
- **D2**: 17% → implied Q2 9.6%; **Meta or another large US CSP/procurement entity**, unresolved.
- **D3**: steady 16% in both quarters; **AWS is the leading candidate**.

The highest-confidence conclusion is not the identity mapping itself. It is the **method**:

> combine NVIDIA concentration math + geography constraints + counterparty capex / PP&E / unpaid equipment + official GPU deployment disclosures + procurement-route structure.

That produces a useful customer map while preserving a strict line between **SEC fact** and **analytical hypothesis**.
