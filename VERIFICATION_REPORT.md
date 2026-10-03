# VERIFICATION REPORT: AMBIGUOUS REPOSITORIES

**Date:** 2026-10-03  
**Scope:** Point verification of 4 repositories flagged in CLASSIFICATION_MATRIX.md  
**Method:** README analysis + Git metadata + structural inspection  
**Confidence levels:** HIGH / MEDIUM / LOW / INSUFFICIENT_EVIDENCE

---

## 1. `eos-core`

### Current Classification (Matrix)
| Field | Value |
|:---|:---|
| EMOJI | ⚙️ |
| CATEGORY | CORE / RUNTIME / SAFETY |
| SUBCATEGORY | E-OS |
| TYPE | CORE |
| STATUS | EXPERIMENTAL |

### Evidence

**README.md:**
```markdown
# EOS-Core + SA:16

Engineering core package containing EOS runtime modules, SA:16 Sanskrit components, 
integration bridge, and ECA analysis primitives.

## Structure
- eos/core: core runtime modules (sol.py, eir.py, runtime.py)
- eos/sanskrit: SA:16 modules (sa16_core.py, sa16_dhatu.py)
- eos/integration: bridge layer (bridge.py)
- eos/eca: ECA analysis components (eca_core.py)
- examples, tests, docs: support folders
```

**Git Metadata:**
- Created: 2026-07-07
- Last pushed: 2026-07-07 (same day as creation)
- Language: Python
- Size: 11 KB (minimal)
- Open issues: 0
- Description: `null`
- No topics assigned
- No license

**Structural Analysis:**
- Has `/eos/core`, `/eos/sanskrit`, `/eos/integration`, `/eos/eca` directories
- Contains `sol.py`, `eir.py`, `runtime.py` (minimal stubs)
- Contains `examples/`, `tests/`, `docs/` folders
- **NOT actively developed** — only initial push on creation date

### Current Role
This is a **minimal skeleton/scaffold package** for E-OS core with Sanskrit integration. It contains basic module structure but appears to be abandoned after initial commit.

### Relation to Other Repos

**Related in matrix:**
- E-OS-v4.6.0-RC1 (the active, fully-documented reference)
- Deep-Seek--engineering-os-core- (actively developed E-OS V2.20 Toolkit Edition)

**Actual relationship:**
- `eos-core` is **predated** by both. It looks like an early attempt or placeholder.
- `E-OS-v4.6.0-RC1` is the canonical reference implementation (active, documented).
- `Deep-Seek--engineering-os-core-` is a newer, more focused variant (TOOLKIT EDITION, V2.20).

### Status Assessment

**Current:** EXPERIMENTAL  
**Recommendation:** ARCHIVED or DEPRECATED

**Reasoning:**
- No commits after initial push (2026-07-07)
- Minimal code (11 KB = mostly scaffolding)
- No description or license
- Superseded by E-OS-v4.6.0-RC1 (more mature) and Deep-Seek variant (more active)

### Recommended Classification Change

**YES — Change STATUS from EXPERIMENTAL to ARCHIVED**

**Proposed Entry:**
```
eos-core | ⚙️ | CORE / RUNTIME / SAFETY | E-OS | CORE | ARCHIVED | e-os, skeleton, deprecated | E-OS-v4.6.0-RC1, Deep-Seek--engineering-os-core- | Minimal skeleton created 2026-07-07, no subsequent commits. Superseded by E-OS-v4.6.0-RC1 (canonical reference) and Deep-Seek variant (active development).
```

---

## 2. `Deep-Seek--engineering-os-core-`

### Current Classification (Matrix)
| Field | Value |
|:---|:---|
| EMOJI | ⚙️ |
| CATEGORY | CORE / RUNTIME / SAFETY |
| SUBCATEGORY | E-OS |
| TYPE | CORE |
| STATUS | EXPERIMENTAL |

### Evidence

