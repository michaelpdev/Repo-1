---
type: reading guide
created: 2026-09-25
updated: 2026-09-26
status: proposed learning route; not an implementation commitment
reliability: AI-selected sequence and approximate study levels; source limitations remain in Harness research
---

# Harness reading order

The category lists hold the complete collection. The main sequence copies a small current selection from them, adjusted to your reviews. You do not need to finish every list or course.

**Category order** follows current study priority, not a ranking of quality, difficulty, or popularity. Within each group, concrete fit and learning dependencies determine the proposed sequence.

1. **Useful now:** material addressing a current knowledge or workflow gap.
2. **Supporting depth:** explanations and comparisons for understanding or adapting it.
3. **Conditional study or implementation:** revisit when the stated problem or implementation choice arises.
4. **Background, familiar, or overlapping:** introductions, already-read material, overlap, and research for later.

Unreviewed leads remain in their existing order without a priority ranking. Discovery collections are directories, not a queue. General **Value for you** estimates can remain high for material that is not urgent now; the priority groups reflect your current reviews and needs.

**Levels describe the suggested reading, not source quality or your ability.**

- **Beginner:** little prior knowledge required.
- **Intermediate:** basic agent or knowledge-management concepts assumed.
- **Advanced:** implementation knowledge, technical detail, or research background needed.

All levels are approximate editorial estimates, based on the selected sections and existing research. This is not a full-course assessment. Resource type is listed separately. Supporting links belong to the same reading entry; they are not extra required tasks.

**Theory / practice** is an individually estimated relative balance for the selected reading scope and always sums to 100. **Theory** means conceptual models, explanations, principles, and research evidence. **Practice** includes not only exercises and procedures, but also concrete architectures, schemas, file structures, workflows, commands, worked examples, and implementation decisions that can be directly adapted. The balance estimates what the recommended sections actually contain; it is not a quality or difficulty score.

- **Theory** = conceptual models, explanations, research findings, and principles.
- **Practice** = procedures, exercises, templates, worked examples, and implementation detail.
- `50 / 50` = roughly balanced; `60 / 40` = somewhat more theoretical; `20 / 80` = strongly practice-oriented.
- **Not assessed:** insufficient inspection, including the existing unreviewed leads. No balance is assigned to whole discovery directories.

A high practice share can mean code-heavy exercises; it does not imply applicability to your setup, ease of use, or suitability for installation. **Value for you** and the review notes address that separately.

**Value for you** estimates the value of studying the selected material for your Obsidian-based knowledge work, agent workflows, planning, and learning, taking your existing guidance and limited capacity into account.

- **High:** directly addresses a current need.
- **Moderate:** useful supporting knowledge with a less immediate application.
- **Conditional:** useful if the stated implementation or problem becomes relevant.
- **Unclear:** insufficient information to assess.

These are provisional judgments, not measured benefits or installation recommendations. Description says what the material contains; “Value for you” combines the learning purpose with its likely fit for your case.

Detailed comparisons, provenance, and limitations: [[Harness research]]. Karpathy’s read mark is retained; partial reading and skim feedback are recorded from [[Harness reading, my reviews]], without marking those resources completed. Other existing marks remain in the research note. Reading a skill does not install or invoke it.

**External signals** use the strongest reasonably available public popularity/adoption signal for each resource: resource-specific GitHub/Gist stars or forks, citation counts, book/course ratings, or other direct metrics first; parent-project metrics second; and domain-level Similarweb traffic rank/reach only as a fallback. Domain-level metrics describe the host or platform, not the quality of the specific resource. Different metric types are not directly comparable. Dates and scope are retained with each signal. A remaining “no verified public signal” line means this bounded check still did not establish a defensible public metric, often because the item is local/private or unusually obscure.

## Main sequence

A proposed next-reading selection copied from the category lists below. Those lists hold the full collection; these copies intentionally repeat selected entries for convenient reading. Update category entries first, then refresh their main-list copies.

Based on [[Harness reading, my reviews]], prioritize concrete source-to-knowledge designs and reusable procedures. Your [[Domains/System/Context/About me|About me]] records CS education (2012), and your review says you already know IA/OOP to some degree. Introductory IA and agent overviews remain in their categories as references; evaluation is optional later. This does not assume familiarity with every specialized topic.

Selection is based on provisional fit to your needs, not an established ranking of authors or resources. Pocock’s skills are operating procedures to inspect, not a validated learning curriculum. Writing for agents remains a main-list candidate; domain-modeling remains provisional pending comparison with alternatives. Handoff, Wayfinder, and Teach are optional category references.

Compare the actual structures and worked examples first. Read skills as procedures to understand or adapt; this route does not install them or commit to a framework.

