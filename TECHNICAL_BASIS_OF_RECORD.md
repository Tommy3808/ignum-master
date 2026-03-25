# IGNUM Protocol — Technical Basis of Record v1.0
**Status:** CANONICAL · Supersedes all prior documents  
**Date:** 2026-03-24  
**Authority:** Tommy Macías, TPWR Holdings

---

## ⚠️ Deprecated Documents

The following documents are **deprecated** and must not be cited in public materials, investor decks, or the website:

- `003_IGNUM_BAJÍO v1-v4` (pre-2026-03-01) — references 4 MW Jenbacher and 50–70 kW mining farm
- Any document referencing "planta Jenbacher 4 MW" as current capacity
- Any document referencing "50–70 kW excedentes para granja inicial" as the compute model

**Canonical source:** JSON v5.0 Master Backup (2026-02-21, Gemini session), confirmed by Tommy Macías 2026-03-17.

---

## 1. Energy Infrastructure — Canonical Numbers

| Parameter | Value | Status |
|-----------|-------|--------|
| On-site generation installed | **7.3 MW** | Operating today |
| Generation technology | Cogeneration (gas) | Operating today |
| Private gas pipeline | 25 km | In place |
| Grid substation | 20 MVA | In place |
| Industrial wells | 3 wells | In place |
| Water treatment | PTAR 1,500 m³/day | In place |
| Energy cost | $0.038–0.045 USD/kWh | Internal blended |
| Campus footprint Phase 1 | 15,000 m² | Available |
| Total campus potential | 45 hectares | Available |
| Long-term generation potential | 100 MW | Expansion |

---

## 2. IT Capacity — Canonical Roadmap

| Phase | IT Capacity | Generation | Timeline |
|-------|-------------|------------|----------|
| Phase 1 (current) | **2 MW IT** | 7.3 MW gen. | 2026 |
| Phase 2 | 8 MW IT | ~15 MW gen. | 2026–2027 |
| Phase 3 | 15 MW IT | ~30 MW gen. | 2027–2028 |
| Long-term | Full campus | 100 MW | 2030+ |

**Note:** "2 MW IT Phase 1" = compute power delivered to IT load. Distinct from 7.3 MW total generation.

---

## 3. Hardware — H200 Status

| Parameter | Value | Wording |
|-----------|-------|---------|
| GPU model | NVIDIA H200 SXM5 | Confirmed |
| GPU memory | 141 GB HBM3e | Confirmed |
| Quantity | **4× units** | Acquired · deploying Phase 1 |
| Physical status | **Acquired — deployment in progress** | Use: "DEPLOYING" |
| Certification target | NVIDIA DGX-Ready | In process |

**Exact wording for public materials:**
> "NVIDIA H200 SXM5 141GB HBM3e — hardware acquired, deployment in progress"

**Do NOT say:** "4 GPUs online", "live", "operational H200s"  
**DO say:** "H200 SXM5 141GB HBM3e · Deploying"

---

## 4. Connectivity — Canonical Numbers

| Route | Latency | Status |
|-------|---------|--------|
| Celaya → Querétaro | 5–12 ms | Measured Feb 2026 |
| Celaya → CDMX (NAPs) | 18–28 ms | Measured Feb 2026 |
| Celaya → Dallas (DFW) | 42–55 ms | Measured Feb 2026 |
| With IRU dark fiber → QRO | <2 ms | **Target / under evaluation** |

**Exact wording for connectivity:**
- Measured latencies: use as stated above — "measured Feb 2026"
- Dark fiber: "dark fiber / IRU path under evaluation" — NOT "planned" or "confirmed"

---

## 5. Pricing — Base Case 2026

| Tier | $/kW-mes | Includes |
|------|----------|---------|
| Industrial Tier III-light | $145–160 | Energy + CaaS + SLA |
| HPC Premium liquid-ready | $165–195 | Liquid loop + NVIDIA-ready + low latency |
| Anchor 400–600 kW | Negotiated | + 2-month deposit |

**These are base case numbers — actual pricing is commercial negotiation.**

---

## 6. Corporate Structure — Canonical

```
Holding Familiar (Héctor) ──► activos físicos 100%
    │
    ├── EnergyCore Owner ──► PPA 15yr + CaaS
    │
    ├── SPV Operativo (SAPI) ──► colocation + compute
    │
    └── HoldCo Delaware (optional) ──► institutional capital
```

**Cap table (institutional round):** Héctor 35% · Tommy 35% · Seed Infra 30%  
**Note:** Cap table details go in investor data room only — NOT on public website.

---

## 7. What Goes Public vs. Private

### ✅ Public Website (ignumprotocol.ai)
- 7.3 MW installed generation today
- 2 MW IT Phase 1
- 15,000 m² Phase 1 footprint
- 45 ha campus potential
- 100 MW long-term expansion
- 25 km private gas pipeline
- 20 MVA substation
- 3 industrial wells + PTAR 1,500 m³/day
- Measured latencies (QRO/CDMX/Dallas)
- H200 SXM5 141GB HBM3e — deploying
- Pricing tiers ($145–195 /kW-mes)
- MX jurisdiction — MLAT-only, no CLOUD Act
- Corporate structure (EnergyCore / SPV / HoldCo — general)

### 🔒 Investor Data Room Only
- PPA pricing: $0.038–0.045/kWh
- DSCR / IRR / EBITDA by phase
- Cap table details
- Execution gates
- Project finance / debt + equity roadmap
- Valuation scenarios (50 MW / 100 MW)

---

## 8. Version History

| Version | Date | Change |
|---------|------|--------|
| v1.0 | 2026-03-24 | Initial canonical release — supersedes all prior |

---

*This document is the single source of truth for all public and investor communications of IGNUM Protocol.*  
*Any discrepancy with prior documents: this document prevails.*
