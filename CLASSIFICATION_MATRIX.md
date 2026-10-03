# CLASSIFICATION MATRIX

**Canonical semantic classification of a50kv109's engineering repository ecosystem.**

---

## Matrix

| REPOSITORY | EMOJI | CATEGORY | SUBCATEGORY | TYPE | STATUS | SUGGESTED TOPICS | RELATED REPOS | NOTES |
|:---|:---:|:---|:---|:---|:---|:---|:---|:---|
| **geometry-reasoning-stand-2** | 📐 | GEOMETRY | Research Stand | RESEARCH_STAND | ACTIVE | `geometry-reasoning`, `research-stand`, `learning-stand`, `parametric-exploration`, `deterministic-verification` | 3D-Geometry-Reasoning-Stand, Portable-Geometric-State-2D, Remix-3CQNS | Primary 2D geometry reasoning environment. Part of geometry cluster. |
| **3D-Geometry-Reasoning-Stand** | 📐 | GEOMETRY | Research Stand | RESEARCH_STAND | ACTIVE | `geometry-reasoning`, `3d-geometry`, `tetrahedron`, `verification-oracle`, `interactive-workstation`, `research-stand` | geometry-reasoning-stand-2, Portable-Geometric-State-2D, blender-adapter | 3D workstation for tetrahedron exploration. Deterministic verification oracle. |
| **Quadrilateral-in-circle-stand** | 📐 | GEOMETRY | Research Stand | RESEARCH_STAND | ACTIVE | `geometry`, `cyclic-geometry`, `research-stand`, `interactive-workstation` | geometry-reasoning-stand-2, Remix-3CQNS | Interactive geometry stand for cyclic quadrilateral properties. |
| **Remix-3CQNS-001-Cyclic-Quadrilateral-Normalization-Stand** | 📐 | GEOMETRY | Research Stand | RESEARCH_STAND | ACTIVE | `geometry`, `cyclic-geometry`, `normalization`, `parametric-exploration`, `research-stand` | geometry-reasoning-stand-2, Quadrilateral-in-circle-stand, Portable-Geometric-State-2D | Cyclic quadrilateral normalization stand. Extension of geometry cluster. |
| **Portable-Geometric-State-2D** | 📐 | GEOMETRY | Semantic Contract | STANDARD | ACTIVE | `geometry`, `2d-graphics`, `semantic-contract`, `portable-format`, `geometry-exchange` | geometry-reasoning-stand-2, Quadrilateral-in-circle-stand, blender-adapter | Portable 2D geometric state exchange standard. Cross-stand interoperability. |
| **AAM-Engineering-Core** | 🧠 | AI / METHODOLOGY | AAM | CORE | EXPERIMENTAL | `aam`, `aam-v1`, `engineering-methodology`, `deterministic-reasoning`, `methodology-core` | AAM-Language-Kernels, AAM-V1_Runtime_Telemetry, aam-v1-agent-guard, SOL-Engineering-Core, acp-core | Reference implementation of AAM-V1 (Artsybashev's Analysis Method). Foundation for methodology layer. |
| **AAM-Language-Kernels** | 🗣️ | AI / METHODOLOGY | Language Kernel | LIBRARY | ACTIVE | `language-kernels`, `nlp`, `aam`, `semantic-analysis`, `multilingual`, `linguistic-architecture` | AAM-Engineering-Core, vedica-aam-core, Pure-Linguistic-Processor | Modular 10-language architecture (eng, rus, ukr, zho, fra, deu, ita, nor, kat, san). |
| **Pure-Linguistic-Processor** | 🗣️ | AI / METHODOLOGY | NLP Tool | TOOL | ACTIVE | `nlp`, `linguistic-analysis`, `language-agnostic`, `linguistic-transformation` | AAM-Language-Kernels, vedica-aam-core | Language-agnostic toolkit for structural linguistic analysis. |
| **vedica-aam-core** | 🗣️ | AI / METHODOLOGY | Language Kernel | LIBRARY | EXPERIMENTAL | `sanskrit`, `linguistic-engineering`, `aam`, `dsl`, `vedic-semantics` | AAM-Language-Kernels, AAM-Engineering-Core | Engineering DSL based on Sanskrit semantic roots. Part of AAM ecosystem. |
| **AAM-Optimus-v21.8** | 🤖 | AI / METHODOLOGY | Agent Application | APPLICATION | EXPERIMENTAL | `robotics`, `adaptive-control`, `impedance-control`, `haptic-feedback`, `aam` | acp-core, AAM-Engineering-Core, aam-v1-agent-guard | Advanced adaptive control system for robotic grip and surface sensing. |
| **aam-v1-agent-guard** | 🛡️ | CORE / RUNTIME / SAFETY | Agent Safety | LIBRARY | EXPERIMENTAL | `agent-safety`, `telemetry`, `long-horizon-agents`, `runtime-guard`, `aam` | AAM-V1_Runtime_Telemetry, acp-core, AAM-Engineering-Core | Topological telemetry and evidence runtime for long-horizon agent monitoring. |
| **AAM-V1_Runtime_Telemetry** | 🛡️ | CORE / RUNTIME / SAFETY | Agent Safety | LIBRARY | EXPERIMENTAL | `agent-safety`, `telemetry`, `early-detection`, `spectral-topological`, `long-horizon-agents`, `aam` | aam-v1-agent-guard, acp-core, warning-engine | Spectral-topological telemetry for early agent collapse detection. |
| **AAM_V1_Colab-AI-2026** | 🤖 | AI / METHODOLOGY | Agent Application | TOOL | EXPERIMENTAL | `aam`, `collaborative-ai`, `agent-framework`, `2026-edition` | AAM-Engineering-Core, acp-core, ai-agent-adapter-st-builder | Collaborative AI tool based on AAM-V1 methodology. |
| **acp-core** | 🛡️ | CORE / RUNTIME / SAFETY | ACP | CORE | FROZEN | `acp`, `deterministic-runtime`, `engineering-reflex`, `safety-critical`, `local-diagnostics` | ACP_CAD_CORE_V1, AAM-Engineering-Core, warning-engine, acp-core | Deterministic engineering reflex runtime. Frozen foundational core. Safety layer for AI agents. |
| **ACP_CAD_CORE_V1** | ⚙️ | CORE / RUNTIME / SAFETY | ACP | CORE | EXPERIMENTAL | `acp`, `cad`, `3d-assembly`, `engineering-analysis`, `e-os` | acp-core, DRAWING-NAV, E-OS-v4.6.0-RC1 | ACP architecture applied to CAD drawings and 3D assemblies. |
| **E-OS-v4.6.0-RC1** | ⚙️ | CORE / RUNTIME / SAFETY | E-OS | CORE | ACTIVE | `e-os`, `engineering-os`, `architecture`, `specification`, `engineering-methodology` | SOL-Engineering-Core, Deep-Seek--engineering-os-core-, DRAWING-NAV, omni-engineering-core-2026 | Engineering Operating System (v4.6.0 RC1). Reference architecture for engineering reasoning. |
| **Deep-Seek--engineering-os-core-** | ⚙️ | CORE / RUNTIME / SAFETY | E-OS | CORE | EXPERIMENTAL | `e-os`, `engineering-os`, `core`, `ontology`, `runtime` | E-OS-v4.6.0-RC1, SOL-Engineering-Core | E-OS core implementation (SOL, ISA, EIR, EEL). |
| **eos-core** | ⚙️ | CORE / RUNTIME / SAFETY | E-OS | CORE | EXPERIMENTAL | `e-os`, `engineering-os`, `core`, `runtime` | E-OS-v4.6.0-RC1, Deep-Seek--engineering-os-core- | E-OS core skeleton/runtime. Incomplete reference. |
| **SOL-Engineering-Core** | 🧠 | AI / METHODOLOGY | SOL | CORE | ACTIVE | `sol`, `structural-operational-language`, `engineering-language`, `typed-core`, `ontology` | E-OS-v4.6.0-RC1, Deep-Seek--engineering-os-core-, Module-64, sol-repository | Structural Operational Language V2.0. Canonical minimal semantic vocabulary. |
| **SOL-2-sol-for-agents** | 🧠 | AI / METHODOLOGY | SOL | FRAMEWORK | EXPERIMENTAL | `sol`, `agents`, `structural-primitives`, `agent-safety`, `invariant-preservation` | SOL-Engineering-Core, Module-64 | SOL methodology for AI agents. Structural primitive extraction and safety. |
| **sol-repository** | 📚 | KNOWLEDGE / DOCUMENTATION | Knowledge Base | LIBRARY | ACTIVE | `sol`, `knowledge-base`, `primitives`, `semantic-contracts`, `engineering-knowledge` | SOL-Engineering-Core, Module-64, sol-lab-g | Canonical knowledge repository for SOL primitives and retrieval contracts. |
| **Module-64** | 📊 | ANALYSIS / MEASUREMENT | Analytical Lenses | LIBRARY | ACTIVE | `sol`, `analytics`, `analytical-lenses`, `structural-analysis`, `measurement` | SOL-Engineering-Core, sol-lab-g, spectral-tracker | Portable library of analytical lenses over SOL primitives. |
| **warning-engine** | 🛡️ | CORE / RUNTIME / SAFETY | Safety System | LIBRARY | ACTIVE | `safety`, `warning-system`, `predictive-analysis`, `early-warning`, `deterministic` | acp-core, aam-v1-agent-guard, mcrg-r-runtime-stabilizer | Deterministic state evaluation and early warning based on weighted predictors. |
| **mcrg-r-runtime-stabilizer** | 🛡️ | CORE / RUNTIME / SAFETY | Safety System | LIBRARY | EXPERIMENTAL | `safety`, `medical-imaging`, `mri-pipeline`, `hallucination-mitigation`, `runtime-stabilization` | AAM-V1_Runtime_Telemetry, warning-engine | Runtime stabilization and hallucination mitigation for MRI neural pipelines. |
| **belov-fiber-sdk** | 📦 | CORE / RUNTIME / SAFETY | SDK | SDK | ACTIVE | `sdk`, `structural-synchronization`, `robotics`, `ai-agents`, `synchronization` | acp-core, E-OS-v4.6.0-RC1 | Universal structural synchronization SDK for AI agents, robotics, and engineering systems. |
| **BOOK-NAV** | 📚 | KNOWLEDGE / DOCUMENTATION | BOOK-NAV | DOCUMENTATION | ACTIVE | `documentation`, `knowledge-extraction`, `intelligent-indexing`, `engineering-books`, `navigation` | BOOK-NAV-Classic, book-nav-classic-v5, BOOK-NAV-Classic-V6, Document-Navigator-Classic | Intelligent navigation standard for engineering books (PDF indexing and extraction). |
| **BOOK-NAV-Classic** | 📚 | KNOWLEDGE / DOCUMENTATION | BOOK-NAV | DOCUMENTATION | EXPERIMENTAL | `documentation`, `ontology`, `representation-ontology`, `engineering-representation`, `knowledge-formalization` | BOOK-NAV, book-nav-classic-v5, BOOK-NAV-Classic-V6, Document-Navigator-Classic | Formalization of engineering representation ontology. Layer 0 of BOOK-NAV. |
| **BOOK-NAV-CLASSIC-FINAL-RELEASE-2** | 📚 | KNOWLEDGE / DOCUMENTATION | BOOK-NAV | DOCUMENTATION | FROZEN | `documentation`, `archive`, `book-nav` | BOOK-NAV, BOOK-NAV-Classic | Final archive release of BOOK-NAV Classic. |
| **book-nav-classic-v5** | 📚 | KNOWLEDGE / DOCUMENTATION | BOOK-NAV | DOCUMENTATION | EXPERIMENTAL | `documentation`, `document-navigation`, `evidence-materialization`, `ai-agents` | BOOK-NAV-Classic, BOOK-NAV-Classic-V6, Document-Navigator-Classic | Document navigation with on-demand evidence materialization. |
| **BOOK-NAV-Classic-V6** | 📚 | KNOWLEDGE / DOCUMENTATION | BOOK-NAV | DOCUMENTATION | EXPERIMENTAL | `documentation`, `document-navigation`, `table-extraction`, `figure-extraction`, `verified-extraction` | book-nav-classic-v5, Document-Navigator-Classic-v2 | Document navigation with verified TABLE and FIGURE extraction. |
| **DRAWING-NAV** | 📚 | KNOWLEDGE / DOCUMENTATION | DRAWING-NAV | TOOL | ACTIVE | `cad`, `drawing-extraction`, `engineering-navigation`, `e-os`, `semantic-typing` | BOOK-NAV, ACP_CAD_CORE_V1, E-OS-v4.6.0-RC1, omni-engineering-core-2026 | CAD drawing converter to E-OS typed artifacts. Engineering drawing passport protocol. |
| **Document-Navigator-Classic** | 📚 | KNOWLEDGE / DOCUMENTATION | Document Processing | TOOL | EXPERIMENTAL | `documentation`, `document-navigation`, `archival-analysis`, `document-processing` | BOOK-NAV, Document-Navigator-Classic-v2, BOOK-NAV-Classic-V6 | Document processing architecture for archival analysis. |
| **Document-Navigator-Classic-v2** | 📚 | KNOWLEDGE / DOCUMENTATION | Document Processing | TOOL | EXPERIMENTAL | `documentation`, `document-navigation`, `source-isolation`, `archival-processing`, `code-protection` | Document-Navigator-Classic, BOOK-NAV-Classic-V6 | Experimental document processing with source isolation. Safer AI-assisted analysis. |
| **engineering-knowledge-repository** | 📚 | KNOWLEDGE / DOCUMENTATION | Knowledge Base | LIBRARY | ACTIVE | `knowledge-base`, `engineering-patterns`, `engineering-laws`, `ecp`, `reusable-primitives` | engineering-constructor-primitives-MENTOR, E-OS-v4.6.0-RC1 | Structured knowledge base of ECPs, patterns, laws, and principles. |
| **engineering-constructor-primitives-MENTOR** | 📚 | KNOWLEDGE / DOCUMENTATION | Methodology | FRAMEWORK | EXPERIMENTAL | `engineering-primitives`, `ecp`, `methodology`, `patterns`, `reusability` | engineering-knowledge-repository, E-OS-v4.6.0-RC1 | ECP methodology for reusable engineering artifacts and composition rules. |
| **CSP-0.1** | 📚 | KNOWLEDGE / DOCUMENTATION | Standard | STANDARD | EXPERIMENTAL | `cognitive-skills`, `skill-passport`, `verification`, `ai-skills`, `transfer` | AAM-Engineering-Core, E-OS-v4.6.0-RC1 | Cognitive Skill Passport (open standard for AI skill description and verification). |
| **graph-builder** | 🛠️ | ENGINEERING TOOLS / ADAPTERS | Graph Tool | LIBRARY | ACTIVE | `graph-construction`, `connectivity-rules`, `deterministic`, `domain-independent`, `architecture-first` | spectral-tracker, sol-lab-g, git-agent-adapter | Transform unstructured objects into structured graphs via explicit connectivity rules. |
| **spectral-tracker** | 📊 | ANALYSIS / MEASUREMENT | Graph Analysis | TOOL | ACTIVE | `graph-analysis`, `spectral-analysis`, `topology-measurement`, `graph-topology`, `measurement` | graph-builder, sol-lab-g, temporal-analyzer-v2 | Deterministic graph topology measurement engine. Produces Graph Passports. |
| **sol-lab-g** | 📊 | ANALYSIS / MEASUREMENT | Structural Analysis | RESEARCH_STAND | ACTIVE | `sol`, `structural-analysis`, `architecture-analysis`, `deterministic-analysis`, `research-stand` | SOL-Engineering-Core, graph-builder, spectral-tracker, Module-64 | SOL Structural Lab (Lab-G). Deterministic architecture analysis for AI agents. |
| **SOL-Structural-Lab--D-v2.0** | 📊 | ANALYSIS / MEASUREMENT | Structural Analysis | RESEARCH_STAND | ACTIVE | `sol`, `structural-analysis`, `evidence-based-analysis`, `bounded-reports`, `graph-topology` | sol-lab-g, spectral-tracker, Module-64 | Evidence-based structural analysis laboratory. Machine-readable reports. |
| **temporal-analyzer-v2** | 📊 | ANALYSIS / MEASUREMENT | Temporal Analysis | LIBRARY | ACTIVE | `temporal-analysis`, `time-series`, `measurement`, `engineering-measurement`, `deterministic` | spectral-tracker, Fe3uni-Harmonic-Analytics-v3.0, warning-engine | Deterministic engineering measurement library for temporal system analysis. |
| **Fe3uni-Harmonic-Analytics-v3.0** | 📊 | ANALYSIS / MEASUREMENT | Harmonic Analysis | LIBRARY | EXPERIMENTAL | `harmonic-analysis`, `analytics`, `physics`, `utilities`, `fe3uni` | spectral-tracker, temporal-analyzer-v2 | Harmonic analysis utilities from Fe3uni. Reusable physics analytics. |
| **vsam** | 📊 | ANALYSIS / MEASUREMENT | Platform | LIBRARY | ACTIVE | `measurement`, `platform`, `analyzers`, `engineering-measurement`, `modular` | E-OS-v4.6.0-RC1, temporal-analyzer-v2, spectral-tracker | Modular engineering measurement platform for building analyzers. |
| **ai-agent-adapter-st-builder** | 🛠️ | ENGINEERING TOOLS / ADAPTERS | Adapter Factory | TOOL | ACTIVE | `adapter`, `ai-adapter`, `agent-integration`, `standardization`, `st-builder` | git-agent-adapter, blender-adapter, libreoffice-agent-adapter, graph-builder | ST Builder: Generate standardized AI agent adapters from software. |
| **git-agent-adapter** | 🔌 | ENGINEERING TOOLS / ADAPTERS | Adapter | TOOL | ACTIVE | `git`, `vcs`, `adapter`, `agent-integration`, `st-builder` | ai-agent-adapter-st-builder, graph-builder | Hybrid ST Builder adapter for Git. Machine-readable metadata + Python SDK. |
| **blender-adapter** | 🔌 | ENGINEERING TOOLS / ADAPTERS | Adapter | TOOL | ACTIVE | `blender`, `3d-graphics`, `adapter`, `ai-automation`, `linux-first` | ai-agent-adapter-st-builder, ACP_CAD_CORE_V1, Portable-Geometric-State-2D | Linux-first Blender adapter for AI agents. Stable automation bridge. |
| **libreoffice-agent-adapter** | 🔌 | ENGINEERING TOOLS / ADAPTERS | Adapter | TOOL | EXPERIMENTAL | `libreoffice`, `adapter`, `document-automation`, `ai-integration` | ai-agent-adapter-st-builder, blender-adapter | LibreOffice adapter for AI agents. Document automation bridge. |
| **https-github.com-a50kv109-apae-adapter-factory** | 🛠️ | ENGINEERING TOOLS / ADAPTERS | Adapter Factory | TOOL | ACTIVE | `adapter-factory`, `engineering`, `adapter-automation`, `st-builder` | ai-agent-adapter-st-builder, graph-builder | Engineering Adapter Factory (reference/duplicate). Automated adapter analysis and verification. |
| **-Chaos-Combine** | 🛠️ | ENGINEERING TOOLS / ADAPTERS | Audit Tool | TOOL | ACTIVE | `chaos-analysis`, `architecture-audit`, `methodology`, `chaos-reduction`, `two-heroes` | two-heroes-tool, AAM-Engineering-Core, E-OS-v4.6.0-RC1 | Architecture auditing and chaos reduction tool. Systematic system analysis. |
| **two-heroes-tool** | 🛠️ | ENGINEERING TOOLS / ADAPTERS | Audit Tool | TOOL | ACTIVE | `adversarial-analysis`, `two-heroes`, `methodology`, `architecture-analysis` | -Chaos-Combine, AAM-Engineering-Core | Adversarial analysis engine. Dialectical interpretation framework. |
| **omni-engineering-core-2026** | ⚙️ | CORE / RUNTIME / SAFETY | E-OS | CORE | ACTIVE | `e-os`, `cad`, `graphics-editor`, `aam`, `delta-minimization` | E-OS-v4.6.0-RC1, DRAWING-NAV, AAM-Engineering-Core | E-OS V2.20 hybrid kernel (Go/Python) for Omni graphics editor integration. |
| **Ukrainian-Poetry-Studio** | 🧪 | EXPERIMENTAL / EMERGING | Creative Application | APPLICATION | EXPERIMENTAL | `poetry`, `creative`, `ukrainian`, `nlp`, `linguistic-art` | (standalone) | Ukrainian poetry studio and composition tool. Creative linguistic exploration. |

---

## Summary

### Counts
- **Total repositories:** 51
- **Total categories:** 7
- **Total subcategories:** 31
- **Frozen (immutable):** 3 (acp-core, BOOK-NAV-CLASSIC-FINAL-RELEASE-2, (optionally) Portable-Geometric-State-2D)
- **Active:** 26
- **Experimental:** 22

### Category Distribution

| Category | Count | Notes |
|:---|:---:|:---|
| GEOMETRY | 5 | Fully coherent research cluster |
| AI / METHODOLOGY / LANGUAGE | 9 | AAM + SOL + Language kernels cluster |
| CORE / RUNTIME / SAFETY | 9 | E-OS, ACP, safety systems |
| ENGINEERING TOOLS / ADAPTERS | 8 | Adapter ecosystem + audit tools |
| KNOWLEDGE / DOCUMENTATION | 13 | Largest cluster: BOOK-NAV, DRAWING-NAV, ECP, CSP |
| ANALYSIS / MEASUREMENT | 6 | Graph/spectral/temporal analysis |
| EXPERIMENTAL / EMERGING | 1 | Creative/standalone projects |

### Key Clusters & Relationships

#### Cluster 1: Geometry (📐)
- **Core relationship:** geometry-reasoning-stand-2 ↔ 3D-Geometry-Reasoning-Stand ↔ Portable-Geometric-State-2D
- **Extensions:** Quadrilateral-in-circle-stand ↔ Remix-3CQNS
- **Integration:** blender-adapter (visualization), ACP_CAD_CORE_V1 (verification)

#### Cluster 2: AI Methodology (🧠 + 🗣️)
- **Foundation:** AAM-Engineering-Core ↔ SOL-Engineering-Core
- **Languages:** AAM-Language-Kernels, vedica-aam-core, Pure-Linguistic-Processor
- **Safety:** AAM-V1_Runtime_Telemetry, aam-v1-agent-guard
- **Application:** AAM-Optimus-v21.8, AAM_V1_Colab-AI-2026

#### Cluster 3: Core Systems (⚙️ + 🛡️)
- **Foundation:** acp-core (frozen) ↔ E-OS-v4.6.0-RC1 (active)
- **Extensions:** Deep-Seek--engineering-os-core-, eos-core, ACP_CAD_CORE_V1, omni-engineering-core-2026
- **Safety layer:** warning-engine, mcrg-r-runtime-stabilizer

#### Cluster 4: Tools & Adapters (🛠️ + 🔌)
- **Adapter factory:** ai-agent-adapter-st-builder (hub)
- **Specific adapters:** git-agent-adapter, blender-adapter, libreoffice-agent-adapter
- **Graph tools:** graph-builder
- **Audit tools:** -Chaos-Combine, two-heroes-tool

#### Cluster 5: Knowledge & Documentation (📚)
- **BOOK-NAV line:** BOOK-NAV ↔ BOOK-NAV-Classic ↔ book-nav-classic-v5 ↔ BOOK-NAV-Classic-V6
- **Document processing:** Document-Navigator-Classic → Document-Navigator-Classic-v2
- **Drawing extraction:** DRAWING-NAV
- **Engineering knowledge:** engineering-knowledge-repository, engineering-constructor-primitives-MENTOR
- **Standards:** CSP-0.1

#### Cluster 6: Analysis & Measurement (📊)
- **Foundational:** graph-builder → spectral-tracker → sol-lab-g
- **Parallel:** temporal-analyzer-v2, Fe3uni-Harmonic-Analytics-v3.0
- **Labs:** SOL-Structural-Lab--D-v2.0 (evidence-based version of sol-lab-g)
- **Support:** Module-64 (analytical lenses), vsam (measurement platform)

### Ambiguous/Speccial Cases

| Repository | Issue | Recommendation | Notes |
|:---|:---|:---|:---|
| **Portable-Geometric-State-2D** | TYPE: STANDARD vs LIBRARY | ✅ STANDARD (correct) | It's a semantic contract, not a runnable library. Classification is correct. |
| **Engineering-constructor-primitives-MENTOR** | STATUS: Methodology vs Code | ✅ EXPERIMENTAL (correct) | Primarily a framework/methodology. Status reflects its maturity. |
| **omni-engineering-core-2026** | Category: CORE/RUNTIME but also integration-specific | ✅ CORE / RUNTIME (correct) | It's an E-OS implementation variant (DRAWING-NAV → E-OS → Omni). Status = ACTIVE. |
| **Ukrainian-Poetry-Studio** | Standalone, creative, not engineering-focused | ✅ EXPERIMENTAL (correct) | Included for completeness. It's a linguistic/creative exploration. Could be archived/hidden from primary nav if needed. |
| **eos-core** | Skeleton/incomplete state | ✅ EXPERIMENTAL (correct) | Placeholder for E-OS runtime. May become ARCHIVED. Needs status review. |
| **Deep-Seek--engineering-os-core-** | Similar to eos-core: implementation variant | ✅ EXPERIMENTAL (correct) | E-OS core implementation. Maturity unclear. Needs status review. |

### Repositories Requiring Manual Review

1. **eos-core** — Is this still maintained or effectively archived?
2. **Deep-Seek--engineering-os-core-** — What's the difference vs E-OS-v4.6.0-RC1? Should this be consolidated?
3. **Ukrainian-Poetry-Studio** — Keep in primary catalog or move to separate creative projects section?
4. **BOOK-NAV-CLASSIC-FINAL-RELEASE-2** — Is this a true archive or a duplicate?

---

## Emoji Legend

| Emoji | Meaning | Usage |
|:---|:---|:---|
| 📐 | Geometry | Research stands, geometric contracts, 2D/3D geometry |
| 🔬 | Research | (Not used currently; geometry-reasoning uses 📐) |
| 🧠 | AI / Reasoning / Methodology | AAM, SOL, theoretical frameworks |
| 🗣️ | Language / NLP | Language kernels, linguistic tools, DSLs |
| ⚙️ | Core / Runtime | Operating systems, runtime engines, core implementations |
| 🛡️ | Safety / Protection | Safety reflexes, telemetry, early warning, protection layers |
| 🛠️ | Tools | General-purpose tools, audit frameworks, automation |
| 🔌 | Adapter / Integration | Adapters to external systems (Git, Blender, LibreOffice) |
| 📚 | Knowledge / Documentation | Books, knowledge bases, documentation standards, ontologies |
| 📊 | Analysis / Measurement | Graph analysis, structural analysis, temporal analysis, measurement engines |
| 🤖 | Agent / Robotics | Agent applications, robotic control, autonomous systems |
| 📦 | SDK / Library | Reusable software development kits and libraries |
| 🧪 | Experimental | Prototypes, research candidates, work-in-progress |

---

## Next Steps

1. **Review & validate** this matrix (especially ambiguous cases).
2. **Correct speccial entries** (eos-core status, Deep-Seek consolidation, etc.).
3. **Approve emoji assignments** (all emojis are intentional; none are redundant).
4. **Once approved**, generate:
   - `PROFILE_README_TEMPLATE.md` (with emoji-grouped navigation)
   - `TOPICS_APPLICATION_GUIDE.md` (batch topics assignment)
   - `COPILOT_SPACES_CONFIG.md` (space definitions)

