---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<a href="{{ base_path }}/files/woodward_galbraith_cv.pdf" class="btn" target="_blank" rel="noopener"><i class="fas fa-fw fa-file-pdf" aria-hidden="true"></i> View CV (PDF)</a>

Research summary
======
PhD student leveraging machine learning, databases, and biology to develop methods that turn heterogeneous biomedical data into structured, connected, and statistically reliable knowledge. Experienced with building systems for large-scale data extraction and knowledge assembly, knowledge graph representations, and biomedical entity linking. My current focus is on developing a system that automatically assembles ontology annotations over large-scale data portals.

Education
======
**Ph.D. in Computer Science** — Northeastern University, Khoury College of Computer Sciences, Boston, MA *(Sept 2025 – present)* — GPA: 3.9/4.0
* Advisor: Dr. Benjamin M. Gyori, Gyori Lab for Computational Biomedicine
* Honors: ISMB Travel Fellowship ($500, 2026); Distinguished Research Fellow, Khoury College of Computer Sciences ($61,500, 2025)

**M.S. in Data Science, focus in Biomedical Informatics** — New York University, New York, NY *(Sept 2022 – May 2024)* — GPA: 3.9/4.0
* Thesis: *A Knowledge Graph-Driven Approach to Understanding Cancer Risks and Treatment Recommendations*, under the advisement of Dr. Kushal Dey, Memorial Sloan Kettering Cancer Center
* Relevant coursework: Single-Cell Analysis, Proteomics, ML for Health Care, Big Data, Causal Inference

**B.A. in Data Science and Economic Theory, Minor in Mathematics** — New York University, New York, NY *(Sept 2018 – May 2022)* — GPA: 3.8/4.0
* Honors: Capital One Undergraduate Research Program ($8,000, 2022); Cum Laude (2022)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Selected projects
======
**[DGLink: Automated knowledge graph construction over biomedical data portals]({{ base_path }}/portfolio/dglink/)**
* Developed an automated framework for assembling knowledge graph representations of biomedical data portals, providing semantic interoperability over large-scale data lakes
* Collaborated with the National Cancer Institute (NCI) Cancer Research Data Commons and Sage Bionetworks to apply the DGLink framework across numerous portals covering heterogeneous data modalities, enabling cross-portal data discovery over the NCI Genomic, Proteomic, and General Data Commons through a combined knowledge graph representation
* Implemented a modular framework for annotating arbitrary experimental file types, including schema-matching-based tabular data harmonization
* LLM agents given DGLink KGs achieve up to 4× lower query time and cost, and improve F1 from 0.50 to 0.90, versus the same agent with only portal API access

**[Similarity-Based Load-Balancing for Distributed Genomic Indices]({{ base_path }}/portfolio/genomic-load-balancing/)**
* Implemented a general-purpose load-balancing strategy leveraging sketching data structures to efficiently distribute genomic sequences over distributed indices
* Conducted comprehensive system benchmarking against baseline load-balancing methods, varying both the number of files to be distributed and the number of workers
* Found our method reduces index color table size by up to 8% and stored k-mer count by up to 15% over baseline

**[Risk-Controlled Prediction Sets for Entity Linking]({{ base_path }}/portfolio/rcps-entity-linking/)**
* Developed a model-agnostic framework leveraging conformal inference to reduce candidate set size when linking free-text entity mentions to identifiers in standard resources, while maintaining statistical risk control
* Method achieves 50% candidate size reduction while only reducing hits@5 from 0.75 to 0.73 for the KRISSBERT model on the BC5CDR benchmark dataset

**[Weakly Supervised Representation Learning for Cross-Ontology Mapping]({{ base_path }}/portfolio/cross-ontology-mapping/)**
* Co-mentoring a group of NYU M.S. in Data Science students for their program capstone project
* Developed a weakly supervised RAG approach for identifying equivalent classes across ontologies, leveraging a SapBERT embedding model fine-tuned on SeMRA ontology mapping landscapes
* Method improves hits@1 (0.79 to 0.93) over a TF-IDF baseline on the MONDO–MeSH ontology matching benchmark

