---
type: comparison
created: 2026-09-25
updated: 2026-09-26
status: detailed conceptual mapping; not an implementation commitment
reliability: "AI interpretation of the linked local notes and selected reading descriptions; compatibility and implementation are not established; model: GPT-5.6 Sol; reasoning: High"
---

# Harness readings mapped to Alexs exocortex

Alex’s Exocortex is a **complete operating template** for an Obsidian-centered human + agent system. [[Harness reading order|Harness reading order]] is broader: it contains architectures, procedures, research, courses, standards, and worked examples that can explain, challenge, or deepen individual parts of Alex’s design.

This note maps the reading set to Alex’s actual §§1–11. A mapping means **relevant to the same design problem**, not “compatible” or “better.” Some readings reinforce Alex; others imply a different architecture.

> [!summary]
> **Alex is strongest as a concrete integrated operating system:** folders, projects, task cards, sessions, migration, safety rules, and maintenance rituals.
>
> The reading set is strongest where Alex is thinner: **knowledge modeling, provenance, context/memory architecture, skill design, evaluation, agent runtime architecture, human control, and alternative PKM patterns.**
>
> The most important external complements are **Karpathy LLM Wiki, Claude Obsidian, Ars Contexta, domain-modeling, PROV/SKOS/data quality, Anthropic memory + long-running harnesses, Writing for agents, OpenAI harness engineering, and concrete task/decision/handoff procedures.**

Sources: [[Domains/System/Harness development/Alexs exocortex|Alex’s Exocortex]] and [[Harness reading order|Harness reading order]].

## How to read the mapping

- **Reinforces** – supports substantially the same design choice.
- **Details** – supplies a more concrete procedure, schema, example, or implementation.
- **Extends** – covers a capability Alex does not develop much.
- **Alternative** – solves the same problem with a materially different structure.
- **Evidence / caution** – adds research, limitations, or evaluation rather than another design.


## §1 Philosophy — five principles

Alex’s five principles are: preserve raw sources, treat derivatives as rebuildable, maintain one shared harness, keep the vault canonical, and prefer simplicity over completeness.

### 1.1 Raw sources are sacred

| Reading | Relation | What it contributes |
|---|---|---|
| **Karpathy: LLM Wiki** | **Reinforces** | Closest conceptual ancestor: preserve source material, then build maintained knowledge above it rather than mutating evidence. |
| **Claude Obsidian** | **Details** | End-to-end source → cited knowledge workflow and sample vault rather than only the principle. |
| **W3C PROV Primer** | **Extends** | Precise vocabulary for source, derivation, revision, responsibility, and provenance when raw-vs-derivative becomes too coarse. |
| **UK Government Data Quality Framework** | **Extends** | Freshness, completeness, consistency, validity, and quality communication; immutable does not necessarily mean correct or sufficient. |
| **Docling document representation** | **Conditional implementation** | Preserves document hierarchy, tables, layout, and provenance during ingestion. |

Alex has a strong **immutability rule**. PROV and data-quality material make it more precise by separating preservation from trustworthiness and lineage.

### 1.2 Derivatives are rebuildable

| Reading | Relation | What it contributes |
|---|---|---|
| **Karpathy: LLM Wiki** | **Reinforces** | Maintained higher-level knowledge is produced from preserved material and can be regenerated or revised. |
| **Claude Obsidian** | **Details** | Concrete extraction and maintenance patterns for turning sources into linked notes. |
| **Anthropic: Contextual Retrieval** | **Alternative / implementation** | Adds source context before retrieval; relevant if ordinary Markdown search later stops being enough. |
| **GraphRAG** | **Conditional alternative** | Heavier graph-based retrieval/synthesis; Alex explicitly argues not to add such machinery until ordinary files/search fail. |
| **Knowledge Graphs for RAG** | **Conditional implementation** | Practical graph representation/query path if linked notes later need machine retrieval beyond Obsidian. |

### 1.3 One harness — many agents

| Reading | Relation | What it contributes |
|---|---|---|
| **Writing for agents** | **Details** | Shared guidance as pointers, procedures, references, and progressively disclosed context instead of duplicated instructions. |
| **Obsidian vault template: Skills Index** | **Details** | Routing metadata: when a skill applies, expected output, dependencies, boundaries. |
| **Agent Skills overview** | **Extends** | Standard skill-folder model and progressive loading of metadata, instructions, and resources. |
| **OpenAI: harness engineering** | **Reinforces / extends** | Maintained knowledge, navigation, constraints, and inspectable artifacts are part of the agent environment, not just prompts. |
| **HumanLayer: 12 Factor Agents** | **Alternative framing** | Makes state, context, control flow, and tool boundaries explicit rather than centering only the filesystem hierarchy. |

