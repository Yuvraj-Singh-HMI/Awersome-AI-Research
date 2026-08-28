# Awesome Causal vs. Correlational Language in LLM-Assisted Editing

A curated collection of research papers, datasets, tools, implementations, and learning resources related to the **preservation of causal versus correlational language during Large Language Model (LLM)-assisted editing**.

This repository focuses on how LLM-based editing and rewriting systems may alter the strength or meaning of scientific claims, particularly when causal language is changed into correlational language or vice versa. It brings together verified research resources to support the study of claim preservation, scientific writing, causal language, LLM-assisted editing, and trustworthy AI-assisted research.

## Contents

* [Overview](#overview)
* [AI-Assisted Research Paper](#ai-assisted-research-paper)
* [Citation Integrity Audit](#citation-integrity-audit)
* [Survey and Review Papers](#survey-and-review-papers)
* [Foundational Papers](#foundational-papers)
* [Recent Research Papers](#recent-research-papers)
* [Methods and Algorithms](#methods-and-algorithms)
* [Applications](#applications)
* [Evaluation Methods and Benchmarks](#evaluation-methods-and-benchmarks)
* [Datasets](#datasets)
* [Tools and Libraries](#tools-and-libraries)
* [GitHub Implementations](#github-implementations)
* [Tutorials and Learning Resources](#tutorials-and-learning-resources)
* [License](#license)

---

## Overview

Large Language Models are increasingly used to assist with writing, editing, rewriting, summarization, and refinement of scientific and technical text. Although these systems can improve readability and fluency, editing can also modify the meaning or strength of a claim.

One important distinction in scientific communication is the difference between **causal** and **correlational** language. A causal statement suggests that one variable, event, or factor produces an effect, while a correlational statement describes an association between variables without necessarily establishing a causal relationship. Preserving this distinction is important because changing the wording of a claim can unintentionally change its scientific interpretation.

This repository focuses on research related to the **preservation of causal versus correlational language during LLM-assisted editing**. Relevant areas include causal inference, scientific writing, claim verification, text editing, controllable generation, factuality, semantic preservation, and evaluation of LLM-generated text.

The resources are organized to help researchers and students understand the problem, examine existing methods, identify suitable datasets and tools, and explore implementations and learning materials.

---

## AI-Assisted Research Paper

### Preservation of Causal Versus Correlational Language During LLM-Assisted Editing

This research paper investigates the preservation of the distinction between causal and correlational claims when Large Language Models are used to edit or rewrite text.

The paper examines the potential for LLM-assisted editing to change the strength or interpretation of scientific statements and discusses methods for identifying and evaluating such changes.

**Paper:** [View AI-Assisted Research Paper](paper/AI_Assisted_Research_Paper.pdf)

---

## Citation Integrity Audit

The scholarly references and claims used in the research activity were checked for citation integrity. Verification focuses on the correctness and existence of references, including paper title, authors, publication year, venue, DOI where available, and whether the linked resource corresponds to the cited work.

**Audit:** [View Citation Integrity Audit](citation-audit/Citation_Integrity_Audit.pdf)

---

## Foundational Papers

Important foundational work related to causal inference, causality, language understanding, scientific claims, and language-model-based text processing.

* **[How LLMs Distort Our Written Language.]** — Abdulhai, M., White, I., Wan, Y., & Qureshi, I., Year- 2026
  [Paper / DOI](https://doi.org/10.48550/arXiv.2603.18161)
  Relevant to our central problem because it examines how LLM-assisted writing can alter human-written language.

* **[‘Spin’ in published biomedical literature: A methodological systematic review.]** — Chiu, K., Grundy, Q., & Bero, L., Year-2017
  [Paper / DOI](https://doi.org/10.1371/journal)
  Reviews the problem of “spin” in biomedical literature, making it relevant to changes in the strength or interpretation of scientific claims.

* **[Correlation or Causation: Analyzing the Causal Structures of LLM and LRM Reasoning Process.]** — Fu, Z., Bao, G., Zhang, H., Hu, C., & Zhang, Y., Year-2025
  [Paper / DOI](https://doi.org/10.48550/arxiv.2509.17380)
  Investigates causal structures in LLM and LRM reasoning and the distinction between correlation and causation.

* **[Causal implicatures from correlational statements.]** — Gershman, S. J., & Ullman, T. D., Year-2023
  [Paper / DOI](https://doi.org/10.1371/journal.pone.0286067)
  Examines how readers may derive causal interpretations from statements that are formally correlational.

* **[A Dataset of Early-Stage Scientific Revisions Extracted from LaTeX Writing Traces.]** — Jourdan, L., Aubert-Beduchaud, J., Chupin, Y., Baccari, M., & Boudin, F., Year-2026
  [Paper / DOI](https://doi.org/10.48550/arXiv.2603.28515)
  Particularly relevant as a resource for studying scientific revision/editing.

* **[Can ChatGPT Understand Causal Language in Science Claims?]** — Kim, Y., Guo, L., Yu, B., & Li, Y., Year-2023
  [Paper / DOI](https://doi.org/10.18653/v1/2023.wassa-1.33)
  Directly relevant to evaluating whether ChatGPT understands causal language in scientific claims.

* **[Constraint Poisoning and Parametric Memory Override: A Failure Taxonomy and Intervention Architecture for LLM-Assisted Philological Editing of Historical Texts.]** — Latif, M. S. (2026)., Year-2026
  [Paper / DOI](https://www.preprints.org/manuscript/202606.0820)
  Relevant to LLM-assisted editing and preservation constraints, although its focus is historical/philological editing rather than scientific causal language.

* **[Can Large Language Models Infer Causal Relationships from Real-World Text?]** — Saklad, R., Year-2026
  [Paper / DOI](https://doi.org/10.18653/v1/2026.acl-long.1003)
  Examines the ability of LLMs to infer causal relationships from real-world text.

* **[AI-associated academic writing anxiety in AI-assisted contexts: evidence from Chinese EFL postgraduate students.]** — Zhang, Y., Year-2026
  [Paper / DOI](https://doi.org/10.3389/fpsyg.2026.1841607)
  Relevant to the broader context of AI-assisted academic writing, although it is less directly connected to causal/correlational claim preservation.

---

## Methods and Algorithms

Research methods relevant to detecting, preserving, or evaluating causal and correlational claims during text editing.

### Causal Language Detection

Methods for identifying linguistic expressions that indicate causal relationships and distinguishing them from expressions describing associations.

### Claim and Meaning Preservation

Methods for determining whether an edited sentence retains the meaning, evidential strength, and intended claim of the original text.

### Factuality and Faithfulness Evaluation

Approaches for evaluating whether LLM-generated or edited text remains faithful to the source material.

### Controlled Text Generation

Methods for controlling the properties of generated text so that editing does not unintentionally strengthen or weaken claims.

---

## Applications

Potential application areas related to preservation of causal and correlational language include:

* Scientific and academic writing
* Research-paper editing
* Literature review generation
* Scientific summarization
* Medical and biomedical communication
* Evidence-based reporting
* Automated proofreading and rewriting
* AI-assisted research workflows
* Fact-checking and claim verification

---

## Evaluation Methods and Benchmarks

Evaluation resources for studying whether LLM-assisted editing preserves the intended meaning and causal strength of statements.

Important evaluation dimensions include:

* Causal versus correlational claim preservation
* Semantic similarity
* Factual consistency
* Claim strength preservation
* Faithfulness to source text
* Human evaluation
* Expert assessment
* Error and contradiction detection

---

## Datasets

Relevant datasets for causal language, scientific claims, natural language inference, factuality, and evaluation of generated or edited text.

Each dataset should include its source, purpose, application, and official link.

* **[Dataset Name]**
  **Source:** [Organization / Project]
  **Purpose:** Brief description.
  **Application:** How it can support this research topic.
  [Dataset Link](LINK)

* **[Dataset Name]**
  **Source:** [Organization / Project]
  **Purpose:** Brief description.
  **Application:** How it can support this research topic.
  [Dataset Link](LINK)

* **[Dataset Name]**
  **Source:** [Organization / Project]
  **Purpose:** Brief description.
  **Application:** How it can support this research topic.
  [Dataset Link](LINK)

---

## Tools and Libraries

Useful tools and libraries for working with LLMs, NLP, causal language, scientific text, and evaluation.

* **[Tool / Library Name]**
  Brief description of its purpose and relevance.
  [Official / Project Link](LINK)

* **[Tool / Library Name]**
  Brief description of its purpose and relevance.
  [Official / Project Link](LINK)

* **[Tool / Library Name]**
  Brief description of its purpose and relevance.
  [Official / Project Link](LINK)

* **[Tool / Library Name]**
  Brief description of its purpose and relevance.
  [Official / Project Link](LINK)

* **[Tool / Library Name]**
  Brief description of its purpose and relevance.
  [Official / Project Link](LINK)

---

## GitHub Implementations

Existing implementations relevant to causal inference, NLP, LLM-assisted editing, claim verification, factuality evaluation, or related research.

* **[Repository Name]**
  Brief description of what the repository implements and why it is relevant.
  [GitHub Repository](LINK)

* **[Repository Name]**
  Brief description of what the repository implements and why it is relevant.
  [GitHub Repository](LINK)

* **[Repository Name]**
  Brief description of what the repository implements and why it is relevant.
  [GitHub Repository](LINK)

* **[Repository Name]**
  Brief description of what the repository implements and why it is relevant.
  [GitHub Repository](LINK)

* **[Repository Name]**
  Brief description of what the repository implements and why it is relevant.
  [GitHub Repository](LINK)

---

## Tutorials and Learning Resources

Authoritative resources for learning about causal inference, causal language, NLP, LLMs, scientific text processing, and evaluation.

* **[Resource Name]** — Brief description of what it teaches.
  [Resource Link](LINK)

* **[Resource Name]** — Brief description of what it teaches.
  [Resource Link](LINK)

* **[Resource Name]** — Brief description of what it teaches.
  [Resource Link](LINK)

* **[Resource Name]** — Brief description of what it teaches.
  [Resource Link](LINK)

* **[Resource Name]** — Brief description of what it teaches.
  [Resource Link](LINK)

---

## Repository Structure

```text
awesome-causal-correlational-language/
|
|-- README.md
|
|-- paper/
|   `-- AI_Assisted_Research_Paper.pdf
|
|-- citation-audit/
|   `-- Citation_Integrity_Audit.pdf
|
|-- references/
|   `-- references.md
|
|-- datasets/
|   `-- datasets.md
|
|-- tools/
|   `-- tools.md
|
|-- implementations/
|   `-- github-repositories.md
|
`-- LICENSE
```

---

## Contributing

This repository is intended as a curated academic resource. When adding a new resource:

1. Verify that the resource genuinely exists.
2. Check the title, authors, year, and publication venue where applicable.
3. Verify the DOI or official link when available.
4. Add a short explanation of the resource's relevance.
5. Prefer authoritative and original sources.
6. Do not add fabricated references or broken links.
7. Do not upload copyrighted research-paper PDFs without permission.

---

## License

This repository is intended for academic and educational use.

See the [`LICENSE`](LICENSE) file for the terms applicable to the repository's original content.