Research experience
======
**PhD Student, Gyori Lab for Computational Biomedicine** — Northeastern University, Khoury College of Computer Sciences, Boston, MA *(Sept 2025 – present)*
* Lead developer on DGLink, collaborating with the NCI Cancer Research Data Commons and Sage Bionetworks on portal integration (see Selected projects for technical details and results)
* Coordinate with lab collaborators on multiple side projects spanning database systems, computational genomics, and conformal prediction
* Mentored numerous graduate and undergraduate researchers in the lab

**Machine Learning Engineer, Advanced Computational Infrastructure Team** — Division of Research, Kaiser Permanente, Pleasanton, CA *(May 2024 – May 2025)*
* Consulted as a machine learning subject-matter expert across 10+ projects under six Principal Investigators; mentored undergraduate and graduate summer interns
* Optimized and containerized DICOM-based breast cancer risk models (Mirai) for the Radiomic and Genomic Predictors of Breast Cancer Risk project (PI: Dr. Laurel A. Habel); used GitLab CI/CD to ensure continuous model availability across 250,000+ patient records; contributed data curation and formal analysis to a resulting comparative study of AI, polygenic, and clinical risk models published in JNCI (2026)
* Led development of NLP models (traditional ML and LLM-based) for identifying breast cancer in clinical pathology reports under Dr. Lawrence Gerstley; best model achieved 0.952 AUPRC across 150,000 reports and was deployed as a RESTful API
* Administered a healthcare-system-wide, PHI-heavy Kubernetes cluster supporting clinical and research workflows

**Research Associate, Dey Lab** — Computational & Systems Biology, Memorial Sloan Kettering Cancer Center, New York, NY *(Sept 2023 – June 2024)*
* Researched graphical machine learning methods (RotatE, TxGNN, GraphSAGE) for embedding and link prediction on a cancer-focused knowledge graph; project was a finalist for Meta's Llama Impact Grant
* Constructed multi-modal (demographic, genomic, mutation, treatment) knowledge graphs spanning 75,000+ cancer patients
* Developed inference models for cancer-relevant prediction tasks (e.g., cancer type from demographics, best treatment given cancer type), achieving a peak mean residual rank of 0.84/1.0 across tasks

**Computational Researcher, Hochwagen Lab** — Department of Biology, New York University, New York, NY *(Apr 2023 – July 2024)*
* Built a pipeline to download, filter, and process rRNA sequences from large public databases, constructing a dataset of 3,202+ humans' rRNA across diverse populations
* Analyzed rRNA sequence variance to identify highly conserved regions where mutations are likely to affect health; verified findings against simulated data with known mutations
* Contributed to a study of purifying selection on human 47S rRNA genes, published in PNAS (2026)

**Summer Research Intern, Cirrone Lab** — Department of Precision Medicine, NYU Langone Health, New York, NY *(May – Sept 2022)*
* Built a prediction model for individual patient response to biologic DMARDs using longitudinal data from 600+ rheumatoid arthritis patients
* Developed a novel two-stage ensemble model (severity regression followed by response classification), improving classification accuracy from 0.67 to 0.75 over baseline while increasing clinical interpretability

Talks & posters
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching & mentorship
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service & leadership
======
* President, PhD Social Committee, Khoury College of Computer Sciences, Northeastern University (2025 – present)
* Capstone Mentor, NYU Center for Data Science / Northeastern University (2025 – present)
* Summer Intern Mentor, Kaiser Permanente Division of Research (2024 – 2025)
* Secretary, Out in STEM, NYU (2022 – 2024)
* Secretary, Math Society, Courant Institute of Mathematical Sciences, NYU (2021 – 2022)

Technical skills
======
* **Programming:** Python, Rust, SQL, R, Bash, LaTeX, Java, PyTorch, TensorFlow, JAX, ONNX, Polars, Pandas
* **Knowledge graphs & biomedical NLP:** Neo4j / Cypher, INDRA, Gilda, ontology/schema matching (heuristic & LLM-based), ICD-10-CM, RCPS/conformal prediction
* **Databases:** Neo4j, MySQL, PostgreSQL, Redis, Oracle DB, Azure SQL, MongoDB, Elasticsearch
* **Infrastructure:** Git, Docker / Docker Compose, Kubernetes, Spark, Airflow, Ansible, GitLab CI/CD, SLURM / HPC cluster computing