### 1.4 Vault is primary; runtime indexes are secondary

| Reading | Relation | What it contributes |
|---|---|---|
| **Karpathy: LLM Wiki** | **Reinforces** | Files remain inspectable and human-owned instead of making an opaque database the only source of truth. |
| **Claude Obsidian** | **Reinforces** | Markdown-native knowledge layer. |
| **Ars Contexta** | **Mostly reinforces** | Filesystem spaces remain durable architecture, but agent self, durable notes, and temporary operations are separated more sharply. |
| **LangGraph persistence / LangMem / memory APIs** | **Alternative runtime layer** | Useful when runtime state or shared memory must live outside Markdown; can remain subordinate if the vault stays canonical. |

### 1.5 Simplicity over completeness

| Reading | Relation | What it contributes |
|---|---|---|
| **Ars Contexta** | **Reinforces with a different rule** | Explicit spaces and promotion rules prevent operational debris from contaminating durable knowledge. |
| **Anthropic: Building effective agents** | **Reinforces** | Prefer simple composable workflows before autonomous or multi-agent complexity. |
| **OpenAI / Fowler harness-engineering material** | **Reinforces** | Improve environment, context, feedback, and constraints before inventing more machinery. |
| **GraphRAG / LangGraph / multi-agent readings** | **Useful escalation paths** | Valuable only when a concrete failure mode justifies the extra complexity. |

## §2 Vault structure

Alex uses a strong **project / system / library / archive folder architecture**. This is one of the places where the readings contain real alternatives, not just elaborations.

| Reading | Relation | What it contributes |
|---|---|---|
| **Ars Contexta: three-space architecture** | **Alternative architecture** | Organizes by purpose and lifecycle: self / durable notes / temporary ops. This cuts across Alex’s project/library structure. |
| **Claude Obsidian** | **Alternative worked system** | Another complete source-to-knowledge vault. |
| **LifeOS architecture** | **Alternative integrated system** | Direction, work records, knowledge, and freshness in a broader personal OS. |
| **GBrain: what schemas unlock** | **Alternative data-centric system** | Typed entities and relationships become primary rather than folder location. |
| **PARA** | **Background analogue** | Projects, responsibilities/resources, archive; Alex is more agent- and source-lifecycle-specific. |
| **Milo: maps of content** | **Extends navigation** | Curated maps over content reduce dependence on folder hierarchy. |
| **Matuschak: concept-oriented notes** | **Tension** | Durable knowledge should organize around reusable concepts rather than the source/project that created it. |

### Main design tension

**Alex:** project/file-location first.  
**Ars:** lifecycle/purpose first.  
**GBrain/domain modeling:** entities/relationships first.  
**Matuschak/MOCs:** concept/navigation first.

These are different axes and can coexist if the vault distinguishes:

- **physical home** – where the file lives;
- **semantic type** – what the thing is;
- **lifecycle** – raw / working / durable / archived;
- **navigation** – how humans and agents find it.

That distinction is not explicit enough in Alex and is one of the strongest contributions of the reading set.

## §3 Naming convention

Alex gives filesystem naming rules; the readings add **semantic naming**.

| Reading | Relation | What it contributes |
|---|---|---|
| **Pocock domain-modeling + Fowler ubiquitous language** | **Extends strongly** | Define stable domain terms before encoding them as folder names, properties, task types, or schemas. |
| **The Accidental Taxonomist** | **Extends** | Preferred labels, synonyms, hierarchical relationships, controlled vocabulary maintenance. |
| **W3C SKOS Primer** | **Extends formally** | Concepts, preferred/alternate labels, broader/narrower/related relationships. |
| **Fowler Value Object / Aggregate** | **Supporting model** | Helps decide identity and boundaries of records, not only their filenames. |
| **Obsidian Markdown skill** | **Implementation reference** | Exact Obsidian syntax and link/property mechanics. |

**Gap in Alex:** naming conventions specify how names look, but less about **how to decide what deserves its own identity and what vocabulary should mean**.

## §4 Harness — AGENTS.md, pointers, protocols

This is one of the richest overlaps.