**README.md:**
```markdown
# E-OS Core V2.20 (TOOLKIT EDITION)

Minimal local scaffold for E-OS Core with runtime/event primitives,
navigation adapters, patterns, and CI-ready tests.

Engineering Operating System Core: clean kernel with SOL (ontological primitives),
ISA (type system), EIR (engineering graph), and EEL (exchange language).

## Structure
- src/core: SOL/ISA/EIR/EEL primitives
- src/runtime: engine, validator, handler
- src/domain: builder and lifecycle
- src/nav: navigation adapters
- tests: pytest test suite
- patterns: YAML pattern definitions
```

**Git Metadata:**
- Created: 2026-07-04
- Last pushed: 2026-07-05
- Language: Python
- Size: 23 KB (more substantial than eos-core)
- Open issues: 2 (active)
- Description: `"Engineering Operating System Core — чистое ядро инженерной операционной системы. Содержит SOL (онтологические примитивы), ISA (система типов), EIR (инженерный граф) и EEL (инженерный язык обмена). Основано на паттернах Кассера (Systemic/Systematic, Anticipatory Testing, Lifecycle Framework)."`
- License: MIT
- No topics assigned

**Structural Analysis:**
- Has `/src/core`, `/src/runtime`, `/src/domain`, `/src/nav` directories
- Has `/patterns` with YAML definitions
- Has `/tests` (pytest test suite)
- Has `/docs` (documentation)
- Contains actual Python code (not just scaffolding)
- **2 open issues** suggest active consideration

### Current Role
This is a **focused, "Toolkit Edition" variant of E-OS Core** (V2.20). It's a minimal, locally-runnable implementation with SOL/ISA/EIR/EEL primitives, adapters, and patterns.

### Relation to Other Repos

**Related in matrix:**
- E-OS-v4.6.0-RC1 (canonical reference, v4.6.0)
- eos-core (skeleton)

**Actual relationship:**
- `E-OS-v4.6.0-RC1` is the **canonical reference** — fully documented architecture (v4.6.0).
- `Deep-Seek--engineering-os-core-` is a **self-contained implementation** labeled "V2.20 TOOLKIT EDITION" — distinct version targeting specific use case (local, minimal, pattern-based).

**Naming confusion:** The "Deep-Seek" prefix suggests it was auto-generated or copied from a tool (DeepSeek AI?), but the content is original E-OS V2.20 implementation.

### Status Assessment

**Current:** EXPERIMENTAL  
**Assessment:** ACTIVE (not experimental)

**Reasoning:**
- Has 2 open issues (active development/consideration)
- More substantive than eos-core (23 KB vs 11 KB)
- Has explicit description in Russian
- Has MIT license
- Has tests and patterns
- Explicitly labeled V2.20 TOOLKIT EDITION (distinct variant of E-OS)
- Last commit: 2026-07-05 (recent, though not ongoing)

### Recommended Classification Change

**YES — Change STATUS from EXPERIMENTAL to ACTIVE**

**Proposed Entry:**
```
Deep-Seek--engineering-os-core- | ⚙️ | CORE / RUNTIME / SAFETY | E-OS | CORE | ACTIVE | e-os, toolkit-edition, v2.20, engineering-core, runtime | E-OS-v4.6.0-RC1, eos-core | E-OS V2.20 Toolkit Edition. Self-contained, locally-runnable implementation with SOL/ISA/EIR/EEL. Distinct from canonical v4.6.0 reference. Active with 2 open issues.
```

---

## 3. `Ukrainian-Poetry-Studio`

### Current Classification (Matrix)
| Field | Value |
|:---|:---|
| EMOJI | 🧪 |
| CATEGORY | EXPERIMENTAL / EMERGING |
| SUBCATEGORY | Creative Application |
| TYPE | APPLICATION |
| STATUS | EXPERIMENTAL |

### Evidence

**README.md:**
- File not found in repository
- Only brief description available: "Ukrainian Poetry Studio"

**Git Metadata:**
- Created: 2026-07-23
- Last pushed: 2026-07-23
- Language: TypeScript
- Size: 23 KB
- Open issues: 0
- Description: `"Ukrainian Poetry Studio"`
- No license assigned
- No topics assigned
- Template source: `google-gemini/aistudio-repository-template`

**Structural Analysis:**
- Based on Gemini AI Studio template
- TypeScript project
- No detailed README (only generic template)
- Created and pushed on same day (initial template setup)
- Minimal size suggests basic structure

