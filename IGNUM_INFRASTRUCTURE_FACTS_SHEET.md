# IGNUM Infrastructure Facts Sheet v1.0
**Status:** Draft canónico estructural  
**Date:** 2026-03-25  
**Purpose:** Control factual — qué puede declararse, cuándo y con qué wording exacto  
**Rule:** Todo claim público futuro debe mapearse a un campo de este documento  

---

## Validation States

| State | Meaning |
|-------|---------|
| ✅ Verified / Public | Puede salir en web, deck, materiales |
| 🔒 Verified / Private | Cierto, pero no publicable aún |
| ⏳ Pending Verification | Probable, no usar hasta confirmar |
| ❌ Not Approved | No sale aunque sea cierto |

---

## 1. Asset Identity

| Field | Value | State |
|-------|-------|-------|
| Public brand name | IGNUM | ✅ Verified / Public |
| Extended name | IGNUM Protocol | ✅ Verified / Public |
| Legal entity | IGNUM Protocol SAPI de CV | ✅ Footer/legal only |
| Category | Sovereign Intelligence Infrastructure Platform | ✅ Verified / Public |
| Regional scope | Latin America | ✅ Verified / Public |
| Primary descriptor | Sovereign Intelligence Infrastructure for Latin America | ✅ Verified / Public |
| Operating status (detail) | Pre-canonical factual consolidation | ⏳ Pending |

---

## 2. Physical Infrastructure

| Field | Reference | State |
|-------|-----------|-------|
| Location | Parque Industrial Cuadritos, Celaya, Guanajuato | ⏳ Pending public wording |
| Total park | ~45 ha | ⏳ Pending Verification |
| Available footprint | ~29.5 ha | ⏳ Pending Verification |
| Initial data hall concept | ~15,000 m² | ⏳ Pending Verification |

**Approved interim wording (public):**
> IGNUM is being developed around a controlled industrial infrastructure context in central Mexico, designed for long-horizon AI deployment and strategic expansion.

---

## 3. Power Infrastructure

| Field | Reference | State |
|-------|-----------|-------|
| Generation thesis | Energy-first infrastructure model | ✅ Verified / Public |
| On-site generation | 7.3 MW cogeneration | ⏳ Pending Verification |
| Generation technology | 2× Jenbacher J620, 3.65 MW each | ⏳ Pending Verification |
| Expansion potential | Up to ~100 MW long-term | ⏳ Pending — qualifier required |
| Substation | 20 MVA | ⏳ Pending Verification |
| Gas pipeline | ~25 km private | ⏳ Pending / Private |
| Power pricing (numeric) | $0.038–0.045 USD/kWh | 🔒 Private — deck/data room only |
| Power pricing (thesis) | Lower-cost vs external dependency | ✅ Verified / Public (no number) |

**Approved public wording:**
> IGNUM is designed around an energy-first infrastructure strategy intended to improve control, resilience, and long-term operating economics.

---

## 4. Cooling / Thermal

| Field | Reference | State |
|-------|-----------|-------|
| Cooling thesis | Integrated energy + cooling logic | ✅ Verified / Public |
| Trigeneration / CHP | Referenced in materials | ⏳ Pending Engineering confirmation |
| Chilled water systems | Referenced | ⏳ Pending / Private |

**Approved public wording:**
> IGNUM's infrastructure model contemplates integrated energy and cooling logic aligned with long-term compute efficiency.

---

## 5. Water / Utility

| Field | Reference | State |
|-------|-----------|-------|
| Industrial wells | 3 wells referenced | ⏳ Pending Verification |
| Water treatment | PTAR ~1,500 m³/day | ⏳ Pending Verification |

**Approved public wording:**
> IGNUM is being structured with infrastructure resilience in mind, including utility continuity as part of long-horizon operations design.

---

## 6. Connectivity

| Field | Reference | State |
|-------|-----------|-------|
| Connectivity thesis | Regional execution + interconnection strategy | ✅ Verified / Public |
| Latency QRO | 5–12 ms (Feb 2026 reference) | ⏳ Pending documented test |
| Latency CDMX | 18–28 ms (Feb 2026 reference) | ⏳ Pending documented test |
| Latency Dallas | 42–55 ms (Feb 2026 reference) | ⏳ Pending documented test |
| Dark fiber / IRU | Conceptual / under evaluation | ❌ Do not publish |
| Target with dark fiber | <2 ms to QRO | ❌ Do not publish — planned only |

**Approved public wording:**
> IGNUM is positioned with regional execution and interconnection strategy in mind, supporting sovereign deployment across Latin America.

---

## 7. Compute Layer

