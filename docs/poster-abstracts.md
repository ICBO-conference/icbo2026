---
disable_toc: true
---

<div style="max-width: 1000px; margin: 0 auto;" markdown>

# Poster & Software Demo Abstracts

**<i class="fa fa-calendar"></i> July 15–17, 2026 &nbsp;|&nbsp; <i class="fa fa-map-marker"></i> Columbia Ballroom, Washington Hilton, Washington D.C.**

Accepted posters and software demos will be presented during the poster and demo recesses on
Day 1 (10:00 – 11:00 AM and 4:00 – 4:40 PM) and Day 2 (10:00 – 11:00 AM). See the
[Conference Agenda](agenda.md) for the full schedule.

---

## Accepted Abstracts

<div class="poster-card" markdown>

<span class="poster-tag">Poster</span>

### Cell Line Ontology in 2026

**Jie Zheng, Stella Liao, Abigail Samuelson, Yongqun He**
<span class="poster-affil">University of Michigan Medical School, Ann Arbor, MI, USA</span>

The Cell Line Ontology (CLO), an OBO Foundry member initiated in 2010, contains more than 43,000
terms standardizing the representation of cell lines from ATCC, HyperCLDB, and other repositories.
After a pause in active development, CLO development resumed in 2026 and several major issues were
identified and resolved: 609 ROBOT-reported errors (duplicate labels, duplicate definitions, and
multiple definitions), imported terms that had been deprecated or replaced in their source
ontologies, and inconsistent application of the cell line cell design pattern. CLO was also
realigned from BFO to the Core Ontology for Biology and Biomedicine (COB) to strengthen
interoperability, and a Makefile-based release workflow using OntoFox and ROBOT templates was
implemented. These updates support richer queries over cell lines by derived cell type, anatomical
structure, source organism, disease model, and repository.

*Keywords: ontology, Cell Line Ontology, cell line*

<p><a href="../posters/icbo2026-poster-cell-line-ontology.pdf" class="btn btn-default btn-sm"><i class="fa fa-file-pdf-o"></i> Read full abstract (PDF)</a></p>

</div>

<div class="poster-card" markdown>

<span class="poster-tag">Software Demo</span>

### CellCards 2.0: An Ontology-Driven Platform for Anatomically Contextualized Cell and Cell Line Knowledge Integration

**Feng-Yu Yeh, Mary Czelusniak, Stella Liao, Jie Zheng, William D. Duncan, Alexander D. Diehl, Bruce W. Herr II, Katy Börner, Yongqun He**
<span class="poster-affil">University of Michigan; University of Florida College of Dentistry; NF/SG VAHS; University at Buffalo; Indiana University</span>