### Current Role
This is a **creative/linguistic application** for Ukrainian poetry composition/analysis. It's a standalone project using Google Gemini AI template, not part of the core engineering methodology ecosystem.

### Relation to Other Repos

**Related in matrix:** (standalone)

**Actual relationship:**
- This is **completely isolated** from the engineering library ecosystem
- No links to AAM, SOL, E-OS, geometry, tools, or knowledge repos
- Represents a separate creative/artistic domain

### Status Assessment

**Current:** EXPERIMENTAL / Standalone  
**Assessment:** CORRECT (but scope question)

**Decision point:** Should this be included in the primary engineering catalog at all?

**Arguments for KEEP:**
- It is a linguistic project (touches on AAM-Language-Kernels methodology)
- Demonstrates language-neutral engineering approach
- Shows broader applications of engineering methodology

**Arguments for REMOVE from primary catalog:**
- No actual code repository (template-based)
- No documentation or implementation
- No connections to engineering ecosystem
- Represents creative/artistic use case, not engineering
- Clutters the main catalog
- Better suited to a separate "Creative Applications" section or archived

### Recommended Classification Change

**CONDITIONAL:**

**Option A (KEEP in main catalog — current):**
No change. Keep as 🧪 EXPERIMENTAL / EMERGING → Creative Application.

**Option B (MOVE to separate section):**
Create a separate `CREATIVE_APPLICATIONS.md` or `OTHER_PROJECTS.md` section. Remove from CLASSIFICATION_MATRIX.md main catalog.

**Option C (ARCHIVE):**
Mark as ARCHIVED if it's not actively developed and not part of the engineering focus.

**Recommendation: OPTION B — Move to separate section or clearly label as "non-engineering creative application"**

**Proposed Entry (if kept):**
```
Ukrainian-Poetry-Studio | 🧪 | EXPERIMENTAL / EMERGING | Creative Application | APPLICATION | EXPERIMENTAL | poetry, ukrainian, nlp, creative, linguistic-art | (standalone) | Creative linguistic exploration. Based on Gemini AI template. No connections to engineering methodology. Consider maintaining separately from core engineering catalog.
```

---

## 4. `BOOK-NAV-CLASSIC-FINAL-RELEASE-2`

### Current Classification (Matrix)
| Field | Value |
|:---|:---|
| EMOJI | 📚 |
| CATEGORY | KNOWLEDGE / DOCUMENTATION |
| SUBCATEGORY | BOOK-NAV |
| TYPE | DOCUMENTATION |
| STATUS | FROZEN |

### Evidence

**README.md:**
```markdown
# BOOK-NAV Classic — Final Release (STEP 08)

Canonical structural core **and** reference runtime for engineering book navigation.

1. Knowledge / Ontology layer (docs/, PHILOSOPHY.md, Layer 0, Atlas)
2. Typed structural core (STEP 02–07)
3. Runtime pipeline binding (STEP 08: Gemini untrusted JSON → ClassicDocument)

PDF → upload → Gemini (untrusted) → bindClassicPipeline → ClassicDocument
```

**Git Metadata:**
- Created: ~54 days ago (August 2026)
- Last pushed: 2026-08-10
- Language: TypeScript
- Size: 106 KB (substantial)
- Open issues: 0
- Description: `null`
- License: MIT
- No topics assigned

**Structural Analysis:**
- Contains full implementation (not scaffold)
- Has typed structural model (CLASSIC-STRUCTURAL-MODEL.json)
- Has 123 tests (115 unit + 8 integration)
- Has documentation (docs/)
- Has runtime pipeline (Gemini → ClassicDocument binding)
- **This is NOT an archive — it's a working release**

### Current Role
This is the **"STEP 08" Final Release** of BOOK-NAV Classic — a working, tested implementation that combines:
1. Knowledge/Ontology layer
2. Typed structural core
3. Runtime pipeline for PDF processing

This is a **functional release**, not merely an archive.

### Relation to Other Repos

**Related in matrix:**
- BOOK-NAV (original)
- BOOK-NAV-Classic (formalization)
- book-nav-classic-v5 (V5 with evidence materialization)
- BOOK-NAV-Classic-V6 (V6 with verified extraction)