| Reading | Relation | What it contributes |
|---|---|---|
| **Writing for agents** | **Direct detail** | Thin pointers, information hierarchy, procedure vs reference, and agent-consumable guidance. |
| **Obsidian Skills Index** | **Direct detail** | Discovery/routing layer Alex names but does not fully specify. |
| **Agent Skills overview** | **Extends** | Standardized skills with metadata and progressive disclosure. |
| **Hugging Face: Building Your First Skill** | **Procedure** | Structure, activation, supporting files, validation/debugging. |
| **Anthropic skill creator** | **Procedure** | Example → baseline → revision loop for developing skills. |
| **OpenAI: using skills for maintenance** | **Worked architecture** | Separates repository guidance, reusable skills, and deterministic scripts. |
| **OpenAI: harness engineering** | **Broader frame** | Harness includes environment, navigation, verification, tools, and feedback—not only an instruction file. |
| **MCP architecture** | **Extends runtime integration** | Hosts, clients, servers, tools, resources, and prompts. |
| **Deep Agents overview** | **Alternative harness** | Planning, filesystem context, delegation, execution, and memory in a packaged harness. |

### Important correction to Alex

Alex treats **AGENTS.md + CLAUDE.md** as the harness center. The newer readings support a broader model:

**harness = instructions + discoverable context + skills/procedures + tools + state/memory + execution environment + verification/feedback.**

The root guidance remains important, but it is one layer of the harness rather than the whole harness.

## §5 Project template

Alex is already concrete here; readings mainly improve **project semantics and execution procedure**.

| Alex element | Best reading complements | What they add |
|---|---|---|
| Project identity / boundaries | **Domain-modeling**, **Shape Up: Set Boundaries** | What the project object represents; appetite, boundaries, uncertainty. |
| Tasks / statuses | **Anthropic task management** | Worked Markdown state transitions, waiting, blocking, updates. |
| Decisions.md | **Nygard decision records** | Context → decision → status → consequences. |
| Task cards | **OpenAI ExecPlans** | Durable progress, discoveries, decisions, outcomes. |
| Planning uncertainty | **Wayfinder** | Decision map, unresolved questions, dependencies, stopping conditions. |
| Session handoff | **Pocock handoff** | Explicit next-session context package. |
| Local implementation | **Project template + Work brief** | Your own current comparison point; more important than adopting external templates wholesale. |
| Cross-level priorities | **GTD horizons** | Connect project execution to responsibilities/goals. |

### Gap in Alex

Alex gives a **good project container**, but comparatively little method for:

- deciding whether work is worth doing;
- shaping an uncertain project;
- representing unresolved decisions;
- learning from execution;
- distinguishing project state from task state.

## §6 Data layers — raw → derivatives → digest

This is the core overlap with the reading program.

### §6.1 Three levels

| Reading | Relation | What it adds |
|---|---|---|
| **Karpathy LLM Wiki** | **Foundational analogue** | Preserved sources plus maintained higher-level knowledge. |
| **Claude Obsidian** | **Concrete implementation** | Actual source-to-knowledge workflow and sample structure. |
| **Ars Contexta** | **Orthogonal architecture** | Durable knowledge vs temporary ops vs optional agent self; Alex’s levels instead describe derivation/compression. |
| **PROV** | **Formal lineage** | Who/what derived what from which source, including revisions. |
| **Data Quality Framework** | **Quality layer** | Freshness/completeness/consistency checks that raw/derived status alone cannot express. |
| **Matuschak / Zettelkasten** | **Knowledge transformation** | Push beyond summaries toward reusable concept-centered knowledge. |

**Key distinction:** Alex’s levels answer **how derived/compressed is this?** Ars answers **what role/lifecycle does this play?** They are orthogonal, not substitutes.

### §6.2 Processing status

Relevant complements:

- **Anthropic process optimization** – inspect queues, waits, handoffs, and rework.
- **Data Quality Framework** – add meaningful dimensions beyond raw/processed.
- **PROV** – retain derivation/revision history if processing becomes multi-step.
- **Docling** – preserve document structure/provenance during ingestion.

A binary **raw / processed** status is a good minimal start but can become too weak if processed later means extracted, verified, linked, summarized, reconciled, or superseded.

### §6.3 Windows instead of duplicates

| Reading | Relation | What it adds |
|---|---|---|
| **Obsidian Bases** | **Direct implementation** | Views and filtering over file properties. |
| **Dataview metadata** | **Direct implementation** | Queryable page/task metadata. |
| **JSON Schema** | **Validation** | Machine-checkable fields if metadata conventions become strict. |
| **MOCs** | **Human-readable alternative** | Curated navigation windows rather than purely query-generated dashboards. |
| **GBrain** | **Semantic alternative** | Views generated from typed entities/relationships rather than folder/file conventions alone. |

