# Innate Immune Cells

| Field | Value |
|-------|-------|
| **Area** | innate immunity |
| **Prerequisites** | none — this is the entry point |
| **Status** | 🌿 roughly understood |
| **Updated** | 2026-09-11 |

## In one sentence

The cells that do **not** need prior acquaintance with a pathogen — they fire on
molecular patterns shared across whole classes of pathogens, within minutes to
hours.

## Why it exists

Adaptive immunity is precise, but precision is slow: a naive T or B cell has to
be found, activated, and clonally expanded, which takes **days**. Bacteria
divide on a timescale of tens of minutes. Something has to hold the line in the
meantime.

So the body keeps a system that does not ask *which* pathogen this is, only
*does this look like a pathogen at all*. It trades specificity for speed.

> **Innate immunity buys time. Adaptive immunity buys precision.**

A second job, easy to miss: innate cells are also what **starts** the adaptive
response. Without dendritic cells carrying antigen to the lymph nodes, the
adaptive arm never gets going. Innate immunity is not just a stopgap — it is the
trigger.

## Mechanism

Recognition targets conserved molecular signatures rather than a specific
antigen:

| Target | What it is |
|--------|------------|
| **PAMP** | Pathogen-Associated Molecular Pattern — molecules common to a class of pathogens and absent from host cells (bacterial cell-wall components, double-stranded RNA) |
| **DAMP** | Damage-Associated Molecular Pattern — host molecules released by injured or dying cells, which also signal that something is wrong |

Both are detected by **PRRs** (Pattern Recognition Receptors), the best-known
family being the **TLRs** (Toll-like Receptors).

```
PAMP / DAMP
     │
     ▼
   PRR on innate cell
     │
     ├──► inflammation        (recruit more cells, raise vascular permeability)
     ├──► phagocytosis        (engulf and destroy)
     ├──► direct killing      (NK cells against infected / transformed cells)
     └──► antigen presentation ──► starts the adaptive response
```

The genome encodes PRRs directly, which is why the response needs no lead time —
and also why the repertoire is fixed and cannot adapt to a novel pathogen.

## Key cells and molecules

| Cell | Chinese | Role |
|------|---------|------|
| Neutrophils | 中性粒细胞 | Fast phagocytosis and bacterial killing; most numerous, first to arrive |
| Macrophages | 巨噬细胞 | Engulf pathogens, clear cellular debris, secrete cytokines |
| Monocytes | 单核细胞 | Circulating **precursors**; differentiate into macrophages and others on entering tissue |
| Dendritic cells (DCs) | 树突状细胞 | **The bridge to adaptive immunity** — carry antigen to lymph nodes and present it to T cells |
| NK cells | 自然杀伤细胞 | Kill virus-infected and tumour cells |
| Mast cells | 肥大细胞 | Tissue-resident; inflammation and allergy |
| Eosinophils | 嗜酸性粒细胞 | Parasites and allergy |
| Basophils | 嗜碱性粒细胞 | Circulating; allergy and inflammation |

The counterpart is the **adaptive immune cells**, of which T cells and B cells
are the canonical examples.

Two supporting components belong to innate immunity but are not cells, and are
easy to forget when the topic is framed as a list of cell types:

- **Complement** — a plasma protein cascade that opsonises, recruits, and lyses
  directly. See [[complement-system]].
- **Physical and chemical barriers** — epithelium, mucus, pH, antimicrobial
  peptides. Technically the true first line, before any cell is involved.

## Innate vs adaptive

| | Speed | Specificity | Memory | Repertoire |
|---|---|---|---|---|
| **Innate** | minutes–hours | broad, pattern-level | largely none | germline-encoded, fixed |
| **Adaptive** | days | high, antigen-level | **yes** | somatically generated, vast |

## Easily confused with

- **Monocyte vs macrophage** — not two parallel cell types but **two stages of
  one lineage**: monocytes circulate in blood, and differentiate into
  macrophages after entering tissue. "Monocyte-derived macrophage" is not a
  third thing. Note also that many tissue macrophages are *not* monocyte-derived
  at all — they seed during embryonic development and self-renew in place.
- **NK cells look like lymphocytes but are innate.** Lymphocyte morphology does
  not imply adaptive immunity. The criterion is the **mode of recognition**
  (germline-encoded pattern receptors vs somatically rearranged antigen
  receptors), not appearance.
- **Mast cells / basophils / eosinophils** all touch allergy and blur together.
  Rough split: mast cells are **tissue-resident**, basophils **circulate**,
  eosinophils lean toward **parasites**.
- **Dendritic cell vs macrophage** — both phagocytose and both can present
  antigen, but only the DC is a professional at *initiating* a naive T cell
  response. Macrophages mostly present to T cells that are already activated.
- ⚠️ **The innate/adaptive boundary is not absolute.** NK cells display
  memory-like behaviour, and monocytes and macrophages can be epigenetically
  reprogrammed by a first encounter so that they respond more strongly to a
  second, unrelated one. The literature calls this **trained immunity**.
  Textbooks draw the line cleanly because it teaches well; the reality is a
  spectrum.

## Open questions

- How exactly do dendritic cells hand antigen to T cells? → [[antigen-presentation]]
- What signals tell an NK cell that a target "should" be killed? The
  missing-self idea suggests loss of MHC I is part of it — needs checking.
- What is the molecular basis of trained immunity, and is it the same kind of
  thing as adaptive memory, or only an analogy?
- Where is the line between "tissue-resident macrophage" and "monocyte-derived
  macrophage" in practice, and does it matter functionally?

## Related

[[antigen-presentation]] · [[t-cells]] · [[b-cells-and-antibodies]] ·
[[complement-system]] · [[inflammation]]