1. [Claude Obsidian](https://github.com/AgriciDaniel/claude-obsidian) · Framework  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 20 / 80
    **Description:** A documented framework for turning preserved sources into linked, cited notes and maintaining the resulting vault.  
    **Read:** overview, “From source to living knowledge,” and [sample vault](https://github.com/AgriciDaniel/claude-obsidian/tree/main/examples/sample-vault).  
    **Value for you:** **High** – Provides an end-to-end example for your ingestion and data-structuring questions.  
    **Notes:** Documentation inspected; the framework was not installed or tested here. Installation suitability remains untested.
    **Category:** [[#Supplied systems and comparisons]].
    **External signals:** [GitHub](https://github.com/AgriciDaniel/claude-obsidian): 15,214 stars, 1,514 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

2. [Ars Contexta: three-space architecture](https://github.com/agenticnotetaking/arscontexta/blob/main/reference/three-spaces.md) · Framework  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 35 / 65
    **Description:** A reference design separating an agent’s own context, durable knowledge, and operating records.  
    **Read:** self, notes, and ops; compare [overview](https://github.com/agenticnotetaking/arscontexta) and [kernel](https://github.com/agenticnotetaking/arscontexta/blob/main/reference/kernel.yaml) selectively.  
    **Value for you:** **High** – Helps distinguish journal evidence, durable knowledge, and temporary task state in your vault.  
    **Notes:** Optional claim checks: [MOC rationale](https://github.com/agenticnotetaking/arscontexta/blob/main/methodology/MOCs%20are%20attention%20management%20devices%20not%20just%20organizational%20tools.md) with [Gloria Mark interview](https://news.gallup.com/businessjournal/23146/too-many-interruptions-work.aspx); [context discussion](https://github.com/agenticnotetaking/arscontexta/blob/main/methodology/LLM%20attention%20degrades%20as%20context%20fills.md) with [Lost in the Middle](https://arxiv.org/abs/2307.03172); [module-adoption guidance](https://github.com/agenticnotetaking/arscontexta/blob/main/methodology/friction-driven%20module%20adoption%20prevents%20configuration%20debt%20by%20adding%20complexity%20only%20at%20pain%20points.md). See the research note’s qualifications; these do not all need reading now.
    **Category:** [[#Supplied systems and comparisons]].
    **External signals:** [GitHub](https://github.com/agenticnotetaking/arscontexta): 3,496 stars, 231 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

3. [Pocock: domain-modeling](https://github.com/mattpocock/skills/blob/main/skills/engineering/domain-modeling/SKILL.md) and [Fowler: ubiquitous language](https://martinfowler.com/bliki/UbiquitousLanguage.html) · Skill and article
    **Selection note:** Main-list selection remains provisional. The skill is an operating procedure to inspect and adapt, paired with Fowler’s conceptual explanation.
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 30 / 70
    **Description:** A modeling skill and accompanying explanation of a shared, domain-specific vocabulary.  
    **Read:** terms, examples, and ambiguous cases.  
    **Value for you:** **High** – Directly addresses defining your data units, properties, and relationships before implementing a schema.
    **Category:** [[#Knowledge and data]].
    **External signals:** [GitHub](https://github.com/mattpocock/skills): 269,713 stars, 22,725 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

4. [Obsidian agent vault template: Skills Index](<C:/Users/Admin/OneDrive/Documents/Obsidian/Vault additional/System/Harnesses/obsidian-agent-vault-template/Skills/Skills Index.md>) · Framework  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 5 / 95
    **Description:** A concrete index showing when skills apply, their outputs, dependencies, and boundaries.  
    **Read:** triggers, expected outputs, dependencies, and boundaries.  
    **Value for you:** **High** – Directly useful for improving discovery and routing within your existing skill collection.  
    **Notes:** Parent [repository](https://github.com/louisfb01/obsidian-agent-vault-template).
    **Category:** [[#Supplied systems and comparisons]].
    **External signals:** [GitHub](https://github.com/louisfb01/obsidian-agent-vault-template): 48 stars, 14 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

5. [Pocock: Writing for agents](https://github.com/mattpocock/skills/blob/main/skills/productivity/writing-for-agents/SKILL.md) · Skill
    **Selection note:** Retained as a main-list candidate for apparent fit with your guidance-writing needs, not because comparative evidence establishes it as the best resource.
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 25 / 75
    **Description:** A reference for context pointers, information hierarchy, and documents consumed by agents.  
    **Read:** context pointers, information hierarchy, and procedure versus reference.  
    **Value for you:** **High** – Helps make your guidance discoverable and usable while reducing duplicated instructions.
    **Category:** [[#Skills and improvement]].
    **External signals:** [GitHub](https://github.com/mattpocock/skills): 269,713 stars, 22,725 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

6. [Anthropic: task management](https://github.com/anthropics/knowledge-work-plugins/blob/main/productivity/skills/task-management/SKILL.md) · Skill  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 10 / 90
    **Description:** A Markdown-based procedure for representing and updating work and waiting states.  
    **Read:** work records, state changes, and waiting.  
    **Value for you:** **Moderate** – Offers a concrete comparison for your task system; its fixed layout is not automatically a fit.
    **Category:** [[#Planning and delegation]].
    **External signals:** [GitHub](https://github.com/anthropics/knowledge-work-plugins): 25,621 stars, 3,032 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

7. [Anthropic: memory management](https://github.com/anthropics/knowledge-work-plugins/blob/main/productivity/skills/memory-management/SKILL.md) · Skill  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 10 / 90
    **Description:** A skill using a small entry layer with deeper information retrieved when needed.  
    **Read:** small entry context and deeper lookup.  
    **Value for you:** **High** – Matches your need for thin guidance and selective access to richer vault context.
    **Category:** [[#Memory and continuity]].
    **External signals:** [GitHub](https://github.com/anthropics/knowledge-work-plugins): 25,621 stars, 3,032 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

## Knowledge and data

Complete topic collection, including introductions kept as optional reference after your reviews. Research details: [[Harness research#Structured knowledge and data units]].

Foundational/high-value references can remain near the top even when already read; completion is shown explicitly rather than by pushing them to the end. Concrete modeling, navigation, and information-quality work follow. Reviewed introductions can remain as later references. Domain-modeling remains provisional.

### Useful now

1. [Karpathy: LLM Wiki](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f) **Read: 25 September 2026.** · Article  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 60 / 40
    **Description:** A short architectural sketch connecting preserved sources with maintained, linked knowledge.  
    **Read:** the author’s original sketch.  
    **Value for you:** **High** – Closely matches the foundational direction you liked and your source-to-knowledge needs.
    **External signals:** [GitHub Gist](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f): 5,000+ stars and 5,000+ forks shown by GitHub; checked 2026-09-26.
    **Your review:** “Awesome”; “Gave much more than Alex did”; “Quite abstract. I need more details.” See [[Harness reading, my reviews]].

2. [Pocock: domain-modeling](https://github.com/mattpocock/skills/blob/main/skills/engineering/domain-modeling/SKILL.md) and [Fowler: ubiquitous language](https://martinfowler.com/bliki/UbiquitousLanguage.html) · Skill and article
    **Selection note:** Main-list selection remains provisional. The skill is an operating procedure to inspect and adapt, paired with Fowler’s conceptual explanation.
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 30 / 70
    **Description:** A modeling skill and accompanying explanation of a shared, domain-specific vocabulary.  
    **Read:** terms, examples, and ambiguous cases.  
    **Value for you:** **High** – Directly addresses defining your data units, properties, and relationships before implementing a schema.
    **External signals:** [GitHub](https://github.com/mattpocock/skills): 269,713 stars, 22,725 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

3. [Milo: maps of content](https://blog.linkingyourthinking.com/notes/mocs-overview) · Article  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 40 / 60
    **Description:** An introduction to maps of content and how their role develops as a collection grows.  
    **Read:** overview, then [three phases of MOCs](https://blog.linkingyourthinking.com/notes/the-3-phases-of-mocs).  
    **Value for you:** **High** – Relevant to your need for useful indexes and an overview without another full folder redesign.
    **External signals:** [Sponsorship.so note-taking creator ranking](https://sponsorship.so/top-influencers/note-taking): Nick Milo’s “Linking Your Thinking” YouTube channel is listed with about 325,000 subscribers; checked 2026-09-26. Creator-level reach, not a rating of this article.

4. [UK Government: Data Quality Framework](https://www.gov.uk/government/publications/the-government-data-quality-framework/the-government-data-quality-framework) · Guidance  
    **Level:** Beginner–Intermediate (approx.)  
    **Theory / practice:** 50 / 50
    **Description:** A framework for assessing information quality throughout its lifecycle and communicating its limits.  
    **Read:** quality dimensions, metadata, and communicating quality; skip organizational governance machinery initially.  
    **Value for you:** **High** – Helps distinguish incomplete, duplicated, inconsistent, outdated, invalid, and inaccurate vault information.  
    **Notes:** Public-sector guidance needs scaling down to personal use; data quality does not by itself establish the truth of a source.  
    **External signals:** [Similarweb](https://www.similarweb.com/website/gov.uk/): gov.uk global traffic rank #524 and about 96.4M visits over the displayed last-three-month period; checked 2026-09-26. Domain-level reach, not a rating of this framework.

### Supporting depth

5. [Matuschak: concept-oriented notes](https://notes.andymatuschak.org/z2hQEhqWkdRLL9JUwfawZZx) · Article  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 70 / 30
    **Description:** Notes about organizing reusable ideas around concepts rather than their source documents.  
    **Read:** the linked note and its examples.  
    **Value for you:** **High** – Can help turn collected materials into knowledge you can retrieve across psychology and harness work.
    **External signals:** [TwStalker](https://www6.twstalker.com/andy_matuschak): Andy Matuschak’s X/Twitter account is shown with about 63,000 followers; checked 2026-09-26. Creator-level reach, not a rating of this note.

6. [Heather Hedden: The Accidental Taxonomist, 3rd edition](https://www.hedden-information.com/accidental-taxonomist/) · Book  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 55 / 45
    **Description:** A guide to concepts, preferred and alternative labels, relationships, and maintaining controlled vocabularies.  
    **Read:** chapters 1, 3, and 4 in the [contents](https://www.hedden-information.com/accidental-taxonomist/table-of-contents/).  
    **Value for you:** **High** – Addresses inconsistent names, overlapping categories, tags, and aliases in your vault.  
    **Notes:** Author overview and contents inspected, not the full book. Goodreads results could not establish a current third-edition rating; do not substitute another edition’s score.  
    **External signals:** [Goodreads](https://www.goodreads.com/book/show/63248377-the-accidental-taxonomist-third-edition): 3.73/5 from 11 ratings for the 3rd edition; checked 2026-09-26.

7. [W3C SKOS Primer](https://www.w3.org/TR/skos-primer/) · Documentation  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 65 / 35
    **Description:** A vocabulary for concepts, labels, semantic relationships, and documentation.  
    **Read:** concepts, labels, broader/narrower/related relations.  
    **Value for you:** **High** – Provides precise foundations for Sasha’s concept-and-relationship direction; formal RDF implementation is unnecessary for this reading.  
    **Notes:** skip RDF syntax initially.
    **External signals:** [Similarweb](https://www.similarweb.com/website/w3.org/): w3.org global traffic rank #26,914; checked 2026-09-26. Domain-level reach, not a rating of this specification.

8. [W3C PROV Primer](https://www.w3.org/TR/prov-primer/) · Documentation  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 65 / 35
    **Description:** A model for describing entities, activities, responsibility, and derivation over time.  
    **Read:** entities, activities, agents, derivation, revision, and time.  
    **Value for you:** **High** – Supports distinguishing your original statements, agent summaries, later revisions, and their sources.
    **External signals:** [Similarweb](https://www.similarweb.com/website/w3.org/): w3.org global traffic rank #26,914; checked 2026-09-26. Domain-level reach, not a rating of this specification.

9. [Anthropic: Contextual Retrieval](https://www.anthropic.com/engineering/contextual-retrieval) · Article  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 45 / 55
    **Description:** An engineering approach that adds explanatory context to chunks before indexing and combines retrieval with reranking.  
    **Read:** why chunks lose context, contextual embeddings and BM25, reranking, and evaluation limits.  
    **Value for you:** **High** – Explains why extracted fragments need source context, even if your current solution remains ordinary notes and search.  
    **Notes:** Reported results concern the provider’s retrieval experiments; they do not establish that your vault needs a RAG pipeline.  
    **External signals:** [Similarweb](https://www.similarweb.com/website/anthropic.com/): anthropic.com global traffic rank #5,521; checked 2026-09-26. Domain-level reach, not a rating of this resource.

10. [Zettelkasten.de: Getting Started](https://zettelkasten.de/overview/) · Study guide  
    **Level:** Beginner–Intermediate (approx.)  
    **Theory / practice:** 35 / 65
    **Description:** A curated introduction to connected notes, knowledge management, reading, writing, and scaling a note collection.  
    **Read:** introduction, atomicity, connectivity, interpreting sources, and scaling the archive.  
    **Value for you:** **High** – Helps turn accumulated sources into connected knowledge you can reuse in psychology and system work.  
    **Notes:** One methodological school, not a universal prescription; overlaps with Matuschak and maps of content.  
    **External signals:** [GitHub](https://github.com/Zettelkasten-Method/zettelkasten.de): 22 stars, 5 forks; checked 2026-09-26. Repository-level signal for the site/project.

11. [Kleppmann and Riccomini: Designing Data-Intensive Applications, 2nd edition](https://www.oreilly.com/library/view/designing-data-intensive-applications/9781098119058/) · Book  
    **Level:** Intermediate–Advanced (approx.)  
    **Theory / practice:** 65 / 35
    **Description:** A broad systems book covering data models, storage, processing, reliability, and distributed-system tradeoffs.  
    **Read:** data models and query languages; compare relational, document, and graph representations before deeper systems chapters.  
    **Value for you:** **High** – Selected modeling sections can clarify data representation choices; the full distributed-systems curriculum exceeds your immediate needs.  
    **Notes:** Publisher overview and contents inspected, not the full book. No verified second-edition-specific rating found; first-edition or combined-edition rankings are not substituted.  
    **External signals:** [Goodreads](https://www.goodreads.com/en/book/show/238227532-designing-data-intensive-applications): 4.62/5 from 93 ratings for the 2026 second edition; checked 2026-09-26.

12. [Fowler: Value Object](https://martinfowler.com/bliki/ValueObject.html) and [Aggregate](https://martinfowler.com/bliki/DDD_Aggregate.html) · Articles  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 60 / 40
    **Description:** Software-design explanations of value-based identity and groups of related objects.  
    **Read:** identity, equality, and grouping examples.  
    **Value for you:** **Moderate** – Helpful for reasoning about note and record boundaries, but translating software concepts adds effort.
    **External signals:** [Similarweb](https://www.similarweb.com/website/martinfowler.com/): martinfowler.com global traffic rank #113,710; checked 2026-09-26. Domain-level reach, not a rating of these articles.

### Conditional study or implementation

13. [JSON Schema: objects](https://json-schema.org/understanding-json-schema/reference/object) · Documentation  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 15 / 85
    **Description:** Documentation for declaring and validating the structure of object-shaped data.  
    **Read:** properties, required fields, and additional properties.  
    **Value for you:** **Conditional** – Useful when you decide to validate metadata automatically; it will not resolve the meanings of your fields.
    **External signals:** [GitHub](https://github.com/json-schema-org/understanding-json-schema): 1,507 stars, 310 forks; checked 2026-09-26. Parent documentation-project signal.

14. [Obsidian Bases](https://help.obsidian.md/bases) · Documentation  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 10 / 90
    **Description:** Documentation for viewing and filtering file properties in Obsidian.  
    **Read:** properties and views; optional [source introduction](https://github.com/obsidianmd/obsidian-help/blob/master/en/Bases/Introduction%20to%20Bases.md).  
    **Value for you:** **Conditional** – Useful if you choose file-based dashboards after settling what the records should represent.
    **External signals:** [GitHub](https://github.com/obsidianmd/obsidian-help): 1,925 stars, 537 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

15. [Dataview metadata](https://blacksmithgu.github.io/obsidian-dataview/annotation/add-metadata/) · Documentation  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 10 / 90
    **Description:** Documentation of the metadata Dataview can read from pages and list or task items.  
    **Read:** page metadata and list/task-item metadata.  
    **Value for you:** **Conditional** – Useful if your chosen dashboard needs item-level queries; choosing a plugin before the data model may add work.
    **External signals:** [GitHub](https://github.com/blacksmithgu/obsidian-dataview): 9,360 stars, 569 forks; checked 2026-09-26. Parent project signal.

16. [Docling: document representation](https://docling-project.github.io/docling/concepts/docling_document/) · Documentation  
    **Level:** Intermediate–Advanced (approx.)  
    **Theory / practice:** 30 / 70
    **Description:** A concrete document model representing content, hierarchy, tables, layout, and provenance together.  
    **Read:** basic structure and grouping examples.  
    **Value for you:** **Conditional** – Useful if importing PDFs or Word documents while preserving structure and traceability.  
    **Notes:** Documentation inspected; extraction quality, installation cost, and suitability for your files remain untested.  
    **External signals:** [GitHub](https://github.com/docling-project/docling): 67,960 stars, 4,926 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

17. [GraphRAG paper](https://www.microsoft.com/en-us/research/publication/from-local-to-global-a-graph-rag-approach-to-query-focused-summarization/) and [documentation](https://microsoft.github.io/graphrag/) · Paper and documentation  
    **Level:** Advanced (approx.)  
    **Theory / practice:** 80 / 20
    **Description:** A research approach and implementation documentation for graph-based retrieval and synthesis.  
    **Read:** abstract, system overview, results, and limitations.  
    **Value for you:** **Conditional** – Worth deeper study if ordinary links and search fail on cross-source questions; it is not an established prerequisite for your vault.
    **External signals:** [GitHub](https://github.com/microsoft/graphrag): 36,105 stars, 3,802 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

18. [Noy and McGuinness: Ontology Development 101](https://protege.stanford.edu/publications/ontology_development/ontology101-noy-mcguinness.html) · Guide  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 45 / 55
    **Description:** A worked introduction to defining a domain through concepts, properties, relationships, and instances.  
    **Read:** scope and competency questions, classes versus instances, properties, and iterative revision.  
    **Value for you:** **Conditional** – Revisit competency questions and modeling decisions if a specific schema problem remains after practical examples; the introduction is not a prerequisite.  
    **Notes:** Older tooling examples; the conceptual method remains useful, but there is no single correct model and the authors distinguish ontology design from software object design.  
    **External signals:** [ResearchGate](https://www.researchgate.net/publication/243772462_Ontology_Development_101_A_Guide_to_Creating_Your_First_Ontology): 6,499 citations shown on the publication page; checked 2026-09-26.
    **Your review:** “Read only the beginning. Check my edu, I know IA, OOP to some degree.” This is a shared review of Covert, Prater, and Ontology Development 101, not confirmation that any was completed. See [[Harness reading, my reviews]].

### Background, familiar, or overlapping

19. [NN/g: Information Architecture Study Guide](https://www.nngroup.com/articles/ia-study-guide/) · Study guide  
    **Level:** Beginner–Intermediate (approx.)  
    **Theory / practice:** 40 / 60
    **Description:** A curated collection with recommended reading order within organization principles, research methods, and navigation design.  
    **Read:** Information Architecture and Organization Principles; card sorting and tree testing when evaluating a proposed structure.  
    **Value for you:** **High** – Supplies an established study path for categories and findability that can help test whether your vault organization makes sense.  
    **Notes:** Website navigation details are less relevant; use selected readings as an alternative to the Covert and Prater introductions in this category.  
    **External signals:** [Similarweb](https://www.similarweb.com/website/nngroup.com/): nngroup.com global traffic rank #84,510; checked 2026-09-26. Domain-level reach, not a rating of this guide.

20. [Obsidian Markdown skill](https://github.com/kepano/obsidian-skills/blob/main/skills/obsidian-markdown/SKILL.md) · Skill  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 5 / 95
    **Description:** A practical reference for Obsidian-flavored Markdown and note features.  
    **Read:** properties, links, embeds, and syntax examples.  
    **Value for you:** **Moderate** – Useful as an agent reference when implementing note conventions; much may already be familiar to you.
    **External signals:** [GitHub](https://github.com/kepano/obsidian-skills): 48,881 stars, 3,484 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

21. [Forte: PARA](https://fortelabs.com/blog/para/) · Article  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 35 / 65
    **Description:** An organizational approach distinguishing projects, ongoing responsibilities, resources, and archives.  
    **Read:** the four roles and examples.  
    **Value for you:** **Moderate** – Offers useful role distinctions, but your existing domain structure may already cover much of them.
    **External signals:** [Goodreads](https://www.goodreads.com/book/show/123174805-the-para-method): the later book dedicated to the same PARA method is rated 4.07/5 from 3,214 ratings; checked 2026-09-26. Related-method signal, not a rating of the linked article.

22. [Sophia Prater: Object-Oriented UX](https://alistapart.com/article/object-oriented-ux/) · Article  
    **Level:** Beginner–Intermediate (approx.)  
    **Theory / practice:** 25 / 75
    **Description:** A worked method for mapping the things in a system, their attributes, and their relationships before designing workflows.  
    **Read:** object mapping and the worked example.  
    **Value for you:** **Moderate** – You already know IA/OOP to some degree; use the worked object map only when it adds a missing modeling step.  
    **Notes:** Written for product design; apply the modeling concepts selectively to notes rather than importing a complete UX process.  
    **External signals:** [Similarweb](https://www.similarweb.com/website/alistapart.com/): alistapart.com global traffic rank #601,862; checked 2026-09-26. Domain-level reach, not a rating of this article.
    **Your review:** “Read only the beginning. Check my edu, I know IA, OOP to some degree.” This is a shared review of Covert, Prater, and Ontology Development 101, not confirmation that any was completed. See [[Harness reading, my reviews]].

23. [Abby Covert: How to Make Sense of Any Mess](https://abbycovert.com/make-sense/) · Book  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 25 / 75
    **Description:** A practical introduction to information architecture with exercises for defining a problem and organizing its information.  
    **Read:** “State Your Intent,” “Face Reality,” and “Play with Structure”; use the exercises on one small vault problem.  
    **Value for you:** **Moderate** – Your review suggests limited immediate benefit from introductory IA; keep the exercises as optional reference for a concrete organization problem.  
    **Notes:** The author links a free online edition; this recommendation is based on the overview and selected material, not a full-book assessment.  
    **External signals:** [Goodreads](https://www.goodreads.com/book/show/23523078-how-to-make-sense-of-any-mess): 3.85/5 from 1,624 ratings in the indexed result retrieved 2026-09-25; the result was crawled four months earlier and the live rating could not be refreshed. Work-level rating, not specific to the expanded edition.
    **Your review:** “Read only the beginning. Check my edu, I know IA, OOP to some degree.” This is a shared review of Covert, Prater, and Ontology Development 101, not confirmation that any was completed. See [[Harness reading, my reviews]].



## Planning and delegation

Planning and work procedures. Continuity examples are in [[#Memory and continuity]]. Research details: [[Harness research#Selected skills from Sasha's lead and first-party examples]].

Work records, bounded effort, decisions, and workflow friction first. Planning machinery is conditional; handoff remains an optional reference because it overlaps with Alex.

### Useful now

1. [Anthropic: task management](https://github.com/anthropics/knowledge-work-plugins/blob/main/productivity/skills/task-management/SKILL.md) · Skill  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 10 / 90
    **Description:** A Markdown-based procedure for representing and updating work and waiting states.  
    **Read:** work records, state changes, and waiting.  
    **Value for you:** **Moderate** – Offers a concrete comparison for your task system; its fixed layout is not automatically a fit.
    **External signals:** [GitHub](https://github.com/anthropics/knowledge-work-plugins): 25,621 stars, 3,032 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

2. [Shape Up: Set Boundaries](https://basecamp.com/shapeup/1.2-chapter-03) and [Show Progress](https://basecamp.com/shapeup/3.4-chapter-13) · Book chapters  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 35 / 65
    **Description:** Two chapters on setting an investment boundary and representing uncertainty and progress.  
    **Read:** appetite and uncertainty versus execution.  
    **Value for you:** **High** – Helps limit harness-development effort and describe actual progress without letting the work keep expanding.
    **External signals:** [Goodreads](https://www.goodreads.com/author/show/2812472.Ryan_Singer): Shape Up is rated 4.25/5 from 2,941 ratings; checked 2026-09-26. Book-level reader signal for the source containing these chapters.

3. [Nygard: decision records](https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions) · Article  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 10 / 90
    **Description:** A concise format for recording a decision’s context, status, and consequences.  
    **Read:** context, decision, status, and consequences.  
    **Value for you:** **High** – Can help preserve your choices and rationale without treating every discussion as a decision.
    **External signals:** [Abstractopedia](https://abstractopedia.org/references/ref-90d26a571847/): the source is cited by 3 indexed artifacts there; checked 2026-09-26. Narrow index count, not a general citation metric.

4. [Anthropic: process optimization](https://github.com/anthropics/knowledge-work-plugins/blob/main/operations/skills/process-optimization/SKILL.md) · Skill  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 15 / 85
    **Description:** A procedure for inspecting workflow steps, handoffs, waiting, and rework.  
    **Read:** steps, handoffs, delays, and rework.  
    **Value for you:** **High** – May reveal where your joint work with agents spends capacity before you add more automation.
    **External signals:** [GitHub](https://github.com/anthropics/knowledge-work-plugins): 25,621 stars, 3,032 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

### Supporting depth

5. [GTD: horizons of focus](https://gettingthingsdone.com/2018/12/the-gtd-horizons-of-focus-for-determining-your-priorities/) · Article  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 65 / 35
    **Description:** A distinction between planning horizons from purpose and responsibilities down to actions.  
    **Read:** the different planning horizons.  
    **Value for you:** **High** – Can clarify the relationship between your domains, programs, projects, and current tasks.
    **External signals:** [Goodreads](https://www.goodreads.com/book/show/2858209-getting-things-done): Getting Things Done is rated 4.00/5 from about 170.6k ratings; checked 2026-09-26. Related-method/book signal, not a rating of the linked article.

### Conditional study or implementation

6. [Pocock: Grilling](https://github.com/mattpocock/skills/blob/main/skills/productivity/grilling/SKILL.md) · Skill  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 5 / 95
    **Description:** A questioning procedure that works through unresolved decisions and their dependencies.  
    **Read:** the complete short procedure.  
    **Value for you:** **High** – Helps clarify decisions that need your input while leaving discoverable facts to the agent.  
    **Notes:** Its exhaustive interview style is an example to adapt. The exhaustive style needs limits to protect your capacity.
    **External signals:** [GitHub](https://github.com/mattpocock/skills): 269,713 stars, 22,725 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

7. [Pocock: Wayfinder](https://github.com/mattpocock/skills/blob/main/skills/engineering/wayfinder/SKILL.md) · Skill
    **Selection note:** Optional category reference, outside the main sequence.
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 15 / 85
    **Description:** A planning procedure that represents a large uncertain effort as a map of decision tickets.  
    **Read:** destination, decision map, dependencies, and stopping conditions.  
    **Value for you:** **High** – Can make uncertain harness-development work manageable by mapping decisions and dependencies.  
    **Notes:** Its tracker machinery may be more than you need.
    **External signals:** [GitHub](https://github.com/mattpocock/skills): 269,713 stars, 22,725 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

8. [OpenAI: ExecPlans](https://developers.openai.com/cookbook/articles/codex_exec_plans) · Documentation  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 20 / 80
    **Description:** An archived specification for plans that retain progress, decisions, discoveries, and results.  
    **Read:** progress, decisions, discoveries, and outcomes.  
    **Value for you:** **Moderate** – Useful for selected Work brief fields; adopting the full coding template may increase maintenance.  
    **Notes:** Archived source; not a current default template.
    **External signals:** [Similarweb](https://www.similarweb.com/website/developers.openai.com/): about 4.7M visits over the displayed last-three-month period; parent [openai.com](https://www.similarweb.com/website/openai.com/) global traffic rank #203; checked 2026-09-26. Domain/subdomain reach, not a rating of this resource.

### Background, familiar, or overlapping

9. [Pocock: handoff](https://github.com/mattpocock/skills/blob/main/skills/productivity/handoff/SKILL.md) · Skill
    **Selection note:** Optional category reference, outside the main sequence.
    **Level:** Beginner (approx.)  
    **Theory / practice:** 5 / 95
    **Description:** A short procedure for preparing context for the next session.  
    **Read:** the full short handoff structure.  
    **Value for you:** **High** – Directly supports continuing work without rereading long histories; its storage destination needs local adaptation.
    **External signals:** [GitHub](https://github.com/mattpocock/skills): 269,713 stars, 22,725 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

## Memory and continuity

Context, session continuity, and durable memory. Conceptual introductions and implementation examples are distinguished by Theory / practice. Research details: [[Harness research#Agent continuity, allocation, and improvement sources]].

Start with concrete retrieval and continuity patterns, then study the supporting concepts. Custom storage and execution machinery requires a specific need.

### Useful now

1. [Anthropic: memory management](https://github.com/anthropics/knowledge-work-plugins/blob/main/productivity/skills/memory-management/SKILL.md) · Skill  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 10 / 90
    **Description:** A skill using a small entry layer with deeper information retrieved when needed.  
    **Read:** small entry context and deeper lookup.  
    **Value for you:** **High** – Matches your need for thin guidance and selective access to richer vault context.
    **External signals:** [GitHub](https://github.com/anthropics/knowledge-work-plugins): 25,621 stars, 3,032 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

2. [Anthropic: long-running harnesses](https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents) · Article  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 30 / 70
    **Description:** An account of maintaining progress and verification across multiple agent sessions.  
    **Read:** session handoffs, progress records, and verification.  
    **Value for you:** **High** – Helps you resume research and project work across sessions, with adaptation beyond coding tasks.
    **External signals:** [Similarweb](https://www.similarweb.com/website/anthropic.com/): anthropic.com global traffic rank #5,521; checked 2026-09-26. Domain-level reach, not a rating of this resource.

3. [Google Memory Bank: generation](https://docs.cloud.google.com/gemini-enterprise-agent-platform/scale/memory-bank/generate-memories) and [revisions](https://docs.cloud.google.com/gemini-enterprise-agent-platform/scale/memory-bank/revisions) · Documentation  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 25 / 75
    **Description:** A managed-service example of extracting, consolidating, and revising stored memories.  
    **Read:** extraction, consolidation, and revision history.  
    **Value for you:** **High** – Provides relevant mechanisms for your session-extraction and data-allocation design, without implying cloud migration.
    **External signals:** [Similarweb](https://www.similarweb.com/website/cloud.google.com/): parent cloud.google.com global traffic rank #597 and about 45.9M visits over the displayed last-three-month period; checked 2026-09-26. Domain-level reach, not a rating of this resource.

### Supporting depth

4. [DeepLearning.AI: Agent Memory](https://www.deeplearning.ai/courses/agent-memory-building-memory-aware-agents/) · Course  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 40 / 60
    **Description:** A course on persistent memory stores, memory management, extraction, consolidation, and write-back.  
    **Read:** “Why AI Agents Need Memory” and “Memory Operations: Extraction, Consolidation, and Self-Updating Memory”; implementation lessons only if needed.  
    **Value for you:** **High** – Selected lessons connect your session-extraction questions with explicit memory updates and continuity.  
    **Notes:** Official syllabus inspected, not the full course. Python and basic LLM concepts recommended; Oracle and LangChain implementation. Overlaps with the memory track: use as an alternative guided explanation, not an additional required course.  
    **External signals:** [Similarweb](https://www.similarweb.com/website/deeplearning.ai/): deeplearning.ai global traffic rank #19,367 and about 2.8M visits over the displayed last-three-month period; checked 2026-09-26. Platform-level reach, not a course rating.

5. [Google ADK: state](https://adk.dev/sessions/state/) · Documentation  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 25 / 75
    **Description:** Documentation of explicit session state, its scope, and storage-dependent persistence.  
    **Read:** state, scope, and persistence.  
    **Value for you:** **Moderate** – Clarifies current-work state versus conversation history, without requiring you to adopt ADK.
    **External signals:** [GitHub](https://github.com/google/adk-python): 21,646 stars, 4,065 forks; checked 2026-09-26. Parent implementation signal for ADK.

6. [OpenAI: session-memory cookbook](https://developers.openai.com/cookbook/examples/agents_sdk/session_memory) · Documentation  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 10 / 90
    **Description:** Examples comparing conversation trimming with summarization.  
    **Read:** trimming and summarization examples.  
    **Value for you:** **Moderate** – Helps you understand continuity tradeoffs, but does not document the desktop agent’s internal memory.
    **External signals:** [Similarweb](https://www.similarweb.com/website/developers.openai.com/): about 4.7M visits over the displayed last-three-month period; parent [openai.com](https://www.similarweb.com/website/openai.com/) global traffic rank #203; checked 2026-09-26. Domain/subdomain reach, not a rating of this resource.

7. [OpenAI: compaction](https://developers.openai.com/api/docs/guides/compaction) · Documentation  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 20 / 80
    **Description:** Documentation of an API mechanism for compacting conversation context.  
    **Read:** the context-compaction mechanism.  
    **Value for you:** **Moderate** – Useful for separating provider-managed context from the durable notes you maintain.
    **External signals:** [Similarweb](https://www.similarweb.com/website/developers.openai.com/): about 4.7M visits over the displayed last-three-month period; parent [openai.com](https://www.similarweb.com/website/openai.com/) global traffic rank #203; checked 2026-09-26. Domain/subdomain reach, not a rating of this resource.

8. [Anthropic: Managed Agents architecture](https://www.anthropic.com/engineering/managed-agents) · Article  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 45 / 55
    **Description:** An engineering description separating durable events, model orchestration, execution, and access.  
    **Read:** session events, orchestration, execution, and access boundaries.  
    **Value for you:** **Moderate** – Offers useful architectural boundaries; recreating the hosted service would exceed your present needs.
    **External signals:** [Similarweb](https://www.similarweb.com/website/anthropic.com/): anthropic.com global traffic rank #5,521; checked 2026-09-26. Domain-level reach, not a rating of this resource.

### Conditional study or implementation

9. [Anthropic: memory tool](https://platform.claude.com/docs/en/agents-and-tools/tool-use/memory-tool) · Documentation  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 10 / 90
    **Description:** An API example where the application provides memory operations and reports their outcomes.  
    **Read:** read/write operations and errors.  
    **Value for you:** **Conditional** – Useful if you build memory tooling; for current vault work, the concepts matter more than provider-specific code.
    **External signals:** [Similarweb](https://www.similarweb.com/website/claude.com/): parent claude.com global traffic rank #469 and about 112.6M visits over the displayed last-three-month period; checked 2026-09-26. Parent-domain reach, not a rating of this documentation.

10. [LangMem: semantic memory extraction](https://langchain-ai.github.io/langmem/guides/extract_semantic_memories/) · Documentation  
    **Level:** Advanced (approx.)  
    **Theory / practice:** 10 / 90
    **Description:** Examples of extracting proposed semantic memories and integrating them with storage.  
    **Read:** structured extraction and storage-manager examples.  
    **Value for you:** **Conditional** – Useful if you implement an extraction pipeline; premature adoption would add code and dependencies.
    **External signals:** [GitHub](https://github.com/langchain-ai/langmem): 1,684 stars, 192 forks; checked 2026-09-26. Parent project signal.

11. [LangGraph: persistence](https://docs.langchain.com/oss/python/langgraph/persistence) · Documentation  
    **Level:** Advanced (approx.)  
    **Theory / practice:** 20 / 80
    **Description:** Documentation distinguishing saved execution checkpoints from shared cross-conversation storage.  
    **Read:** thread checkpoints and shared storage.  
    **Value for you:** **Conditional** – Useful if you build resumable workflows; a Markdown handoff alone does not need this machinery.
    **External signals:** [GitHub](https://github.com/langchain-ai/langgraph): 42,293 stars, 7,156 forks; checked 2026-09-26. Parent project signal.

12. [LongMemEval](https://arxiv.org/html/2410.10813v2) · Paper  
    **Level:** Advanced (approx.)  
    **Theory / practice:** 90 / 10
    **Description:** A benchmark studying retrieval, updates, temporal reasoning, and answering from conversation history.  
    **Read:** sections 3–5 and limitations.  
    **Value for you:** **Moderate** – Helps diagnose memory failures, but reading the full experiment is less immediate than fixing a concrete retrieval case.
    **External signals:** [GitHub](https://github.com/xiaowu0162/LongMemEval): 1,107 stars, 85 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

### Background, familiar, or overlapping

13. [Anthropic: context engineering](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents) · Article  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 65 / 35
    **Description:** An engineering account of selecting and maintaining the information available to an agent.  
    **Read:** context selection, retrieval, and continuity.  
    **Value for you:** **Moderate** – Keep for a specific context-design question; your review supports moving on to concrete worked designs.  
    **External signals:** [Similarweb](https://www.similarweb.com/website/anthropic.com/): anthropic.com global traffic rank #5,521; checked 2026-09-26. Domain-level reach, not a rating of this resource.
    **Your review:** “Basic, boring.” See [[Harness reading, my reviews]].

## Skills and improvement

Tools, reusable procedures, evaluations, and improvement. Your review puts evals below current knowledge-structure and workflow needs; their entries remain available for specific problems. Research details: [[Harness research#Evaluation and self-improvement]].

Guidance writing and skill structure first. Evaluation work remains conditional or background in line with your review, even where its general value estimate is high.

### Useful now

1. [Pocock: Writing for agents](https://github.com/mattpocock/skills/blob/main/skills/productivity/writing-for-agents/SKILL.md) · Skill
    **Selection note:** Retained as a main-list candidate for apparent fit with your guidance-writing needs, not because comparative evidence establishes it as the best resource.
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 25 / 75
    **Description:** A reference for context pointers, information hierarchy, and documents consumed by agents.  
    **Read:** context pointers, information hierarchy, and procedure versus reference.  
    **Value for you:** **High** – Helps make your guidance discoverable and usable while reducing duplicated instructions.
    **External signals:** [GitHub](https://github.com/mattpocock/skills): 269,713 stars, 22,725 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

2. [Hugging Face: Building Your First Skill](https://huggingface.co/learn/context-course/unit1/building-skills) · Documentation  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 10 / 90
    **Description:** A tutorial connecting skill instructions, supporting resources, validation, and activation checks.  
    **Read:** structure, validation, and activation debugging.  
    **Value for you:** **High** – Relevant when making your existing workflows reliably discoverable without inventing more procedures.
    **External signals:** [GitHub](https://github.com/huggingface/context-course): 100 stars, 21 forks; checked 2026-09-26. Parent course repository signal.

### Supporting depth

3. [Agent Skills: overview](https://agentskills.io/home) · Documentation  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 45 / 55
    **Description:** The open format overview explains skill folders and how metadata, instructions, and supporting resources load progressively.  
    **Read:** what skills contain; discovery, activation, and execution.  
    **Value for you:** **High** – Clarifies how reusable procedures become discoverable without putting every instruction into permanent context.  
    **Notes:** This describes the format; actual loading behavior and compatibility depend on the client.  
    **External signals:** [GitHub](https://github.com/agentskills/agentskills): 25,692 stars, 1,936 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

4. [OpenAI: Astra skills guidance](https://developers.openai.com/blog/rethinking-skills-and-prompts-for-gpt-6-astra) · Article  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 50 / 50
    **Description:** Provider guidance on context selection, skill routing, and instructions inherited from earlier models.  
    **Read:** context selection, routing, and inherited handholding.  
    **Value for you:** **High** – Relevant to your concern that obvious or outdated rules consume attention without improving work.
    **External signals:** [Similarweb](https://www.similarweb.com/website/developers.openai.com/): about 4.7M visits over the displayed last-three-month period; parent [openai.com](https://www.similarweb.com/website/openai.com/) global traffic rank #203; checked 2026-09-26. Domain/subdomain reach, not a rating of this resource.

5. [OpenAI: using skills for maintenance](https://developers.openai.com/blog/skills-agents-sdk) · Article  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 20 / 80
    **Description:** A worked software-maintenance example separating guidance, reusable skills, and executable scripts.  
    **Read:** roles of repository guidance, skills, and deterministic scripts.  
    **Value for you:** **Moderate** – Clarifies where guidance, reusable procedures, and tool implementation belong in your harness, although the examples are coding-oriented.
    **External signals:** [Similarweb](https://www.similarweb.com/website/developers.openai.com/): about 4.7M visits over the displayed last-three-month period; parent [openai.com](https://www.similarweb.com/website/openai.com/) global traffic rank #203; checked 2026-09-26. Domain/subdomain reach, not a rating of this resource.

6. [Compound Engineering update](https://every.to/p/compound-engineering-gets-an-upgrade) · Article  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 45 / 55
    **Description:** A practitioner account of learning from completed work while revisiting human judgment.  
    **Read:** learning from completed work and revisiting human judgment.  
    **Value for you:** **Moderate** – Offers ideas for your improvement process, with overlap with guidance you already have.
    **External signals:** [Similarweb](https://www.similarweb.com/website/every.to/): every.to global traffic rank #124,213 and about 434.1K visits over the displayed last-three-month period; checked 2026-09-26. Domain-level reach, not a rating of this article.

7. [WikiSkill](https://arxiv.org/html/2608.27454v1) · Paper  
    **Level:** Advanced (approx.)  
    **Theory / practice:** 80 / 20
    **Description:** A research design connecting execution traces, pattern knowledge, and evaluated skill updates.  
    **Read:** section 3.1, appendix E.2, and evaluation limits.  
    **Value for you:** **High** – Closely matches your interest in separating accumulated knowledge from operating instructions; automation remains a later question.
    **External signals:** [GitHub implementation](https://github.com/Stahl-G/wikiskill): 37 stars, 3 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

### Conditional study or implementation

8. [Anthropic: writing effective tools](https://www.anthropic.com/engineering/writing-tools-for-agents) · Article  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 25 / 75
    **Description:** Guidance on designing tool responsibilities, interfaces, results, and checks.  
    **Read:** tool boundaries, descriptions, responses, and testing.  
    **Value for you:** **Moderate** – Helps you judge whether integrations and scripts make agent actions useful and checkable; less immediately actionable with existing tools.
    **External signals:** [Similarweb](https://www.similarweb.com/website/anthropic.com/): anthropic.com global traffic rank #5,521; checked 2026-09-26. Domain-level reach, not a rating of this resource.

9. [Anthropic: skill creator](https://github.com/anthropics/skills/blob/main/skills/skill-creator/SKILL.md) · Skill  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 10 / 90
    **Description:** A skill-development workflow using examples, comparisons, and iterative changes.  
    **Read:** examples, baseline comparison, and iteration.  
    **Value for you:** **High** – Provides a concrete comparison for your existing Create skill process; adoption still needs local judgment.
    **External signals:** [GitHub](https://github.com/anthropics/skills): 178,303 stars, 21,108 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

10. [Anthropic: agent evaluations](https://www.anthropic.com/engineering/demystifying-evals-for-ai-agents) · Article  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 50 / 50
    **Description:** An explanation of agent evaluation using tasks, traces, graders, and human judgment.  
    **Read:** task outcomes, traces, graders, and human calibration.  
    **Value for you:** **High** – Helps you judge harness changes against useful knowledge-work outcomes instead of polished responses alone.
    **External signals:** [Similarweb](https://www.similarweb.com/website/anthropic.com/): anthropic.com global traffic rank #5,521; checked 2026-09-26. Domain-level reach, not a rating of this resource.

11. [OpenAI: skill evaluations](https://developers.openai.com/blog/eval-skills) · Article  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 20 / 80
    **Description:** A method for testing skill behavior through cases, artifacts, and grading.  
    **Read:** test cases, artifacts, grading, and regression checks.  
    **Value for you:** **High** – Helps check whether a changed skill actually reduces repeated failures in your work.  
    **Notes:** Supporting lesson: [ADK: Why evaluate agents](https://adk.dev/evaluate/) (Intermediate, approximate); read actions versus final-response criteria.
    **External signals:** [Similarweb](https://www.similarweb.com/website/developers.openai.com/): about 4.7M visits over the displayed last-three-month period; parent [openai.com](https://www.similarweb.com/website/openai.com/) global traffic rank #203; checked 2026-09-26. Domain/subdomain reach, not a rating of this resource.

12. [Obsidian CLI skill](https://github.com/kepano/obsidian-skills/blob/main/skills/obsidian-cli/SKILL.md) · Skill  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 5 / 95
    **Description:** A skill documenting commands and assumptions for operating an Obsidian vault.  
    **Read:** targeting, commands, and operational assumptions.  
    **Value for you:** **Conditional** – Useful if you choose CLI-based vault operations and verify availability in your setup.
    **External signals:** [GitHub](https://github.com/kepano/obsidian-skills): 48,881 stars, 3,484 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

13. [NVIDIA SkillEvaluator](https://github.com/NVIDIA/SkillEvaluator) · Framework  
    **Level:** Advanced (approx.)  
    **Theory / practice:** 15 / 85
    **Description:** A framework offering structural, duplication, and behavioral skill checks.  
    **Read:** static, duplication, and behavioral checks.  
    **Value for you:** **Conditional** – Useful when your skill collection and test environment justify automation; static checks alone are insufficient.
    **External signals:** [GitHub](https://github.com/NVIDIA/SkillEvaluator): 514 stars, 56 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

14. [Microsoft SkillOpt](https://github.com/microsoft/SkillOpt) · Framework  
    **Level:** Advanced (approx.)  
    **Theory / practice:** 20 / 80
    **Description:** An implementation of bounded skill optimization with evaluation-based acceptance.  
    **Read:** bounded edits, rejected attempts, and acceptance checks.  
    **Value for you:** **Conditional** – Useful only when you have representative tasks, scoring, and enough infrastructure to evaluate changes reliably.
    **External signals:** [GitHub](https://github.com/microsoft/SkillOpt): 17,495 stars, 1,634 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

15. [DSPy tutorials](https://dspy.ai/3.0.0/tutorials/) · Documentation and tutorials  
    **Level:** Advanced (approx.)  
    **Theory / practice:** 15 / 85
    **Description:** Tutorials for structured LLM programs, retrieval, evaluation, and optimizing program behavior.  
    **Read:** structured extraction, basic RAG, and evaluation before optimization.  
    **Value for you:** **Conditional** – Relevant if you build and evaluate repeatable extraction or research programs; requires coding and representative test cases.  
    **Notes:** Earlier tutorial inspection informed this recommendation; the versioned page could not be fetched during consolidation. Use the [project](https://github.com/stanfordnlp/dspy) to locate current documentation before implementation.  
    **External signals:** [GitHub](https://github.com/stanfordnlp/dspy): 38,287 stars, 3,357 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

### Background, familiar, or overlapping

16. [Hamel Husain: A Field Guide to Rapidly Improving AI Products](https://hamel.dev/blog/posts/field-guide/) · Article  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 25 / 75
    **Description:** A practitioner guide to error analysis, inspecting real interactions, and maintaining useful evaluation criteria.  
    **Read:** error analysis, simple data viewers, domain-expert judgment, and trust in evaluations.  
    **Value for you:** **Conditional** – Use when a specific recurring failure warrants error analysis; your review puts eval-focused study behind concrete knowledge and workflow design.  
    **Notes:** Consulting examples and reported outcomes are not controlled evidence for a personal harness.  
    **External signals:** [O’Reilly Radar](https://www.oreilly.com/radar/a-field-guide-to-rapidly-improving-ai-products/) republishes the article; [Similarweb](https://www.similarweb.com/website/oreilly.com/) ranks oreilly.com about #15,928 globally; checked 2026-09-26. Publisher/domain reach, not an article rating.
    **Your review:** “Skimmed, havent found much use. Evals are not my top priority, i guess.” See [[Harness reading, my reviews]].

17. [Hugging Face: Dummy Agent Library](https://huggingface.co/learn/agents-course/unit1/dummy-agent-library) · Documentation  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 10 / 90
    **Description:** A small teaching example contrasting generated observations with executed tool results.  
    **Read:** the tool-execution example.  
    **Value for you:** **Moderate** – Helps you distinguish invented observations from returned tool evidence; skip it if that foundation is already clear.
    **External signals:** [GitHub](https://github.com/huggingface/agents-course): 32,880 stars, 2,363 forks; checked 2026-09-26. Parent course repository signal.

18. [SkillsBench](https://arxiv.org/abs/2602.12670v4) · Paper  
    **Level:** Advanced (approx.)  
    **Theory / practice:** 90 / 10
    **Description:** A benchmark comparing skills across tasks and model/harness combinations.  
    **Read:** design, results, and limitations.  
    **Value for you:** **Moderate** – Can inform how you judge skill claims, but does not choose the right skills for your vault.
    **External signals:** [SkillsBench citations](https://www.skillsbench.ai/citations): about 130 academic citations in an internal June 2026 count across Google Scholar, Semantic Scholar, and arXiv; checked 2026-09-26.

19. [Evaluating AGENTS.md](https://arxiv.org/html/2602.11988v1) · Paper  
    **Level:** Advanced (approx.)  
    **Theory / practice:** 90 / 10
    **Description:** A study of how repository guidance affects tested coding-agent behavior.  
    **Read:** experimental setup, findings, and transfer limits.  
    **Value for you:** **Moderate** – Provides evidence against adding instructions indiscriminately; transfer to your knowledge work is limited.
    **External signals:** [Similarweb](https://www.similarweb.com/website/arxiv.org/): arxiv.org global traffic rank #2,255 and about 26.2M visits over the displayed last-three-month period; checked 2026-09-26. Platform-level reach, not a paper citation count.

20. [ACE](https://arxiv.org/html/2510.04618v1) · Paper  
    **Level:** Advanced (approx.)  
    **Theory / practice:** 80 / 20
    **Description:** A research approach separating task execution, reflection, and context curation.  
    **Read:** execution, reflection, curation, and reported failures.  
    **Value for you:** **Moderate** – Useful for understanding improvement loops and their failure modes; your immediate need may be a simpler reviewed process.
    **External signals:** [GitHub project](https://github.com/ace-agent/ace): 1,333 stars, 170 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

## Architecture and human collaboration

Architecture and human-control references. Your reviewed introductions are retained here, outside the current main route. Research details: [[Harness research#Research findings and evidence]].

Concrete environment design and correction/control guidance first. Reviewed overviews, low-applicability engineering material, and research surveys are later references.

### Useful now

1. [OpenAI: harness engineering](https://openai.com/index/harness-engineering/) · Article  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 35 / 65
    **Description:** An engineering account of maintained knowledge, navigation, and inspectable agent work.  
    **Read:** maintained knowledge, navigation, and inspectable artifacts.  
    **Value for you:** **High** – Offers concrete patterns relevant to your vault, although the setting is software development.
    **External signals:** [Similarweb](https://www.similarweb.com/website/openai.com/): openai.com global traffic rank #203 and about 204.3M visits over the displayed last-three-month period; checked 2026-09-26. Domain-level reach, not a rating of this resource.

2. [Microsoft HAX: correction and control](https://www.microsoft.com/en-us/haxtoolkit/library/) · Documentation  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 25 / 75
    **Description:** Guidelines for designing AI interactions that support correction, feedback, and user control.  
    **Read:** guidelines 9, 14, 15, and 17.  
    **Value for you:** **High** – Helps keep interactions correctable while reducing correction effort and preventing tentative ideas becoming assumed decisions.  
    **Notes:** Supporting evidence: [study overview](https://www.microsoft.com/en-us/research/publication/guidelines-for-human-ai-interaction/) and [CHI paper](https://www.microsoft.com/en-us/research/wp-content/uploads/2019/01/Guidelines-for-Human-AI-Interaction-camera-ready.pdf); methods and limits are optional advanced reading.
    **External signals:** [Similarweb](https://www.similarweb.com/website/microsoft.com/): microsoft.com global traffic rank #32; checked 2026-09-26. Domain-level reach, not a rating of HAX.

### Supporting depth

3. [Harness engineering for coding agent users](https://martinfowler.com/articles/harness-engineering.html) · Article  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 45 / 55
    **Description:** An explanation of shaping the environment and feedback around existing coding agents.  
    **Read:** context, constraints, feedback, and the distinction between using a harness and developing agent applications.  
    **Value for you:** **High** – Helps focus your effort on the guidance and work environment you control in your existing setup.  
    **Notes:** Published on Martin Fowler’s site; coding examples require adaptation to knowledge work.  
    **External signals:** [Similarweb](https://www.similarweb.com/website/martinfowler.com/): martinfowler.com global traffic rank #113,710; checked 2026-09-26. Domain-level reach, not a rating of this article.

4. [NN/g: Designing AI Products and Features](https://www.nngroup.com/articles/designing-ai-study-guide/) · Study guide  
    **Level:** Beginner–Intermediate (approx.)  
    **Theory / practice:** 40 / 60
    **Description:** A curated collection on deciding AI’s value and designing understandable AI interactions.  
    **Read:** strategy and value proposition, prompt assistance, and selected agent-control examples.  
    **Value for you:** **High** – Helps judge whether a proposed feature reduces your work and preserves understandable human control.  
    **Notes:** Product-design examples need adaptation for personal use; complements the HAX entry in this category.  
    **External signals:** [Similarweb](https://www.similarweb.com/website/nngroup.com/): nngroup.com global traffic rank #84,510; checked 2026-09-26. Domain-level reach, not a rating of this guide.

5. [Anthropic: trustworthy agents framework](https://www.anthropic.com/research/trustworthy-agents) · Article  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 80 / 20
    **Description:** A framework distinguishing the model, harness, tools, and environment when analyzing agent behavior.  
    **Read:** model, harness, tools, and environment distinctions.  
    **Value for you:** **High** – Helps identify whether a recurring problem needs better data, a workflow change, or a tool fix.
    **External signals:** [Similarweb](https://www.similarweb.com/website/anthropic.com/): anthropic.com global traffic rank #5,521; checked 2026-09-26. Domain-level reach, not a rating of this resource.

6. [OpenAI: Codex as a platform](https://developers.openai.com/blog/codex-as-a-platform) · Documentation  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 45 / 55
    **Description:** Documentation separating a reusable execution harness from its surrounding application.  
    **Read:** execution harness versus surrounding application.  
    **Value for you:** **Moderate** – Helps avoid rebuilding capabilities already supplied by your agent environment.
    **External signals:** [Similarweb](https://www.similarweb.com/website/developers.openai.com/): about 4.7M visits over the displayed last-three-month period; parent [openai.com](https://www.similarweb.com/website/openai.com/) global traffic rank #203; checked 2026-09-26. Domain/subdomain reach, not a rating of this resource.

### Conditional study or implementation

7. [Model Context Protocol: architecture](https://modelcontextprotocol.io/docs/learn/architecture) · Documentation  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 40 / 60
    **Description:** An overview of hosts, clients, servers, and the tools, resources, and prompts exchanged through MCP.  
    **Read:** participants, core primitives, and the discovery/tool-execution example; skip transport details initially.  
    **Value for you:** **Moderate** – Helps distinguish an integration interface from the agent’s instructions and knowledge design.  
    **Notes:** The overview redirected to version 2026-07-28 during inspection; implementation must match the version supported by your clients.  
    **External signals:** [GitHub](https://github.com/modelcontextprotocol/modelcontextprotocol): 9,306 stars, 1,833 forks; checked 2026-09-26. Parent MCP project signal.

8. [LangChain: Deep Agents overview](https://docs.langchain.com/oss/python/deepagents/overview) · Framework documentation  
    **Level:** Intermediate–Advanced (approx.)  
    **Theory / practice:** 35 / 65
    **Description:** A concrete agent harness combining planning, filesystem context, delegation, and execution support.  
    **Read:** architecture and the roles of planning, files, subagents, and memory; skip installation initially.  
    **Value for you:** **Conditional** – Useful as an implementation comparison if existing agents cannot support a specific workflow.  
    **Notes:** Documentation inspected; no installation or tests. Not a recommendation to replace your current agent environment.  
    **External signals:** [GitHub](https://github.com/langchain-ai/deepagents): 29,766 stars, 4,182 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

9. [Anthropic: multi-agent research system](https://www.anthropic.com/engineering/multi-agent-research-system) · Article  
    **Level:** Intermediate–Advanced (approx.)  
    **Theory / practice:** 40 / 60
    **Description:** A production research-system account of orchestration, delegation, tool use, and evaluation.  
    **Read:** task decomposition, delegation boundaries, coordination costs, and evaluation.  
    **Value for you:** **Conditional** – Useful if your research workload warrants parallel agents; added coordination and token costs may outweigh benefits for smaller tasks.  
    **Notes:** Provider case study and reported results, not proof that multi-agent work is appropriate for your vault.  
    **External signals:** [Similarweb](https://www.similarweb.com/website/anthropic.com/): anthropic.com global traffic rank #5,521; checked 2026-09-26. Domain-level reach, not a rating of this resource.

### Background, familiar, or overlapping

10. [Anthropic: Building effective agents](https://www.anthropic.com/engineering/building-effective-agents) · Article  
    **Level:** Beginner–Intermediate (approx.)  
    **Theory / practice:** 50 / 50
    **Description:** An introduction to workflows, autonomous agents, and composable patterns for LLM applications.  
    **Read:** workflows versus agents, when to use each, and the pattern overview.  
    **Value for you:** **Moderate** – Retain as a pattern reference; your skim did not identify an immediate application, so it is outside the current main route.  
    **Notes:** Provider engineering guidance and examples, not proof that any pattern will improve your vault.  
    **External signals:** [Similarweb](https://www.similarweb.com/website/anthropic.com/): anthropic.com global traffic rank #5,521; checked 2026-09-26. Domain-level reach, not a rating of this resource.
    **Your review:** “Skimmed. Not sure what to apply. Seems basic.” See [[Harness reading, my reviews]].

11. [Google: architecture components](https://docs.cloud.google.com/architecture/choose-agentic-ai-architecture-components) · Documentation  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 55 / 45
    **Description:** A component map of the interfaces, tools, state, memory, and runtime used in agent applications.  
    **Read:** component roles and architecture choices; skip deployment setup.  
    **Value for you:** **Moderate** – Reference for component names and responsibilities; your review indicates little immediate learning value.  
    **External signals:** [Similarweb](https://www.similarweb.com/website/cloud.google.com/): cloud.google.com global traffic rank #597 and about 45.9M visits over the displayed last-three-month period; checked 2026-09-26. Domain-level reach, not a rating of this page.
    **Your review:** “Skimmed. Boring, basic, dont know what to apply” See [[Harness reading, my reviews]].

12. [HumanLayer: 12 Factor Agents](https://github.com/humanlayer/12-factor-agents) · Guide  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 35 / 65
    **Description:** A set of engineering principles for explicit context, state, control flow, tool use, and focused agents.  
    **Read:** factors 3, 5, 6, 8, and 10; skim the overall map first.  
    **Value for you:** **Conditional** – Revisit only if you need to build or debug agent machinery; your current assessment is low applicability. The guide covers broader LLM software, but its implementation focus still limits immediate fit.  
    **Notes:** Production software examples need adaptation; this is practitioner guidance rather than an evaluated personal-system template.  
    **External signals:** [GitHub](https://github.com/humanlayer/12-factor-agents): 26,388 stars, 1,978 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.
    **Your review:** “Its coding agents. Not applicable to me, i guess” See [[Harness reading, my reviews]].

13. [Measuring Agents in Production](https://arxiv.org/html/2512.04123v4) · Paper  
    **Level:** Advanced (approx.)  
    **Theory / practice:** 90 / 10
    **Description:** An observational study of production and pilot agent systems and their engineering practices.  
    **Read:** methods and sections 5–7.  
    **Value for you:** **Moderate** – Provides professional context without establishing a proven personal harness or a ready-made workflow.
    **External signals:** [Similarweb](https://www.similarweb.com/website/arxiv.org/): arxiv.org global traffic rank #2,255 and about 26.2M visits over the displayed last-three-month period; checked 2026-09-26. Platform-level reach, not a paper citation count.

14. [Human–AI collaboration meta-analysis](https://www.nature.com/articles/s41562-024-02024-1) · Paper  
    **Level:** Advanced (approx.)  
    **Theory / practice:** 95 / 5
    **Description:** A meta-analysis comparing human–AI combinations with human and AI performance separately.  
    **Read:** abstract, comparison baselines, and limitations.  
    **Value for you:** **High** – Directly relevant to whether added review improves outcomes enough to justify your attention; findings are not a prescription for your system.
    **External signals:** [Nature Human Behaviour](https://doi.org/10.1038/s41562-024-02024-1): 631 citations, about 229k accesses, and Altmetric 656; checked 2026-09-26.

## Supplied systems and comparisons

Concrete system designs and supplied comparisons, including Claude Obsidian and Ars Contexta. Selected entries are copied into [[#Main sequence]]. Research details: [[Harness research#Companion references]] and [[Harness research#Other system examples and discovery sources]].

Worked vault designs and usable structures first; broader system adoption remains conditional. Alex is retained as a supporting comparison, not treated as something you must reread in full.

### Useful now

1. [Claude Obsidian](https://github.com/AgriciDaniel/claude-obsidian) · Framework  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 20 / 80
    **Description:** A documented framework for turning preserved sources into linked, cited notes and maintaining the resulting vault.  
    **Read:** overview, “From source to living knowledge,” and [sample vault](https://github.com/AgriciDaniel/claude-obsidian/tree/main/examples/sample-vault).  
    **Value for you:** **High** – Provides an end-to-end example for your ingestion and data-structuring questions.  
    **Notes:** Documentation inspected; the framework was not installed or tested here. Installation suitability remains untested.
    **External signals:** [GitHub](https://github.com/AgriciDaniel/claude-obsidian): 15,214 stars, 1,514 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

2. [Ars Contexta: three-space architecture](https://github.com/agenticnotetaking/arscontexta/blob/main/reference/three-spaces.md) · Framework  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 35 / 65
    **Description:** A reference design separating an agent’s own context, durable knowledge, and operating records.  
    **Read:** self, notes, and ops; compare [overview](https://github.com/agenticnotetaking/arscontexta) and [kernel](https://github.com/agenticnotetaking/arscontexta/blob/main/reference/kernel.yaml) selectively.  
    **Value for you:** **High** – Helps distinguish journal evidence, durable knowledge, and temporary task state in your vault.  
    **Notes:** Optional claim checks: [MOC rationale](https://github.com/agenticnotetaking/arscontexta/blob/main/methodology/MOCs%20are%20attention%20management%20devices%20not%20just%20organizational%20tools.md) with [Gloria Mark interview](https://news.gallup.com/businessjournal/23146/too-many-interruptions-work.aspx); [context discussion](https://github.com/agenticnotetaking/arscontexta/blob/main/methodology/LLM%20attention%20degrades%20as%20context%20fills.md) with [Lost in the Middle](https://arxiv.org/abs/2307.03172); [module-adoption guidance](https://github.com/agenticnotetaking/arscontexta/blob/main/methodology/friction-driven%20module%20adoption%20prevents%20configuration%20debt%20by%20adding%20complexity%20only%20at%20pain%20points.md). See the research note’s qualifications; these do not all need reading now.
    **External signals:** [GitHub](https://github.com/agenticnotetaking/arscontexta): 3,496 stars, 231 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

3. [[Domains/System/Harness development/Alexs notes formatting SKILL|Alex’s formatting skill]] · Skill  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 10 / 90
    **Description:** A supplied skill with formatting principles and layouts for common knowledge-work documents.  
    **Read:** core principles and research, project, handoff, and decision layouts.  
    **Value for you:** **High** – Offers concrete structures for the notes and work records you already use.
    **External signals:** Not applicable — local/private vault artifact; no public popularity or citation metric is expected.

4. [Obsidian agent vault template: Skills Index](<C:/Users/Admin/OneDrive/Documents/Obsidian/Vault additional/System/Harnesses/obsidian-agent-vault-template/Skills/Skills Index.md>) · Framework  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 5 / 95
    **Description:** A concrete index showing when skills apply, their outputs, dependencies, and boundaries.  
    **Read:** triggers, expected outputs, dependencies, and boundaries.  
    **Value for you:** **High** – Directly useful for improving discovery and routing within your existing skill collection.  
    **Notes:** Parent [repository](https://github.com/louisfb01/obsidian-agent-vault-template).
    **External signals:** [GitHub](https://github.com/louisfb01/obsidian-agent-vault-template): 48 stars, 14 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

### Supporting depth

5. [[Notes Sacha|Sasha’s notes]] · Notes  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 70 / 30
    **Description:** Your short record of Sasha’s ideas about concepts, metadata, evidence, maps, and protocols.  
    **Read:** the whole short note.  
    **Value for you:** **High** – Directly relevant to your data-structuring interests, while missing definitions need clarification.  
    **Notes:** These are leads, not Sasha’s complete specification.
    **External signals:** Not applicable — local/private vault artifact; no public popularity or citation metric is expected.

6. [GBrain: what schemas unlock](<C:/Users/Admin/OneDrive/Documents/Obsidian/Vault additional/System/Harnesses/gbrain/docs/what-schemas-unlock.md>) · Framework documentation  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 40 / 60
    **Description:** Documentation of typed entities, relationships, and the system of record in a knowledge framework.  
    **Read:** schema explanation, then [system of record](<C:/Users/Admin/OneDrive/Documents/Obsidian/Vault additional/System/Harnesses/gbrain/docs/architecture/system-of-record.md>).  
    **Value for you:** **Moderate** – Relevant to your schema questions, but evidence-preservation differences and untested claims limit direct adoption.  
    **Notes:** Parent [repository](https://github.com/garrytan/gbrain); the local collection is documentation, not a working installation.
    **External signals:** [GitHub](https://github.com/garrytan/gbrain): 30,331 stars, 4,543 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

7. [[Alexs exocortex|Alex’s Exocortex]] · Framework  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 35 / 65
    **Description:** A supplied template covering vault structure, source layers, project records, and session routines.  
    **Read:** principles, data layers, project records, and session routines.  
    **Value for you:** **High** – One of your primary references for foundational changes, with conventions to select rather than import wholesale.
    **External signals:** Not applicable — local/private vault artifact; no public popularity or citation metric is expected.

### Conditional study or implementation

8. [[aim-harness-setup|AIM setup]] · Framework  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 20 / 80
    **Description:** A supplied harness guide for inventorying the setup and diagnosing gaps across components.  
    **Read:** inventory, component diagnosis, and workflow gaps.  
    **Value for you:** **Moderate** – Useful as a comparison, but a full setup pass may duplicate existing work and expand scope.
    **External signals:** Not applicable — local/private vault artifact; no public popularity or citation metric is expected.

9. [[aim-harness-setup-selfdev|AIM self-development]] · Skill  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 10 / 90
    **Description:** A supplied maintenance skill covering repeated problems and targeted improvements.  
    **Read:** maintenance questions and improvement loop; [public source](https://github.com/ai-mindset-org/harness-setup-selfdev/blob/main/SKILL.md).  
    **Value for you:** **Moderate** – Can help refine your existing improvement skill; another parallel review process may add burden.
    **External signals:** [GitHub](https://github.com/ai-mindset-org/harness-setup-selfdev): 3 stars, 1 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

10. [LifeOS architecture](https://docs.ourlifeos.ai/LifeosSystemArchitecture/) · Framework  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 40 / 60
    **Description:** A broad personal-system design linking direction, work records, knowledge, and freshness.  
    **Read:** overview, then [Work System](https://docs.ourlifeos.ai/Work__WorkSystem/) and [Freshness](https://docs.ourlifeos.ai/Freshness__FreshnessSystem/).  
    **Value for you:** **Moderate** – Useful for comparing relationships, but its breadth and platform assumptions could distract from bounded changes.  
    **Notes:** Parent [repository](https://github.com/danielmiessler/LifeOS); optional design comparison.
    **External signals:** [GitHub](https://github.com/danielmiessler/LifeOS): 19,138 stars, 2,479 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

### Background, familiar, or overlapping

11. [Founder OS #32 transcript](<C:/Users/Admin/OneDrive/Documents/Obsidian/Vault additional/System/Агенты/Расшифровки/09 — Founder OS #32 — как собрать personal OS для саморазвития_ About Me_ агенты и транскрипты.md>) · Transcript  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 50 / 50
    **Description:** A supplied transcript discussing personal context, reflection, and its use in ongoing work.  
    **Read:** 15–20, 25–35, and 80–85 minute segments.  
    **Value for you:** **Moderate** – Relevant to making existing personal notes affect useful decisions rather than merely expanding your profile.  
    **Notes:** Original [video](https://www.youtube.com/watch?v=tINOI67z99M). AI-produced supplied material; transcript and speaker limitations remain in the research note.
    **External signals:** Not applicable — local/private vault artifact; no public popularity or citation metric is expected.

## Learning methods

Research details: [[Harness research#Three ways to study this with limited capacity]].

Start with selecting and using learning material; teaching automation and research evidence are optional follow-ups. Pocock is not prioritized by author.

### Useful now

1. [Founder OS #31 transcript](<C:/Users/Admin/OneDrive/Documents/Obsidian/Vault additional/System/Агенты/Расшифровки/11 — Founder OS #31 — как AI меняет обучение_ виртуальный студент в чате и зона ближайшего развития.md>) · Transcript  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 60 / 40
    **Description:** A supplied transcript about AI-assisted learning, learner state, recall, and adapting difficulty.  
    **Read:** 5–20 and 30–35 minute segments.  
    **Value for you:** **High** – Relevant to distinguishing what the agent has summarized from what you have actually learned.  
    **Notes:** Original [video](https://www.youtube.com/watch?v=afH-iQhQqcY).
    **External signals:** Not applicable — local/private vault artifact; no public popularity or citation metric is expected.

2. [Diataxis](https://diataxis.fr/) · Documentation  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 55 / 45
    **Description:** A framework distinguishing tutorials, how-to guides, explanations, and reference material.  
    **Read:** tutorial, how-to, reference, and explanation distinctions.  
    **Value for you:** **High** – Helps choose materials that answer your current learning need instead of accumulating another mixed resource list.
    **External signals:** [GitHub](https://github.com/evildmp/diataxis-documentation-framework): 1,242 stars, 203 forks; checked 2026-09-26. Framework repository signal.

### Supporting depth

3. [Pocock: Research](https://github.com/mattpocock/skills/blob/main/skills/engineering/research/SKILL.md) · Skill  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 20 / 80
    **Description:** A skill for framing questions, using primary sources, and producing cited synthesis.  
    **Read:** question framing, primary sources, and synthesis.  
    **Value for you:** **High** – Relevant to improving source-grounded research while reducing broad, repetitive AI-generated reports.
    **External signals:** [GitHub](https://github.com/mattpocock/skills): 269,713 stars, 22,725 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

### Conditional study or implementation

4. [Pocock: Teach](https://github.com/mattpocock/skills/blob/main/skills/productivity/teach/SKILL.md) · Skill
    **Selection note:** Optional category reference, outside the main sequence.
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 5 / 95
    **Description:** A skill describing a structured teaching interaction with practice and feedback.  
    **Read:** practice and feedback procedure.  
    **Value for you:** **High** – Could help turn this reading collection into learning sessions adjusted to your understanding.
    **External signals:** [GitHub](https://github.com/mattpocock/skills): 269,713 stars, 22,725 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

### Background, familiar, or overlapping

5. [Karpicke and Blunt: retrieval practice](https://learninglab.psych.purdue.edu/downloads/2011/2011_Karpicke_Blunt_Science.pdf) · Paper  
    **Level:** Advanced (approx.)  
    **Theory / practice:** 95 / 5
    **Description:** An experiment comparing retrieval practice with other ways of studying science texts.  
    **Read:** abstract, results, and limitations.  
    **Value for you:** **Moderate** – Supports using recall and application in your learning, while the research detail remains optional for everyday use.
    **External signals:** [Metascience Observatory explorer](https://explore.metascienceobservatory.org/papers/W2161621074): 877 citations; source data up to January 2025, checked 2026-09-26.

## Longer courses and study paths

These are alternatives, not a cumulative course list. Start with one route matched to a current need; individual lessons already placed in a topic track are not listed twice.

For a broad agent foundation, compare Microsoft, Google/Kaggle, Hugging Face Agents, and Andrew Ng. For a technical knowledge-assistant project, consider LLM Zoomcamp; Labonne is a broader technical roadmap. Full Stack offers selected system and UX perspectives, with older implementation details. Pydantic and Knowledge Graphs for RAG are targeted extensions only when their implementation problem arises. The Agent Memory course is already in [[#Memory and continuity]].

Priority applies to the selected lessons, not completing courses. Start with the context/skills material closest to your present work; builder curricula require a concrete implementation goal.

### Useful now

1. [Hugging Face: Context Course](https://huggingface.co/learn/context-course/unit0/introduction) · Course  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 35 / 65
    **Description:** A course on context and agent customization through skills, tools, and related mechanisms.  
    **Read:** unit 1 and skill/tool/context mechanisms.  
    **Value for you:** **High** – The selected parts connect directly to your harness work, though command-line and Python prerequisites affect effort.  
    **Notes:** Python and command-line familiarity assumed; the first-skill lesson is already in the skills track.
    **External signals:** [GitHub](https://github.com/huggingface/context-course): 100 stars, 21 forks; checked 2026-09-26. Parent course repository signal.

### Supporting depth

2. [Chip Huyen: AI Engineering](https://github.com/chiphuyen/aie-book/blob/main/ToC.md) · Book  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 55 / 45
    **Description:** A broad book on building AI applications, including evaluation, retrieval, agents, data, and architecture.  
    **Read:** chapters 1, 4, 6, and 10; selected concepts from 2–3.  
    **Value for you:** **High** – A potential longer-term foundation across your questions; selected chapters keep the initial commitment manageable.  
    **Notes:** The link is the contents, not free access to the full book.
    **External signals:** [GitHub](https://github.com/chiphuyen/aie-book): 17,545 stars, 2,558 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

3. [Google/Kaggle: AI Agents Intensive](https://www.kaggle.com/learn-guide/5-day-agents) · Course  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 35 / 65
    **Description:** A systems course connecting agent architecture, tools, memory, quality, and production.  
    **Read:** days 2–4; day 1 as needed.  
    **Value for you:** **High** – A coherent foundation for understanding the whole harness; labs are optional and add setup cost.  
    **Notes:** Optional [2026 successor](https://www.kaggle.com/learn-guide/5-day-agents-vibecoding) (Intermediate, approximate): coding and deployment emphasis; an alternative, not a required sequel. ADK state and evaluation lessons are placed in the memory and skills tracks.
    **External signals:** [Similarweb](https://www.similarweb.com/website/kaggle.com/): kaggle.com global traffic rank #4,239 and about 10.5M visits over the displayed last-three-month period; checked 2026-09-26. Platform-level reach, not a course rating.

4. [Full Stack: LLM Bootcamp, Spring 2023](https://fullstackdeeplearning.com/llm-bootcamp/spring-2023/) · Course  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 45 / 55
    **Description:** A curriculum connecting LLM foundations, augmentation, user experience, evaluation, and deployment.  
    **Read:** Augmented Language Models, UX for Language User Interfaces, and LLMOps.  
    **Value for you:** **Moderate** – Offers an overall system perspective and human-interface considerations often missing from framework tutorials.  
    **Notes:** Published in 2023; implementation details need current documentation. Selected lectures are an alternative perspective, not another complete course requirement.  
    **External signals:** [GitHub](https://github.com/the-full-stack/the-full-stack-website): 1,359 stars, 219 forks; checked 2026-09-26. Parent course-site repository signal.

### Conditional study or implementation

5. [Microsoft: AI Agents for Beginners](https://github.com/microsoft/ai-agents-for-beginners/blob/main/STUDY_GUIDE.md) · Course and study guide  
    **Level:** Beginner–Intermediate (approx.)  
    **Theory / practice:** 25 / 75
    **Description:** An ordered curriculum with goal-based routes through tools, retrieval, workflows, multi-agent systems, and production concerns.  
    **Read:** foundational lessons 1–6, then choose the study guide’s workflow or tool-use route.  
    **Value for you:** **High** – Provides an established coverage checklist and a coherent learning route across agent components.  
    **Notes:** Alternative to Google/Kaggle, Hugging Face Agents, or Andrew Ng, not an additional required course. Current code examples lean toward Microsoft Agent Framework and Azure/Foundry; setup is optional for conceptual reading.  
    **External signals:** [GitHub](https://github.com/microsoft/ai-agents-for-beginners): 75,679 stars, 24,891 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

6. [Hugging Face: Agents Course](https://huggingface.co/learn/agents-course/unit0/introduction) · Course  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 25 / 75
    **Description:** A practical Python course covering agent loops, tools, and frameworks.  
    **Read:** agent loop and tool use before framework-specific units.  
    **Value for you:** **Conditional** – Useful if you want to build the machinery yourself; overlaps with the other builder courses.  
    **Notes:** Dummy Agent Library is already in the skills track. Overlaps with Google/Kaggle and Andrew Ng; choose by preferred depth.
    **External signals:** [GitHub](https://github.com/huggingface/agents-course): 32,880 stars, 2,363 forks; checked 2026-09-26. Parent course repository signal.

7. [DataTalks.Club: LLM Zoomcamp](https://github.com/DataTalksClub/llm-zoomcamp) · Course  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 15 / 85
    **Description:** A practical curriculum for knowledge assistants covering retrieval, agents, orchestration, evaluation, monitoring, and a project.  
    **Read:** agentic RAG, evaluation, and monitoring; complete the project only if building a knowledge assistant is an actual goal.  
    **Value for you:** **Conditional** – A coherent hands-on route if you choose to build your own assistant over the knowledge collection.  
    **Notes:** Python, command-line comfort, and basic Docker familiarity expected. Alternative to other builder curricula; free teaching materials do not remove API or setup costs.  
    **External signals:** [GitHub](https://github.com/DataTalksClub/llm-zoomcamp): 7,342 stars, 1,362 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

8. [DeepLearning.AI: Pydantic for LLM Workflows](https://community.deeplearning.ai/t/new-course-enroll-in-pydantic-for-llm-workflows/863507) · Course  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 15 / 85
    **Description:** A course on structured LLM outputs and validating data before passing it between application components.  
    **Read:** structured-output basics, required-field validation, and tool-calling examples.  
    **Value for you:** **Conditional** – Useful when automating extraction of tasks or records into predictable fields; less immediate for manual Markdown organization.  
    **Notes:** Official announcement inspected; course page access failed during research, and lessons were not taken. Python assumed. Complements JSON Schema; neither resolves the meaning of your fields.  
    **External signals:** [Similarweb](https://www.similarweb.com/website/deeplearning.ai/): deeplearning.ai global traffic rank #19,367 and about 2.8M visits over the displayed last-three-month period; checked 2026-09-26. Platform-level reach, not a course rating.

9. [DeepLearning.AI: Knowledge Graphs for RAG](https://www.deeplearning.ai/courses/knowledge-graphs-rag) · Course  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 25 / 75
    **Description:** A course on representing connected information in a graph and retrieving it for LLM applications.  
    **Read:** graph representation, relationships, and graph queries before the full application exercise.  
    **Value for you:** **Conditional** – Useful if linked questions outgrow ordinary vault search and you choose to build graph-based retrieval.  
    **Notes:** Official overview inspected, not the full course. Neo4j and LangChain examples; overlaps with GraphRAG concepts but teaches a different approach. Access terms may change.  
    **External signals:** [Similarweb](https://www.similarweb.com/website/deeplearning.ai/): deeplearning.ai global traffic rank #19,367 and about 2.8M visits over the displayed last-three-month period; checked 2026-09-26. Platform-level reach, not a course rating.

10. [Andrew Ng: Agentic AI](https://www.deeplearning.ai/courses/agentic-ai) · Course  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 25 / 75
    **Description:** An implementation-oriented course on reflection, tools, planning, and evaluation.  
    **Read:** reflection, tools, planning, and evaluation.  
    **Value for you:** **Conditional** – Useful if you choose a Python builder route; access and overlap should be checked before committing.  
    **Notes:** Python assumed; access terms not verified. Supporting [announcement](https://www.deeplearning.ai/the-batch/check-out-our-course-on-how-to-build-ai-agents). Alternative builder route.
    **External signals:** [Similarweb](https://www.similarweb.com/website/deeplearning.ai/): deeplearning.ai global traffic rank #19,367 and about 2.8M visits over the displayed last-three-month period; checked 2026-09-26. Platform-level reach, not a course rating.

11. [Maxime Labonne: LLM Course](https://github.com/mlabonne/llm-course) · Study path and tutorials  
    **Level:** Intermediate–Advanced (approx.)  
    **Theory / practice:** 30 / 70
    **Description:** A curated roadmap divided into LLM fundamentals, model development, and application engineering, with linked resources and notebooks.  
    **Read:** LLM Engineer track, especially application architecture, retrieval, and evaluation; consult fundamentals only for gaps.  
    **Value for you:** **Moderate** – A useful broad technical map, but model training and deployment detail can divert your limited study capacity.  
    **Notes:** Alternative technical route to the other builder courses. Optional LLM Scientist and fine-tuning material is outside your immediate harness needs.  
    **External signals:** [GitHub](https://github.com/mlabonne/llm-course): 83,142 stars, 9,678 forks; checked 2026-09-26. Repository-level popularity/adoption signal, not a quality score.

12. [Anthropic: human-agent teams](https://academy.claude.com/courses/building-effective-human-agent-teams) · Course  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 45 / 55
    **Description:** An introductory course on roles, delegation, and information access in human-agent teams.  
    **Read:** roles, delegation, and information access.  
    **Value for you:** **Moderate** – Some collaboration concepts transfer, but organizational examples may not fit a single-person system.  
    **Notes:** Organizational examples need adaptation for personal use.
    **External signals:** [Similarweb](https://www.similarweb.com/website/claude.com/): parent claude.com global traffic rank #469 and about 112.6M visits over the displayed last-three-month period; checked 2026-09-26. Parent-domain reach, not a course rating.

13. [Berkeley: LLM Agents 2024](https://llmagents-learning.org/f24) · Course  
    **Level:** Advanced (approx.)  
    **Theory / practice:** 80 / 20
    **Description:** A university lecture series introducing agent research and application topics.  
    **Read:** overview, knowledge assistants, enterprise workflows, and evaluation.  
    **Value for you:** **Conditional** – Useful when a specific research question warrants lecture-level depth; a full pass would be a large detour.
    **External signals:** [Berkeley RDI](https://rdi.berkeley.edu/education) reports 40,000+ learners for its Agentic AI MOOC series; the 2024 overview lecture has [55,787 YouTube views and 806 likes](https://www.youtube.com/watch?v=RM6ZArd2nVc); checked 2026-09-26. Series/course-media reach, not a course rating.

14. [Berkeley: advanced agents 2025](https://llmagents-learning.org/) · Course  
    **Level:** Advanced (approx.)  
    **Theory / practice:** 85 / 15
    **Description:** An advanced lecture series extending agent research topics.  
    **Read:** lectures matching a specific question after the introductory course.  
    **Value for you:** **Conditional** – Best used for a concrete question after foundations, not as a prerequisite for improving your current vault.
    **External signals:** [Berkeley RDI](https://rdi.berkeley.edu/education) reports 40,000+ learners for its Agentic AI MOOC series, which includes the Spring 2025 Advanced LLM Agents MOOC; checked 2026-09-26. Series-level learner reach, not a rating of this course.

### Background, familiar, or overlapping

15. [Anthropic: AI capabilities and limitations](https://academy.claude.com/courses/ai-capabilities-and-limitations) · Course  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 65 / 35
    **Description:** An introductory course on AI capabilities, limitations, and diagnosing failures.  
    **Read:** diagnostic sections; skip familiar basics.  
    **Value for you:** **Moderate** – Use selected diagnostic lessons if they fill a gap; completing familiar basics may not repay your time.
    **External signals:** [Similarweb](https://www.similarweb.com/website/claude.com/): parent claude.com global traffic rank #469 and about 112.6M visits over the displayed last-three-month period; checked 2026-09-26. Parent-domain reach, not a course rating.

16. [Anthropic: AI Fluency](https://academy.claude.com/courses/ai-fluency-framework-foundations) · Course  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 35 / 65
    **Description:** A course on delegating to AI, communicating tasks, and judging its work.  
    **Read:** delegation and discernment.  
    **Value for you:** **Moderate** – Relevant to collaboration, but selected lessons are likely more efficient than completing overlapping introductions.
    **External signals:** [Similarweb](https://www.similarweb.com/website/claude.com/): parent claude.com global traffic rank #469 and about 112.6M visits over the displayed last-three-month period; checked 2026-09-26. Parent-domain reach, not a course rating.

## Local worked examples

Optional comparison material already referenced in the research. These are local working documents or drafts, not validated curricula.

Existing project and skill records first. Query documentation needs a concrete query problem; unconfirmed drafts remain unranked.

### Useful now

1. [[Domains/System/_templates/Project|Project template]] and [[Domains/System/_templates/Work brief|Work brief]] · Templates  
    **Level:** Beginner (approx.)  
    **Theory / practice:** 5 / 95
    **Description:** Local templates proposing project fields and a durable work brief.  
    **Read:** fields, progress, decisions, and completion.  
    **Value for you:** **High** – Lets you improve existing work records instead of adopting another framework’s complete file package.  
    **Notes:** draft status does not establish adoption.
    **External signals:** Not applicable — local/private vault artifact; no public popularity or citation metric is expected.

2. [[Domains/System/Skills/Create skill|Create skill]] and [[Domains/System/_templates/Skill|Skill template]] · Skill and template  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 5 / 95
    **Description:** Your local skill-creation guidance and template.  
    **Read:** structure and checks.  
    **Value for you:** **High** – These are the direct comparison points for applying the skill-development readings without creating duplicate guidance.
    **External signals:** Not applicable — local/private vault artifact; no public popularity or citation metric is expected.

### Conditional study or implementation

3. [[Domains/System/Tools/line-query/line-query-basic-operations|Line-query operations]] · Documentation  
    **Level:** Intermediate (approx.)  
    **Theory / practice:** 5 / 95
    **Description:** Local documentation showing operations for querying vault text.  
    **Read:** query examples.  
    **Value for you:** **Moderate** – Provides a familiar implementation example, but studying it is useful mainly when a query requirement is concrete.
    **External signals:** Not applicable — local/private vault artifact; no public popularity or citation metric is expected.

### Not assessed

4. [[PM research]], [[Domains/System/Pm tm/Pm tm learning map|PM learning map]], and [[Domains/System/Pm tm/Management system|Management system]] · Local research and drafts  
    **Level:** Level not assessed  
    **Theory / practice:** Not assessed – the selected material has not been reviewed enough to rate.  
    **Description:** Local research and AI-produced drafts about project and task management.  
    **Read:** the relevant example or topic only.  
    **Value for you:** **Unclear** – Their acceptance and fit remain unresolved; inspect only the relevant example before treating them as guidance.  
    **Notes:** the larger AI-produced drafts remain unconfirmed.
    **External signals:** Not applicable — local/private vault artifact; no public popularity or citation metric is expected.

## Further study leads

Source bundle: [Agent skill evolution frameworks manifest](<C:/Users/Admin/Downloads/Agent skill evolution frameworks/references/SOURCES.md>). The manifest is a locator, not evidence that every listed framework was reviewed. ACE and WikiSkill already have entries in **Skills and improvement**; SkillWiki below is a separate named lead.

The remaining leads keep their existing order. Each has **level not assessed** and **resource type not verified**. First locate its original source through the manifest, then inspect its overview and evidence before choosing deeper sections.

1. **Trace2Skill** · Resource type not verified  
    **Level:** not assessed  
    **Theory / practice:** Not assessed – the selected material has not been reviewed enough to rate.  
    **Description:** Provisional: an unreviewed lead from the skill-evolution collection; its contents and claims have not been established here.  
    **Read:** inspect its proposed trace-to-skill mechanism. Locate the original source through the manifest above.  
    **Value for you:** **Unclear** – Insufficient source inspection to tell whether it adds to the reviewed material or merits more of your study time.
    **External signals:** [GitHub](https://github.com/Qwen-Applications/Trace2Skill): 293 stars, 20 forks; checked 2026-09-26.

2. **SkillWiki** · Resource type not verified  
    **Level:** not assessed  
    **Theory / practice:** Not assessed – the selected material has not been reviewed enough to rate.  
    **Description:** Provisional: an unreviewed lead from the skill-evolution collection; its contents and claims have not been established here.  
    **Read:** establish how its knowledge and skill arrangement differs from WikiSkill. Locate the original source through the manifest above.  
    **Value for you:** **Unclear** – Insufficient source inspection to tell whether it adds to the reviewed material or merits more of your study time.
    **External signals:** [GitHub](https://github.com/Huangdingcheng/SkillWiki): 34 stars, 5 forks; checked 2026-09-26.

3. **Memento** · Resource type not verified  
    **Level:** not assessed  
    **Theory / practice:** Not assessed – the selected material has not been reviewed enough to rate.  
    **Description:** Provisional: an unreviewed lead from the skill-evolution collection; its contents and claims have not been established here.  
    **Read:** establish the mechanism and relevance before studying further. Locate the original source through the manifest above.  
    **Value for you:** **Unclear** – Insufficient source inspection to tell whether it adds to the reviewed material or merits more of your study time.
    **External signals:** [GitHub](https://github.com/Memento-Teams/Memento-Skills): 1,565 stars, 181 forks; checked 2026-09-26. Matching public skill-evolution project.

4. **MetaClaw** · Resource type not verified  
    **Level:** not assessed  
    **Theory / practice:** Not assessed – the selected material has not been reviewed enough to rate.  
    **Description:** Provisional: an unreviewed lead from the skill-evolution collection; its contents and claims have not been established here.  
    **Read:** establish the mechanism and relevance before studying further. Locate the original source through the manifest above.  
    **Value for you:** **Unclear** – Insufficient source inspection to tell whether it adds to the reviewed material or merits more of your study time.
    **External signals:** [GitHub](https://github.com/aiming-lab/MetaClaw): 3,492 stars, 452 forks; checked 2026-09-26.

5. **SkillCommit** · Resource type not verified  
    **Level:** not assessed  
    **Theory / practice:** Not assessed – the selected material has not been reviewed enough to rate.  
    **Description:** Provisional: an unreviewed lead from the skill-evolution collection; its contents and claims have not been established here.  
    **Read:** establish the mechanism and relevance before studying further. Locate the original source through the manifest above.  
    **Value for you:** **Unclear** – Insufficient source inspection to tell whether it adds to the reviewed material or merits more of your study time.
    **External signals:** [arXiv](https://arxiv.org/abs/2608.15165): public paper released August 2026; [Similarweb](https://www.similarweb.com/website/arxiv.org/) ranks arxiv.org #2,255 globally. Platform-level reach used because no verified project popularity metric was established.

6. **GEPA** · Resource type not verified  
    **Level:** not assessed  
    **Theory / practice:** Not assessed – the selected material has not been reviewed enough to rate.  
    **Description:** Provisional: an unreviewed lead from the skill-evolution collection; its contents and claims have not been established here.  
    **Read:** inspect the optimization overview and prerequisites. Locate the original source through the manifest above.  
    **Value for you:** **Unclear** – Insufficient source inspection to tell whether it adds to the reviewed material or merits more of your study time.

These descriptions are investigation questions, not verified claims about the projects.

    **External signals:** [GitHub](https://github.com/gepa-ai/gepa): 6,741 stars, 546 forks; checked 2026-09-26.
## Discovery sources

Directories and curated collections to consult for a specific gap, not a sequence to finish. These are upstream sources for maintaining this reading guide: mine them for strong individual resources, repeated recommendations, useful taxonomies, and worked examples. Do not add whole collections to the active reading queue by default. No difficulty rating applies to a whole publication channel or directory.

**External signals:** GitHub stars and forks are snapshot popularity/adoption signals, not quality scores. Counts below were checked on 2026-09-25.

### Primary publication and learning channels

- [Pocock skills repository](https://github.com/mattpocock/skills) – parent collection for the skills placed above.
- [OpenAI developer learning](https://developers.openai.com/learn) and [research index](https://openai.com/research/index/) – practical guidance and original research.
- [Anthropic Engineering](https://www.anthropic.com/engineering), [Research](https://www.anthropic.com/research), and [Claude Academy](https://academy.claude.com/) – engineering, research, and courses.
- [Google Research](https://research.google/pubs/) and [Google DeepMind](https://deepmind.google/research/publications/) – original papers.
- [Microsoft Research HAX](https://www.microsoft.com/en-us/research/group/hax-team/) – human–AI interaction research.
- **Hugging Face Learn:** use the Agents and Context course entries above; [Daily Papers](https://huggingface.co/papers) is a discovery feed.
- **Berkeley:** course directories are linked under [[#Longer courses and study paths]].
- [OpenReview](https://openreview.net/) and [ACL Anthology](https://aclanthology.org/) – publication and review discovery.

### Core agent and harness collections

- [Awesome Generative AI Guide](https://github.com/aishwaryanr/awesome-generative-ai-guide) · Discovery collection – Large general GenAI hub with dedicated agent, context, RAG, evaluation, research, notebook, and production material. Use selectively as a broad coverage check.
  **External signals:** [GitHub](https://github.com/aishwaryanr/awesome-generative-ai-guide): 29,581 stars, 5,961 forks; checked 2026-09-25.

- [VoltAgent: Awesome AI Agent Papers](https://github.com/VoltAgent/awesome-ai-agent-papers) · Research collection – Current agent-engineering papers including memory, workflows, evaluation, and autonomous systems; useful for newer material that may not yet appear in older surveys.
  **External signals:** [GitHub](https://github.com/VoltAgent/awesome-ai-agent-papers): 1,804 stars, 186 forks; checked 2026-09-25.

- [LLM Agent Survey](https://github.com/xinzhel/LLM-Agent-Survey) · Research collection – Curated survey-oriented paper map with a structured taxonomy and selective research coverage; useful as an independent quality and coverage cross-check.
  **External signals:** [GitHub](https://github.com/xinzhel/LLM-Agent-Survey): 520 stars, 23 forks; checked 2026-09-25.

- [Learn AI Agents](https://github.com/artnitolog/awesome-agent-learning) · Meta-collection – Guides, courses, reading lists, and other learning resources for agents. Useful mainly for discovering alternative study paths rather than as a source to complete.
  **External signals:** [GitHub](https://github.com/artnitolog/awesome-agent-learning): 158 stars, 31 forks; checked 2026-09-25.

- [Awesome LLM Agent Papers](https://github.com/js-lee-AI/awesome-llm-agent-papers) · Research collection – Papers and annotated material spanning architectures, planning, memory, tool use, multi-agent systems, evaluation, safety, and applications. Use its starter selections and taxonomy as filters rather than reading the whole catalog.
  **External signals:** [GitHub](https://github.com/js-lee-AI/awesome-llm-agent-papers): 84 stars, 24 forks; checked 2026-09-25.

- [EthicalML: Awesome Agentic Engineering Resources](https://github.com/EthicalML/awesome-agentic-engineering-resources) · Discovery collection – Broad directory organized across context, memory, planning, tools, evaluations, product design, and related agent-engineering topics. Useful for coverage audits rather than sequential study.  
  **External signals:** [GitHub](https://github.com/EthicalML/awesome-agentic-engineering-resources): 74 stars, 16 forks; checked 2026-09-25.

- [Awesome Agentic Engineering](https://github.com/fatihkc/awesome-agentic-engineering) · Discovery collection – Material on harnesses, loop engineering, context engineering, specifications, evaluations, and production case studies.
  **External signals:** [GitHub](https://github.com/fatihkc/awesome-agentic-engineering): 20 stars, 11 forks; checked 2026-09-25.

- [Awesome Agent Loop Papers](https://github.com/js-lee-AI/awesome-agent-loop-papers) · Discovery collection – Research and real-world artifacts organized around agent-loop mechanics, context, recovery, skills, harnesses, orchestration, evaluation, and safety. One of the closest upstream collections to the harness-development scope of this guide.
  **External signals:** [GitHub](https://github.com/js-lee-AI/awesome-agent-loop-papers): 6 stars, 4 forks; checked 2026-09-25.

- [Awesome Agents](https://github.com/arvindcr4/awesome-agents) · Discovery collection – Agent papers and resources across reasoning, planning, memory, infrastructure, frameworks, and benchmarks.
  **External signals:** [GitHub](https://github.com/arvindcr4/awesome-agents): 2 stars, 0 forks; checked 2026-09-25.

### Context, memory, retrieval, and knowledge

- [Awesome Knowledge Graph](https://github.com/totogo/awesome-knowledge-graph) · Discovery collection – Knowledge-graph learning material, tooling, graph databases, semantic modeling, and related LLM/KG resources.
  **External signals:** [GitHub](https://github.com/totogo/awesome-knowledge-graph): 1,894 stars, 178 forks; checked 2026-09-25.

- [TeleAI: Awesome Agent Memory](https://github.com/TeleAI-UAGI/Awesome-Agent-Memory) · Research collection – Agent-memory systems, benchmarks, papers, tutorials, and long-term memory approaches.
  **External signals:** [GitHub](https://github.com/TeleAI-UAGI/Awesome-Agent-Memory): 648 stars, 107 forks; checked 2026-09-25.

- [Awesome RAG](https://github.com/coree/awesome-rag) · Discovery collection – RAG papers, surveys, lectures, tutorials, tools, and related resource lists.
  **External signals:** [GitHub](https://github.com/coree/awesome-rag): 448 stars, 59 forks; checked 2026-09-25.

- [Awesome RAG – Poll the People](https://github.com/Poll-The-People/awesome-rag) · Practical collection – Retrieval, chunking, embeddings, GraphRAG, evaluation, security, observability, cost, courses, and research.
  **External signals:** [GitHub](https://github.com/Poll-The-People/awesome-rag): 188 stars, 29 forks; checked 2026-09-25.

- [Awesome Context Engineering – yzfly](https://github.com/yzfly/awesome-context-engineering) · Discovery collection – Context retrieval, generation, management, compression, isolation, memory, skills, MCP, and harness-related material.
  **External signals:** [GitHub](https://github.com/yzfly/awesome-context-engineering): 149 stars, 54 forks; checked 2026-09-25.

- [Awesome Context Engineering – jihoo-kim](https://github.com/jihoo-kim/awesome-context-engineering) · Discovery collection – Organizes context work around writing, selecting, compressing, and isolating context, with memory, RAG, and multi-agent extensions.
  **External signals:** [GitHub](https://github.com/jihoo-kim/awesome-context-engineering): 113 stars, 31 forks; checked 2026-09-25.

- [Snseam: Awesome Agent Memory](https://github.com/Snseam/awesome-agent-memory) · Meta-collection – Aggregates and deduplicates multiple agent-memory reading lists and provides architecture/research maps; useful for identifying repeatedly surfaced memory work.
  **External signals:** [GitHub](https://github.com/Snseam/awesome-agent-memory): 17 stars, 4 forks; checked 2026-09-25.

- [Mnemoverse: Awesome Agent Memory](https://github.com/mnemoverse/awesome-agent-memory) · Implementation-oriented collection – Memory engines, APIs, MCP-compatible approaches, frameworks, benchmarks, and foundational work.
  **External signals:** [GitHub](https://github.com/mnemoverse/awesome-agent-memory): 3 stars, 10 forks; checked 2026-09-25.

- [Awesome Agentic Memory](https://github.com/Anandesh-Sharma/awesome-agentic-memory) · Discovery collection – Memory taxonomy, frameworks, research, benchmarks, and guided starting points.
  **External signals:** [GitHub](https://github.com/Anandesh-Sharma/awesome-agentic-memory): 1 stars, 4 forks; checked 2026-09-25.

### Skills, instructions, and reusable procedures

- [Agent Skill Index](https://github.com/heilcheng/awesome-agent-skills) · Skill collection – Community directory of skills used across Codex, Claude, Gemini CLI, Copilot, and related agent environments.
  **External signals:** [GitHub](https://github.com/heilcheng/awesome-agent-skills): 6,231 stars, 718 forks; checked 2026-09-25.

- [Awesome Agent Skills – JayLZhou](https://github.com/JayLZhou/Awesome-Agent-Skills) · Research-oriented collection – Skills as reusable procedural artifacts with applicability conditions, supporting resources, and governance considerations.
  **External signals:** [GitHub](https://github.com/JayLZhou/Awesome-Agent-Skills): 152 stars, 40 forks; checked 2026-09-25.

- [Awesome Agent Skills – Ezeafk](https://github.com/Ezeafk/awesome-agent-skills) · Skill collection – Reusable agent skills across research, productivity, business, MCP, coding, and other domains; useful for studying skill structure and selection criteria.
  **External signals:** [GitHub](https://github.com/Ezeafk/awesome-agent-skills): 99 stars, 38 forks; checked 2026-09-25.

- [Awesome AGENTS.md](https://github.com/tairov/awesome-agents.md) · Example collection – Real-world agent-instruction files and supporting tooling. Relevant to thin root guidance, context pointers, and instruction architecture.
  **External signals:** [GitHub](https://github.com/tairov/awesome-agents.md): 35 stars, 14 forks; checked 2026-09-25.

- [Awesome Agent Skills – khasky](https://github.com/khasky/awesome-agent-skills) · Skill collection – Curated skill implementations and guidance for choosing or comparing overlapping procedures.
  **External signals:** [GitHub](https://github.com/khasky/awesome-agent-skills): 10 stars, 2 forks; checked 2026-09-25.

- [Awesome Agent Skills – open-agent-craft](https://github.com/open-agent-craft/awesome-agent-skills) · Skill collection – Agent instructions, evaluation/testing, MCP/tool use, research, productivity, and development procedures.
  **External signals:** [GitHub](https://github.com/open-agent-craft/awesome-agent-skills): 3 stars, 15 forks; checked 2026-09-25.

### Research workflows and worked implementations

- [Awesome LLM Apps](https://github.com/Shubhamsaboo/awesome-llm-apps) · Worked-example collection – Concrete agent, RAG, MCP, multi-agent, and application implementations. Use when conceptual material is too abstract and a working example would clarify the design.
  **External signals:** [GitHub](https://github.com/Shubhamsaboo/awesome-llm-apps): 139,746 stars, 20,533 forks; checked 2026-09-25.

- [AI Engineering Hub](https://github.com/patchy631/ai-engineering-hub) · Tutorial and project collection – Hands-on LLM, RAG, and agent projects across multiple implementation levels.
  **External signals:** [GitHub](https://github.com/patchy631/ai-engineering-hub): 38,018 stars, 6,248 forks; checked 2026-09-25.

- [Awesome CLI Coding Agents](https://github.com/bradAGI/awesome-cli-coding-agents) · Ecosystem collection – CLI agents plus harnesses, autonomous loops, runners, and supporting infrastructure; useful for comparison with Codex-style workflows.
  **External signals:** [GitHub](https://github.com/bradAGI/awesome-cli-coding-agents): 1,281 stars, 367 forks; checked 2026-09-25.

- [Awesome AutoResearch](https://github.com/AI4Scientist/awesome-autoresearch) · Research collection – Autonomous-research systems spanning hypotheses, experiments, analysis, and research-output generation.
  **External signals:** [GitHub](https://github.com/AI4Scientist/awesome-autoresearch): 160 stars, 26 forks; checked 2026-09-25.

- [AI Literature Review Agents & Tools](https://github.com/brycewang-stanford/lit-review-agent-tools) · Workflow collection – Tools and agents mapped to literature-review stages such as discovery, screening, extraction, synthesis, citation verification, and writing.
  **External signals:** [GitHub](https://github.com/brycewang-stanford/lit-review-agent-tools): 27 stars, 2 forks; checked 2026-09-25.

- [Awesome Research Agents – chchenhui](https://github.com/chchenhui/awesome-research-agents) · Research collection – Scientific discovery, literature review, idea generation, research engineering, writing, and assessment.
  **External signals:** [GitHub](https://github.com/chchenhui/awesome-research-agents): 14 stars, 4 forks; checked 2026-09-25.

- [Awesome Research Agents – chrisliu298](https://github.com/chrisliu298/awesome-research-agents) · Discovery collection – Research harnesses, agent skills, autonomous research loops, project memory, literature workflows, writing, review, and benchmarks, including CLI-agent-oriented approaches.
  **External signals:** [GitHub](https://github.com/chrisliu298/awesome-research-agents): 3 stars, 3 forks; checked 2026-09-25.

### Orchestration, evaluation, and production

- [Agents Towards Production](https://github.com/NirDiamant/agents-towards-production) · Practical collection – State, memory, deployment, browser automation, multi-agent patterns, observability, evaluation, security, and user-interface considerations.
  **External signals:** [GitHub](https://github.com/NirDiamant/agents-towards-production): 21,493 stars, 2,852 forks; checked 2026-09-25.

- [Awesome LLMOps](https://github.com/tensorchord/Awesome-LLMOps) · Operations collection – LLM lifecycle, observability, serving, retrieval infrastructure, reliability, and operational tooling.
  **External signals:** [GitHub](https://github.com/tensorchord/Awesome-LLMOps): 5,948 stars, 1,068 forks; checked 2026-09-25.

- [BenchFlow: Awesome Agent Evals](https://github.com/benchflow-ai/awesome-evals) · Evaluation collection – Agent-evaluation papers, practitioner material, talks, tools, and benchmarks. Use when evaluation becomes a priority rather than treating the whole collection as required study.
  **External signals:** [GitHub](https://github.com/benchflow-ai/awesome-evals): 911 stars, 108 forks; checked 2026-09-25.

- [EthicalML: Awesome Production Agentic Systems](https://github.com/EthicalML/awesome-production-agentic-systems) · Production collection – Agent infrastructure, frameworks, observability, protocols, memory, security, and interfaces for production systems.
  **External signals:** [GitHub](https://github.com/EthicalML/awesome-production-agentic-systems): 175 stars, 29 forks; checked 2026-09-25.

- [Awesome Agent Orchestration](https://github.com/vivy-yi/awesome-agent-orchestration) · Discovery collection – Frameworks and patterns for sequential, parallel, hierarchical, multi-agent, MCP, and A2A orchestration.
  **External signals:** [GitHub](https://github.com/vivy-yi/awesome-agent-orchestration): 43 stars, 16 forks; checked 2026-09-25.

- [Awesome Multi-Agent Systems](https://github.com/bloo-mind/awesome-multi-agent-systems) · Annotated collection – Coordination theory, LLM-era multi-agent systems, failure modes, benchmarks, and learning paths.
  **External signals:** [GitHub](https://github.com/bloo-mind/awesome-multi-agent-systems): 6 stars, 5 forks; checked 2026-09-25.

- [Awesome LLM Agent Orchestration](https://github.com/CuiZHIQ/Awesome-LLM-Agent-Orchestration) · Research collection – Scheduling, routing, tool dispatch, workflow graphs, runtime orchestration, and related reading paths.
  **External signals:** [GitHub](https://github.com/CuiZHIQ/Awesome-LLM-Agent-Orchestration): 5 stars, 2 forks; checked 2026-09-25.

- [Awesome Agent Observability](https://github.com/anhermon/awesome-agent-observability) · Operations collection – Tracing, OpenTelemetry-related material, evaluation, guardrails, gateways, and MCP observability.
  **External signals:** [GitHub](https://github.com/anhermon/awesome-agent-observability): 0 stars, 8 forks; checked 2026-09-25.

### PKM and second-brain collections

- [Awesome PKM](https://github.com/doanhthong/awesome-pkm) · Discovery collection – PKM methods, evergreen-note and second-brain material, tools, reading, writing, and knowledge-work workflows.
  **External signals:** [GitHub](https://github.com/doanhthong/awesome-pkm): 114 stars, 14 forks; checked 2026-09-25.

- [Awesome Second Brain](https://github.com/Mindola-ai/awesome-second-brain) · Discovery collection – Second-brain and PKM methods, tools, personal AI, local-first approaches, books, creators, and communities. Relevant to the personal-OS side of this harness rather than agent engineering alone.
  **External signals:** [GitHub](https://github.com/Mindola-ai/awesome-second-brain): 4 stars, 8 forks; checked 2026-09-25.

### Broad auxiliary collection

- [DAIR.AI: Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide) · Discovery collection – Organized guides, papers, lessons, and examples covering prompting, context, retrieval, and agents. Use for a specific gap rather than as another sequence to finish.  
  **External signals:** [GitHub](https://github.com/dair-ai/Prompt-Engineering-Guide): 78,625 stars, 8,644 forks; checked 2026-09-25.
## Coverage

The category lists retain all 121 distinct numbered reading entries. The expanded [[#Discovery sources]] section is an upstream source map and is not counted as numbered reading entries. All 16 former main entries now have a category home. The 7 main-sequence entries are intentional copies of category entries, not additional resources.

Descriptions, selected sections, source qualifications, links, and dated external signals are retained. Current value estimates and reading feedback for the reviewed materials are adjusted to [[Harness reading, my reviews]]. That note is left unchanged; a skim or reading only the beginning is not recorded as completion.

Historical conversations and operating records remain evidence in [[Harness research#Starting point from the repository]], not assigned readings. The research note is unchanged. Maintain the category entry as the source of truth and refresh its selected main-list copy when changing it.