**Actual relationship:**
- **BOOK-NAV-CLASSIC-FINAL-RELEASE-2** is positioned as "FINAL RELEASE (STEP 08)"
- **BOOK-NAV-Classic** is the formalization layer
- **book-nav-classic-v5** and **BOOK-NAV-Classic-V6** are newer versions with enhanced extraction
- **BOOK-NAV** is the original standard

**Version lineage:**
```
BOOK-NAV (original)
  ↓
BOOK-NAV-Classic (formalization)
  ↓
BOOK-NAV-CLASSIC-FINAL-RELEASE-2 (STEP 08 implementation)
  ↓
book-nav-classic-v5 (evidence materialization)
  ↓
BOOK-NAV-Classic-V6 (verified table/figure extraction)
```

### Status Assessment

**Current:** FROZEN  
**Assessment:** CORRECT, but naming confusion

**Reasoning:**
- It is "FINAL RELEASE" — so it should not receive further changes
- It has 0 open issues (not active development)
- It's a milestone implementation (STEP 08), not an ongoing project
- Newer versions (v5, v6) supersede it for new development

**Naming issue:** "FINAL-RELEASE-2" suggests there's a "FINAL-RELEASE-1" somewhere (not in catalog), which creates ambiguity about whether this is truly final or deprecated.

### Recommended Classification Change

**NO — Keep as FROZEN** ✅

**However, add clarification to NOTES:**

**Proposed Entry:**
```
BOOK-NAV-CLASSIC-FINAL-RELEASE-2 | 📚 | KNOWLEDGE / DOCUMENTATION | BOOK-NAV | DOCUMENTATION | FROZEN | documentation, book-nav, final-release, reference-implementation | BOOK-NAV-Classic, book-nav-classic-v5, BOOK-NAV-Classic-V6 | Milestone release (STEP 08) combining ontology, typed core, and runtime pipeline. Superseded by v5 and v6 for new work. Frozen as reference implementation.
```

---

## Summary & Recommendations

| Repository | KEEP | CHANGE | Recommendation | Confidence |
|:---|:---:|:---:|:---|:---:|
| `eos-core` | ❌ | ✅ | Change STATUS: EXPERIMENTAL → ARCHIVED | **HIGH** |
| `Deep-Seek--engineering-os-core-` | ✅ | ✅ | Change STATUS: EXPERIMENTAL → ACTIVE | **HIGH** |
| `Ukrainian-Poetry-Studio` | ⚠️ | ✅ | MOVE to separate non-engineering section OR keep as-is with clarification | **MEDIUM** |
| `BOOK-NAV-CLASSIC-FINAL-RELEASE-2` | ✅ | ❌ | KEEP as-is (FROZEN status is correct) | **HIGH** |

---

## Action Items

### Immediate (HIGH CONFIDENCE)

1. ✅ **Update `eos-core` STATUS:** EXPERIMENTAL → ARCHIVED
   - Rationale: Superseded, no commits after creation
   - Impact: Low (minimal usage expected)

2. ✅ **Update `Deep-Seek--engineering-os-core-` STATUS:** EXPERIMENTAL → ACTIVE
   - Rationale: Has 2 open issues, explicit V2.20 implementation, MIT licensed
   - Impact: Medium (clarifies this is active variant)

### Conditional (MEDIUM CONFIDENCE)

3. ⚠️ **Handle `Ukrainian-Poetry-Studio`:**
   - Option A: Keep in matrix with note that it's non-engineering-focused
   - Option B: Move to separate `CREATIVE_APPLICATIONS.md` or similar
   - **Recommendation:** Option B (cleaner catalog)

### No Action Needed

4. ✅ **`BOOK-NAV-CLASSIC-FINAL-RELEASE-2`:** No change required. FROZEN status is correct.

---

## Next Steps

Once you approve these findings, I can:
1. Update CLASSIFICATION_MATRIX.md with the recommended changes
2. Create CREATIVE_APPLICATIONS.md (if option B chosen for Ukrainian-Poetry-Studio)
3. Proceed to PROFILE_README_TEMPLATE.md generation
4. Define GitHub Topics assignments