[CellCards](https://cellcards.org) is an ontology-driven knowledgebase for the standardized
characterization of cell types. Because identical cell types can exhibit distinct molecular and
functional profiles across tissues, CellCards 2.0 maps Cell Ontology (CL) identifiers to multiple
UBERON anatomical contexts, enabling tissue-specific disambiguation of primary cells, and adds
over 30,000 immortalized cell lines represented through the Cell Line Ontology (CLO). The platform
integrates HuBMAP ASCT+B tables and Functional Tissue Unit reference models, ingests ontology-linked
metadata from over 160,000 Cellosaurus records, and retrieves CL and CLO information via Ontobee
SPARQL queries. The demo showcases tissue-aware cell exploration, ontology-linked biomarker
integration, and semantic disambiguation workflows across multi-source biomedical datasets.

*Keywords: Cell Ontology; Cell Line Ontology; semantic integration; HuBMAP; biomedical ontologies*

<p><a href="../posters/icbo2026-poster-cellcards-2.pdf" class="btn btn-default btn-sm"><i class="fa fa-file-pdf-o"></i> Read full abstract (PDF)</a>
<a href="https://cellcards.org" target="_blank" class="btn btn-default btn-sm"><i class="fa fa-external-link"></i> cellcards.org</a></p>

</div>

<div class="poster-card" markdown>

<span class="poster-tag">Poster</span>

### Connecting Neural Circuit Biotypes to Pharmacogenomics: An OWL 2 DL Ontology Extension for Precision Psychiatry Decision Support

**Lucas Wozniak, Atul Chaudhari, Chuyi Zhang, Lauren Hamilton**

Depression and anxiety disorders exhibit substantial biological heterogeneity, yet no existing
system provides a unified, computable representation linking neural circuit biotype classification
to pharmacogenomics safety constraints for antidepressant prescribing. This work presents a
confidence-qualified neural phenotype ontology joining the two domains through an OWL 2 DL
knowledge architecture, a Bayesian network for biotype inference, and a pharmacogenomics clinical
decision support module. The ontology aligns to BFO 2020 and bridges via SKOS to UBERON, HPO, the
Cognitive Atlas, and SNOMED CT, with accompanying SSSOM mapping tables; it validates as OWL 2
DL-conformant with zero ROBOT errors. An HL7 CDS Hooks 2.0 service combines SPARQL-queried
drug–gene relationships, CPIC Activity Score rules, and FHIR Genomics Reporting IG v3.0.0 genotype
data to generate real-time prescribing alerts, maintaining a strict separation between ontology
vocabulary, curated knowledge base, and procedural rule engine.

<p><a href="../posters/icbo2026-poster-neural-circuit-biotypes.pdf" class="btn btn-default btn-sm"><i class="fa fa-file-pdf-o"></i> Read full abstract (PDF)</a>
<a href="https://sapphire-cision.github.io/bmds210-neural-phenotype-ontology/#brain" target="_blank" class="btn btn-default btn-sm"><i class="fa fa-external-link"></i> Demo</a></p>

</div>

<div class="poster-card" markdown>

<span class="poster-tag">Poster</span>

### Enabling Cross-Domain Semantic Data Integration with an RDF Representation of RefChem

**Qingliang Li, Sunghwan Kim, Paul Thiessen, Jian Zhang, Tiejun Cheng, Asta Gindulyte, Siqian He, Evan Bolton**
<span class="poster-affil">National Center for Biotechnology Information, National Library of Medicine, NIH, Bethesda, MD, USA</span>

Chemical entity integration across heterogeneous biomedical resources remains a persistent
challenge, since even authoritative sources disagree over whether two representations refer to the
same entity — formaldehyde as a gas versus formalin as an aqueous solution, or active
pharmaceutical ingredients versus their salt forms. RefChem, the PubChem Reference Collection,
disambiguates and semantically organizes chemical substances using standardized structures, names,
and identifiers. This work presents an RDF-based representation of RefChem that captures substance
identity, structural relationships, naming types, associations, and variants, enabling formal
semantic integration within PubChemRDF and across external resources such as drugs, toxicology
data, biological assays, literature, and patents, and advancing the interoperability and FAIRness
of chemical data.

<p><a href="../posters/icbo2026-poster-refchem-rdf.pdf" class="btn btn-default btn-sm"><i class="fa fa-file-pdf-o"></i> Read full abstract (PDF)</a></p>

</div>

<div class="poster-card" markdown>

<span class="poster-tag">Poster</span>

### Semantic Mapping of Psychological Assessment Questions to BERTopic-Derived Solitude-Related Concepts Using SciBERT Embeddings

**B. Damayanthi Jesudas, Jérémy Ravenel, Maxime Jublou, Sam Smith, Feng-Yu Yeh, Jie Zheng, Yongqun He, Regina Hurley, Julie C. Bowker, Hollen N. Reischer, John Beverley, William D. Duncan**
<span class="poster-affil">University of Florida; NF/SG VAHS; University at Buffalo; University of Michigan Medical School; NaasAI, Inc.</span>

Part of the Promoting Healthy Aging through Semantic Enrichment of Solitude Research (PHASES)
project, this study extends prior BERTopic modeling of *The Handbook of Solitude* by semantically
linking psychological assessment questions to BERTopic-derived topic representations using SciBERT
embeddings. Questions drawn from the UCLA Loneliness Scale, Differential Loneliness Scale, Inventory
of Interpersonal Problems, and Subjective Happiness and Loneliness Scales were encoded alongside
topic summaries, and cosine similarity identified the five most semantically similar topics per
question. The framework captures relationships beyond keyword overlap and surfaces candidate
psychological constructs for ontology development, while demonstrating that subject matter expert
review remains necessary to separate genuinely relevant concepts from semantically related but
conceptually irrelevant topics.

*Keywords: SciBERT; BERTopic; semantic similarity; psychological assessment; solitude; ontology development*

<p><a href="../posters/icbo2026-poster-solitude-scibert.pdf" class="btn btn-default btn-sm"><i class="fa fa-file-pdf-o"></i> Read full abstract (PDF)</a>
<a href="http://buffalo-ontology-group.github.io/phases-healthy-aging.github.io/" target="_blank" class="btn btn-default btn-sm"><i class="fa fa-external-link"></i> Project website</a>
<a href="https://github.com/Buffalo-Ontology-Group/phases-nlp" target="_blank" class="btn btn-default btn-sm"><i class="fa fa-github"></i> Source code</a></p>

</div>

<div class="poster-card" markdown>

<span class="poster-tag">Poster</span>

### Tracking Usage of Ontologies in the Translational Science Ecosystem

**Sebastian Duesing, Fabrício Rodrigues, Barry Smith**
<span class="poster-affil">Department of Philosophy, University at Buffalo, Amherst, NY, USA</span>

Translational research projects use ontologies to annotate, analyze, and harmonize diversely
formatted data, and both the ontologies and the projects benefit when developers understand how
their ontologies are used. At present, however, it is almost impossible for open-source ontology
development teams to identify where their ontologies are being used outside their own laboratories.
Ontology browsers such as Ontobee and the Ontology Lookup Service expose inter-ontology
dependencies, but comparable visibility into downstream project use does not exist. The authors
propose a registry of ontology usage in translational research (ROUTR) to collect and disseminate
information about how clinical translational science projects use and depend on ontologies.

*Keywords: ontology, ontology usage, clinical translational science, database*

<p><a href="../posters/icbo2026-poster-routr-ontology-usage.pdf" class="btn btn-default btn-sm"><i class="fa fa-file-pdf-o"></i> Read full abstract (PDF)</a></p>

</div>

<div class="poster-card" markdown>

<span class="poster-tag">Poster</span>

### Using MedGen to Assign Clinical Categories to Tests and Utilize the Disease Categories as a Search Criterion for Tests in the NIH Genetic Testing Registry (GTR®)

**Thilakam Venkatapathi, Adriana Malheiro, Megan Kane, Marilu Hoeppner, Baoshan Gu, George Zhou, Doug Hoffman, Sahithi Punyasamudram, Brandi Kattman**
<span class="poster-affil">National Center for Biotechnology Information, National Library of Medicine, NIH, Bethesda, MD, USA</span>

[MedGen](https://www.ncbi.nlm.nih.gov/medgen) integrates clinically relevant and sometimes
orthogonal ontologies and vocabularies — including HPO, Mondo, OrphaNet, a UMLS subset, OMIM,
PharmGKB, GeneReviews, and GARD — under one resource, mapping equivalent concepts to a single
MedGen record and routing automated-pipeline discrepancies to curators for review. To help
clinicians select suitable tests in the [NIH Genetic Testing Registry](https://www.ncbi.nlm.nih.gov/gtr),
this work assigns broad clinical specialty labels to tests: higher-level HPO and Mondo nodes are
matched to each clinical category label, descendants inherit that label, and the labels collected
across a test's indicated diseases are scored by how frequently they are represented in order to
prioritize display. The resulting clinical categories now power retrieval of tests by broad clinical
category in GTR's advanced search.

<p><a href="../posters/icbo2026-poster-medgen-gtr.pdf" class="btn btn-default btn-sm"><i class="fa fa-file-pdf-o"></i> Read full abstract (PDF)</a></p>

</div>

---

## <i class="fa fa-envelope"></i> Contact Information

Please direct all questions to Asiyah Yu Lin — <a href="mailto:ontology.world@gmail.com">ontology.world@gmail.com</a>

</div>