| Field | Reference | State |
|-------|-----------|-------|
| Compute thesis | Private AI training, inference, model operations | ✅ Verified / Public |
| H200 SXM5 141GB HBM3e | 4 units acquired | ⏳ Pending — "deploying" only |
| GPU counts public | Any number | ❌ Not approved until inventory locked |
| Readiness | Deploying / deployment in progress | ✅ "deploying" is the correct term |
| "Live" / "operational" for H200 | Any claim | ❌ NOT approved — not yet deployed |

**Approved public wording:**
> 4× NVIDIA H200 SXM5 141GB HBM3e — deployment in progress

**Canonical rule:** No GPU counts, cluster counts, or "operational" claims until asset lock.

---

## 8. Service Lines

| Service | State |
|---------|-------|
| Dedicated AI Infrastructure | ✅ Verified / Public |
| Private Inference Environments | ✅ Verified / Public |
| Custom Model Deployment | ✅ Verified / Public |
| Private Training Environments | ✅ Verified / Public |
| Sovereign Stack Advisory | ✅ Verified / Public |

**Do NOT claim publicly:**
- Mass-market GPU rental
- Commodity cloud replacement at scale
- Unrestricted public marketplace access

---

## 9. Security / Control Posture

| Phrase | State |
|--------|-------|
| "Controlled environments" | ✅ Approved |
| "Operational discipline" | ✅ Approved |
| "Protected deployment pathways" | ✅ Approved |
| "Privacy-oriented infrastructure posture" | ✅ Approved |
| "Fully secure" | ❌ Prohibited — too absolute |
| "Military-grade" | ❌ Prohibited — no audit basis |
| "Institutional-grade" | ❌ Prohibited — until defined internally |
| "Unhackable" | ❌ Prohibited |

---

## 10. Deployment Stage

| Stage label | State |
|-------------|-------|
| "Being structured / developed" | ✅ Approved |
| "Long-horizon platform" | ✅ Approved |
| "Fully operational" | ❌ Forbidden until confirmed |
| "Now live at scale" | ❌ Forbidden |
| "Active production cluster" | ❌ Forbidden until confirmed |
| "Enterprise-ready now" | ❌ Forbidden until confirmed |

**Approved interim public wording:**
> IGNUM is being structured as a long-horizon sovereign AI infrastructure platform for Latin America.

---

## 11. Public Claims Registry (Summary)

### ✅ Publish now
- Sovereign intelligence infrastructure
- Private AI environments
- Controlled deployment
- Secure inference environments
- Custom model operations
- Sovereign stack advisory
- Latin America regional focus
- Energy-first thesis
- Infrastructure for organizations that cannot outsource control

### 🔒 Private only — data room / deck
- Exact energy capacity numbers
- PPA pricing target ($0.038–0.045/kWh)
- DSCR / IRR / EBITDA projections
- Cap table
- Exact land area
- Exact utility structure
- Exact GPU inventory count

### ⏳ Conditional — publish after source verification
- City / site naming (Celaya / Cuadritos)
- MW references (7.3 MW)
- Substation reference (20 MVA)
- Park footprint (15,000 m² / 45 ha)
- Latency references (5–12 ms / 18–28 ms / 42–55 ms)

---

## 12. Required Evidence Pack (to close to v1.1)

These 7 documents are needed to make this sheet canonical v1.1:

1. Site control / site rights summary
2. Power infrastructure documentation (Jenbacher spec, MW confirmed)
3. Utility and cooling documentation
4. Interconnection / telecom reference (if for disclosure)
5. Hardware / compute inventory policy (H200 count + status)
6. Disclosure policy signed internally
7. Approved stage-of-development language (locked)

**Without these 7, any technical public statement remains structurally fragile.**

---

## 13. Canonical Boilerplate (Approved)

**Full institutional version:**
> IGNUM is a sovereign intelligence infrastructure platform for Latin America, built for organizations that require private AI environments, controlled deployment, and long-term strategic control.

**Site-safe infrastructure version:**
> IGNUM provides private AI infrastructure pathways, secure inference environments, and controlled model deployment for institutions, enterprises, private capital, and industrial groups operating in Latin America.

**Short version:**
> Infrastructure for organizations that cannot outsource intelligence control.

---

## 14. Red Flags (How IGNUM breaks trust publicly)

1. **Over-specificity before evidence** — Publishing MW, latency, acreage, GPU counts without locked evidence
2. **Category drift** — Sounding like GPU rental, AI agency, crypto brand, or abstract manifesto
3. **Visual overclaim** — Site that looks more operationally mature than facts permit
4. **Language inflation** — "First", "largest", "fully operational", "institutional-grade" without factual defense

---

## Version History

| Version | Date | Change |
|---------|------|--------|
| v1.0 | 2026-03-25 | Draft canónico estructural — Heptagon + Tommy |
| v1.1 | Pending | Close after 7-document evidence pack |

---

*Next document: IGNUM Public Claims Registry v1.0 — line-by-line approved wording*  
*This document does not replace legal counsel review for investor or institutional materials.*