### Tension with the reading guide itself

The reading guide keeps canonical category entries **and repeats seven selected entries in Main sequence**. That intentionally violates Alex’s “windows, not duplicates” principle at the document-text level.

If this becomes annoying, a generated/query-based Main view would align better with Alex and remove synchronization work.

## §7 Rules

### §7.1 Document hygiene

Best complements:

- **Data Quality Framework** – what healthy information means beyond formatting.
- **PROV** – source and revision lineage.
- **JSON Schema** – validate required metadata mechanically.
- **Obsidian Markdown skill** – implementation syntax.
- **SKOS / taxonomy material** – keep labels and categories coherent.

Alex is stronger on **operating hygiene**; the readings are stronger on **semantic quality and validation**.

### §7.2 Working files and ownership

Relevant readings:

- **Ars Contexta ops space** – temporary operational material has a distinct lifecycle and promotion path.
- **Anthropic task management** – concrete stateful work records.
- **OpenAI ExecPlans** – durable execution records.
- **Domain-modeling** – determine whether owner, project, source, task, and artifact are actually distinct concepts.

### §7.3 Links and basename rules

Relevant readings:

- **MOCs** – link-based navigation at scale.
- **Matuschak** – concept-centered links rather than only structural links.
- **SKOS** – semantic relations beyond an undifferentiated wiki-link.
- **PROV** – derivation/revision relations.
- **GBrain** – typed relationships.

**Gap:** Alex treats links mostly as robust filesystem references. The reading set asks what different links **mean**.

### §7.4 One structural writer at a time

There is no stronger direct replacement in the reading list. Alex remains one of the most operational sources here.

Nearby material:

- **OpenAI harness engineering** – inspectable changes and feedback.
- **HAX correction/control** – make AI changes correctable and controllable.
- **Trustworthy agents framework** – distinguish model/harness/tool/environment failure sources.
- **Agent/skill eval material** – verify changes rather than trusting generation.

### §7.5 Runtime ≠ development

Strong complements:

- **Writing for agents** – reference vs procedure vs context.
- **OpenAI skills maintenance** – repository instructions vs reusable skills vs deterministic scripts.
- **Agent Skills overview** – skill packaging and progressive loading.
- **OpenAI Codex as a platform** – reusable execution harness vs surrounding application.

This distinction generalizes beyond personality files and deserves more weight than Alex gives it.

### §7.6 Cloud mirrors

No major reading is a direct replacement. Alex is unusually concrete here.

Possible extensions:

- **PROV** for canonical-source/version lineage.
- **Data Quality** for freshness/staleness.
- **Context engineering** for what should be loaded vs merely available.
- **Writing for agents** for keeping cloud instructions thin.

### §7.7 Sync and Git

Again, Alex is more operational than the reading set. Generic agent literature does not provide a better vault-specific substitute for:

- one structural writer;
- sync exclusions;
- path repair;
- versioning/rollback;
- avoiding repository corruption during sync.

Keep this as an Alex/local-operations topic rather than replacing it with generic agent architecture.

## §8 Session rituals

| Alex ritual | Best complements | What they add |
|---|---|---|
| Session start / orientation | **Anthropic memory management**, **Ars self/ops orientation** | Thin starting context plus deeper lookup. |
| Long-running continuity | **Anthropic long-running harnesses** | Progress records, verification, handoff across fresh contexts. |
| State vs memory | **Google ADK state**, **Memory Bank**, **Managed Agents architecture** | Separate session state, durable memory, event history, and orchestration. |
| Context pressure | **OpenAI compaction**, **session-memory cookbook** | Concrete trimming/summarization strategies. |
| Session close | **Pocock handoff** | Explicit next-session package. |
| Decision capture | **Nygard ADR** | Small durable decision record with rationale/consequences. |
| Task update | **Anthropic task management** | Consistent state/waiting transitions. |

### Improvement suggested by the readings

Alex’s start chain is file-oriented:

**AGENTS → project CLAUDE → Start → last handoff → Tasks**

The memory readings suggest modeling the same chain by **function**:

1. identity / invariant guidance;
2. current goals and task state;
3. recent episodic/session state;
4. relevant durable knowledge retrieved on demand;
5. broader source material only when needed.

That makes the architecture portable even if filenames change.

## §9 Migrating an existing vault

