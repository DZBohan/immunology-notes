# 🧬 Immunology Notes

Self-study notes for immunology. The unit of work is a **topic**, not a paper:
each note answers "what did I actually understand," not "what did I read."

Notes are written in English; Chinese glosses are kept in
[`glossary.md`](glossary.md) because the terminology is where a second language
actually helps.

---

## Layout

```
immunology/
├── README.md          this file: index + learning path
├── topics/            one concept or mechanism per file   ← the main work
├── papers/            papers read, if any
├── glossary.md        term table (immunology is an acronym swamp)
├── questions.md       open questions, answered in place
└── logs/              study log, YYYY-MM-DD
```

## How to use it

1. **One topic → one file** in `topics/`, following
   [`topics/_TEMPLATE.md`](topics/_TEMPLATE.md). One file says one thing.
   Prefer more files over one long essay.
2. **Link concepts with `[[file-name]]`.** Immunology is a network, not a tree,
   and links capture that better than folders. Linking to a note that does not
   exist yet is fine — that is the to-write list.
3. **Papers go in `papers/<year>_<slug>_<author>/`**, matching the convention
   used in my other reading repos so the two can cross-reference later.
4. **Open questions go in `questions.md`.** Answer them in place with a date;
   never delete them. The list *is* the progress record.
5. **Every acronym goes in `glossary.md`** — and write what it *does*, not just
   what it expands to.

## Template sections that matter

Two sections in the topic template carry most of the value:

- **Why it exists** — forces the mechanism to be explained in terms of what
  would go wrong without it, instead of restating a definition.
- **Easily confused with** — immunology is full of concepts that look alike and
  are not. This section is usually the most valuable part of a note.

## Learning path

Immunology has strong prerequisite structure; skipping around leaves gaps.
A workable order:

1. **Overview** — innate vs adaptive: division of labour and timescales
2. **Cells and organs** — haematopoietic lineages, primary and secondary
   lymphoid organs, lymphocyte recirculation
3. **Innate immunity** — pattern recognition (PRR / PAMP / DAMP), complement,
   inflammation
4. **Antigen presentation** — MHC I / II, proteasome and endosomal routes,
   cross-presentation
5. **T cells** — TCR rearrangement, thymic positive and negative selection,
   CD4 subsets, CD8 killing
6. **B cells and antibodies** — BCR, class switching, somatic hypermutation,
   affinity maturation, germinal centres
7. **Immune regulation** — Tregs, checkpoints (CTLA-4 / PD-1), tolerance and
   autoimmunity
8. **Applications** — tumour immunology, vaccines, immunotherapy

> Step 8 is where this intersects my own work on ecDNA and spatial genomics —
> tumour microenvironment, immune evasion, immune infiltration in spatial
> transcriptomics. Worth reading against the thesis library when I get there.

## Topic index

Add a line here whenever a topic note is created:
`- [Title](topics/file.md) — one line`

### 1. Overview

- [Innate Immune Cells](topics/innate-immune-cells.md) 🌿 — the cells that fire
  immediately on shared pathogen patterns, with no prior acquaintance required;
  innate buys time, adaptive buys precision
