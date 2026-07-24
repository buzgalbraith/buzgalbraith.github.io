---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Computer Science (Computational Biology & Machine Learning Research Areas), Northeastern University, Khoury College of Computer Sciences, 2025 – present (GPA: 3.9/4.0)
  * Advised by Prof. Benjamin M. Gyori, Gyori Lab for Computational Biomedicine
  * Research spans biomedical knowledge graph construction, ontology matching, entity grounding, and computational genomics
  * Honors: ISMB Travel Fellowship ($500, 2026); Distinguished Research Fellow, Khoury College of Computer Sciences ($61,500, 2025)
* M.S. in Data Science (focus in Biomedical Informatics), New York University, 2022 – 2024 (GPA: 3.9/4.0)
  * Thesis: *A Knowledge Graph-Driven Approach to Understanding Cancer Risks and Treatment Recommendations* (advised by Dr. Kushal Dey, Memorial Sloan Kettering Cancer Center)
  * Coursework: Single-Cell Analysis, Deep Learning, ML for Health Care, Proteomics, Big Data, Causal Inference
* B.A. in Data Science and Economic Theory, Minor in Mathematics, New York University, 2018 – 2022 (GPA: 3.8/4.0)
  * Honors: Capital One Undergraduate Research Program ($8,000, 2022); Cum Laude (2022)

Research experience
======
**Machine Learning Engineer, Advanced Computational Infrastructure Team** — Division of Research, Kaiser Permanente, Pleasanton, CA *(May 2024 – 2025)*
* Consulted as a machine learning subject-matter expert across 10+ projects under six Principal Investigators; mentored undergraduate and graduate summer interns
* Optimized and containerized DICOM-based breast cancer risk models (Mirai); used GitLab CI/CD to ensure continuous model availability across 250,000+ patient records; contributed data curation and formal analysis to a comparative study published in JNCI (2026)
* Led development of NLP models (traditional ML and LLM-based) for identifying breast cancer in clinical pathology reports; best model achieved 0.952 AUPRC across 150,000 reports and was deployed as a RESTful API
* Administered a healthcare-system-wide, PHI-heavy Kubernetes computing cluster supporting clinical and research workflows

**Research Associate, Dey Lab** — Computational & Systems Biology, Memorial Sloan Kettering Cancer Center, New York, NY *(Sept 2023 – May 2024)*
* Researched graphical ML methods (RotatE, TxGNN, GraphSAGE) for embedding and link prediction on a cancer-focused knowledge graph; project was a finalist for Meta's Llama Impact Grant
* Constructed multi-modal (demographic, genomic, mutation, treatment) knowledge graphs spanning 75,000+ cancer patients
* Developed inference models for cancer-relevant prediction tasks, achieving a peak mean residual rank of 0.84/1.0 across tasks

**Computational Researcher, Hochwagen Lab** — Department of Biology, New York University, New York, NY *(Apr 2023 – May 2024)*
* Built a pipeline to download, filter, and process rRNA sequences from large public databases, constructing a dataset of 3,202+ humans' rRNA across diverse populations
* Analyzed rRNA sequence variance to identify highly conserved regions where mutations are likely to affect health
* Contributed to a study of purifying selection on human 47S rRNA genes, published in PNAS (2026)

**Summer Research Intern, Cirrone Lab** — Department of Precision Medicine, NYU Langone Health, New York, NY *(May – Sept 2022)*
* Built a prediction model for individual patient response to biologic DMARDs using longitudinal data from 600+ rheumatoid arthritis patients
* Developed a two-stage ensemble model, improving classification accuracy from 0.67 to 0.75 over baseline; work resulted in a co-authored publication (Chen et al., 2022)

Skills
======
* **Programming:** Python, Rust, SQL, R, Bash, LaTeX, Java
* **ML / Data:** PyTorch, TensorFlow, JAX, ONNX, Polars, Pandas
* **Knowledge Graphs & Biomedical NLP:** Neo4j / Cypher, INDRA, Gilda, ontology/schema matching (heuristic & LLM-based), ICD-10-CM, RCPS/conformal prediction
* **Databases:** MySQL, PostgreSQL, Redis, Oracle DB, Azure SQL, MongoDB, Elasticsearch
* **Infrastructure:** Git, Docker / Docker Compose, Kubernetes, Spark, Airflow, Ansible, GitLab CI/CD, SLURM / HPC cluster computing
* **Other:** Neovim, tmux, uv, MCP/LLM chat interface development

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
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
* PhD Social Committee, Khoury College of Computer Sciences, Northeastern University (2025 – present)
* Co-mentor, NYU M.S. capstone students, LeonMap ontology-mapping project (2025 – present)
* Mentor, undergraduate and graduate summer interns, Kaiser Permanente Division of Research (2024 – 2025)
* Secretary, Out in STEM, NYU (2022 – 2024)
* Secretary, Math Society, Courant Institute of Mathematical Sciences, NYU (2021 – 2022)