Alex is substantially stronger than most readings here. The dry-run, backup, explicit move map, path registry, single writer, no content rewriting, and acceptance checks form a real migration protocol.

| Reading | What it adds |
|---|---|
| **AIM setup** | Inventory and component-gap diagnosis before redesign. |
| **Anthropic process optimization** | Detect unnecessary steps, waits, handoffs, and rework. |
| **Data Quality Framework** | Define acceptance checks for completeness, consistency, validity, freshness. |
| **PROV** | Preserve lineage if documents are transformed during migration. |
| **Docling** | Structured import when PDFs/Word documents must retain hierarchy/provenance. |
| **HAX correction/control** | Keep structural changes inspectable and reversible by the human. |

### Strong Alex-specific contribution

The reading set has many architectures but almost no equally concrete **safe migration protocol**. Alex should remain a primary operational reference here even if its target folder architecture is not adopted wholesale.

## §10 What not to do

Alex’s anti-pattern list is broadly consistent with the reading set.

| Alex warning | Supporting reading |
|---|---|
| Don’t build RAG/vector machinery early | **Building effective agents**, **harness engineering**, **Contextual Retrieval** as an escalation path |
| Don’t duplicate rules | **Writing for agents**, **Skills overview**, progressive disclosure |
| Don’t trust stale cloud memory | **Context engineering**, **memory management**, **Data Quality Framework** |
| Don’t mix runtime/development | **OpenAI skills maintenance**, **Codex as platform** |
| Don’t introduce complexity without a failure | **Ars Contexta**, **12 Factor Agents**, harness-engineering material |
| Keep AI correctable | **Microsoft HAX** |
| Don’t infer reliability from tidy architecture | **Trustworthy agents framework**, **Measuring Agents in Production**, evaluation readings |

The evaluation literature adds something Alex mostly lacks: **a system can be tidy and still fail behaviorally**. Structural hygiene should eventually be complemented by tests, traces, and outcome checks where the cost justifies it.

## §11 After the start — roadmap and maintenance

| Alex roadmap idea | Complement |
|---|---|
| Add complexity only after living in the system | **Shape Up**, **Ars friction-driven adoption**, harness-engineering principles |
| Clear queues / operational debt | **Process optimization**, **Ars ops space** |
| Regular map-vs-reality review | **Data Quality Framework**, **AIM self-development** |
| Improve repeated failures | **Compound Engineering**, **skill creator**, **SkillOpt**, **SkillEvaluator** |
| Plan uncertain system changes | **Wayfinder**, **ExecPlans** |
| Connect projects to higher goals | **GTD horizons** |

Alex’s roadmap is mainly a **maintenance cadence**. The improvement/skills readings add another loop:

**observe repeated friction → formulate improvement → test → accept/reject → update procedure → re-evaluate**

That is closer to a self-improving harness than cleanup alone.

## Capabilities the reading guide adds beyond Alex

### Semantic knowledge modeling

**Domain-modeling, SKOS, taxonomy, ontology development, GBrain, DDIA.**

Alex has folders, properties, and layers but no deep method for deciding:

- canonical entities;
- identity and boundaries;
- typed relationships;
- aliases/synonyms;
- when something is a concept vs source vs project artifact.

### Memory architecture

**Anthropic memory management, long-running harnesses, Google Memory Bank, ADK state, OpenAI session memory/compaction, Managed Agents, LangMem/LangGraph, LongMemEval.**

Alex has Start.md, digest, handoff, and source layers, but not a full distinction among:

- working/session state;
- episodic memory;
- semantic memory;
- durable event history;
- compaction;
- retrieval;
- revision/consolidation.

### Skill and procedure engineering

**Writing for agents, Agent Skills, skill creator, SkillEvaluator, SkillOpt, skill evaluations, WikiSkill, ACE.**

Alex has Protocols, but little machinery for:

- routing to the right procedure;
- packaging supporting resources;
- testing activation;
- evaluating skill quality;
- improving procedures from traces.

### Runtime / agent architecture

**OpenAI harness engineering, Codex as platform, MCP, Deep Agents, multi-agent research, 12 Factor Agents.**

Alex is primarily a **vault operating architecture**, not a full agent runtime architecture.

### Human control and evaluation

**Microsoft HAX, trustworthy agents, human–AI collaboration research, agent evaluations, Measuring Agents in Production.**

Alex has human approval at important structural points, but does not deeply cover:

- correction UX;
- confidence/calibration;
- evaluation design;
- trace inspection;
- human-vs-agent task allocation.

### Learning system

**Diataxis, Teach, Research, retrieval-practice evidence, Founder OS learning material.**

Alex structures information but does not provide a strong model for turning information into learned competence.

## Important tensions and choices

### 1. Projects vs concepts vs lifecycle

Alex’s filesystem is strongly project-oriented. Several readings imply that **durable knowledge should not inherit the project structure that created it**.

Possible synthesis:

- projects own work;
- raw sources retain provenance;
- durable concepts live independently;
- links/properties connect concepts back to projects/sources;
- ops/session material remains temporary.

### 2. Three derivation levels vs three Ars spaces

Do not collapse these into one hierarchy.

**Alex levels:** raw → derivative → digest = **derivation/compression**.  
**Ars spaces:** self → notes → ops = **purpose/lifecycle**.

A file can therefore be both a **derivative** in Alex’s sense and a durable **note** in Ars’s sense.

### 3. Folder structure vs semantic schema

Alex can work with minimal metadata, but domain-modeling/GBrain/SKOS suggest that once agents automate across the vault, **semantic types and relationships may matter more than exact folders**.

Do not redesign around a schema merely because one exists; introduce it where real queries or automation require it.

### 4. Processed is potentially too broad

**raw / processed** is an excellent minimal start but may later hide meaningful states such as:

**raw → extracted → reviewed → linked → verified → superseded**

Only add these when actual workflows need them.

### 5. AGENTS.md is necessary but not the whole harness

The reading set strongly suggests a larger model:

**guidance + context discovery + skills + tools + state/memory + execution + verification**

This is one of the biggest conceptual upgrades over Alex’s wording.

### 6. Main-list duplication

The reading guide’s Main sequence intentionally copies category entries. Alex’s “windows, not duplicates” rule would prefer a generated/query view.

The current duplication is acceptable while the list is small and manually curated, but it creates synchronization work whenever ratios/descriptions change.

## Where Alex is still stronger

Do not assume newer or more technical readings supersede Alex. Alex remains unusually useful for:

1. **Safe migration:** inventory → classify → dry-run → backup → move → path repair → acceptance.
2. **Concrete project filesystem:** start state, tasks, decisions, sessions, archives.
3. **Operational safety:** one structural writer, diff approval, no destructive cleanup.
4. **Cloud mirrors and canonical-source discipline.**
5. **Practical anti-scope:** don’t build infrastructure before a real failure requires it.
6. **Maintenance ritual:** map-vs-reality review, stale-source surfacing, archive discipline.

These remain reusable operational patterns even if the final folder architecture changes.

## Highest-value pairings

| Alex area | Read next | Why |
|---|---|---|
| §1 + §6 source/knowledge layers | **Karpathy LLM Wiki → Claude Obsidian → PROV** | Principle → worked system → precise lineage model. |
| §2 vault structure | **Ars Contexta → MOCs → domain-modeling** | Purpose/lifecycle → navigation → semantic entities. |
| §4 harness | **Writing for agents → Skills Index → Agent Skills overview → OpenAI harness engineering** | Guidance → discovery → packaging → broader harness model. |
| §5 project work | **Anthropic task management → ADR → Shape Up / Wayfinder** | State → decisions → shaping uncertain work. |
| §6.3 views | **Bases / Dataview → JSON Schema if needed** | Query canonical records before adding schema validation. |
| §8 continuity | **Long-running harnesses → memory management → session memory/compaction** | Cross-session procedure → durable context → context-window mechanics. |
| §9 migration | **Keep Alex primary; add Data Quality + AIM setup** | External readings supplement rather than replace the migration protocol. |
| §10–11 maintenance | **HAX → process optimization → skill/eval material when needed** | Human control → workflow improvement → tested self-improvement. |

## Bottom line

Alex is best treated as a **practical baseline operating template**, not as the complete theory of the harness.

The reading guide adds four major upgrades:

1. **semantic modeling** – what information is, not just where files live;
2. **memory/context architecture** – what agents load, retain, revise, and retrieve;
3. **procedure/skill engineering** – how reusable agent behavior is discovered, tested, and improved;
4. **runtime + evaluation** – how the wider agent system executes and how you know it works.

The strongest synthesis is not “replace Alex with another framework.” It is:

**keep Alex’s operational concreteness and safety rules; use the readings to challenge its folder assumptions, deepen its data/memory model, and broaden harness beyond AGENTS.md into context, skills, tools, state, execution, and verification.**
