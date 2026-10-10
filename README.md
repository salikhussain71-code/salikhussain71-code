Salik Hussain | AI Research & Engineering

<div align="center"><img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:080D1B,45:102A43,100:00B4D8&text=SALIK%20HUSSAIN&fontSize=54&fontColor=FFFFFF&fontAlignY=37&desc=Computer%20Science%20%7C%20Urdu%20NLP%20%7C%20Trustworthy%20AI&descSize=17&descAlignY=59&descColor=BAE6FD" width="100%" alt="Salik Hussain — AI Research and Engineering"/><a href="https://github.com/salikhussain71-code">
<img src="https://img.shields.io/badge/GitHub-Research%20%26%20Code-111827?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>
<a href="https://linkedin.com/in/salik-hussain-7822a1388">
<img src="https://img.shields.io/badge/LinkedIn-Professional%20Profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="https://kaggle.com/salikhussain">
<img src="https://img.shields.io/badge/Kaggle-Data%20Science-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle"/>
</a>
<a href="https://x.com/salikhussain71">
<img src="https://img.shields.io/badge/X-Research%20Updates-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"/>
</a>BS Computer Science Student · Iqra University, Islamabad, Pakistan

Research interests: Low-Resource NLP · Urdu and Roman Urdu · Information Retrieval · Trustworthy RAG

"Research Projects" (#-research-projects) · "Publications" (#-research-papers) · "Academic Roadmap" (#-four-year-academic--research-roadmap) · "Technical Skills" (#-technical-skills)

</div>---

01. About

I am Salik Hussain, a Computer Science undergraduate at Iqra University, Islamabad, Pakistan. I began my BS Computer Science degree in October 2026 after studying Pre-Medical at the intermediate level.

My long-term goal is to contribute to internationally competitive AI research, particularly in natural language processing, multilingual systems, information retrieval, and reliable language-model applications.

I am especially interested in one question:

«Can AI systems understand Urdu, Roman Urdu, and Urdu-English mixed text while providing accurate, verifiable answers supported by evidence?»

My research direction focuses on language access, reproducible evaluation, transparent evidence, and practical AI systems for public information.

I want my work to be useful to researchers and real users. That means documenting experiments, comparing appropriate baselines, reporting limitations, respecting dataset licenses, and publishing results that other people can reproduce.

Research principles

- Evidence before claims: report measured results, not expected results.
- Baselines before complexity: compare simple methods before adding advanced models.
- Reproducibility: publish evaluation procedures, configurations, and limitations.
- Responsible data use: respect copyright, privacy, licenses, and source permissions.
- Research before publication targets: choose a conference or journal according to the actual contribution.

Academic profile

Item| Details
Current degree| BS Computer Science
University| Iqra University, Islamabad
Degree start| October 2026
Expected degree period| 2026–2030, subject to the university's academic schedule
Primary research interest| Low-resource and multilingual NLP
Secondary research interest| Retrieval-augmented generation and AI reliability
Geographic base| Rawalpindi, Pakistan
Long-term objective| Competitive, fully funded postgraduate study and AI research

---

02. Research Direction

<div align="center"><img src="https://img.shields.io/badge/01-LANGUAGE%20UNDERSTANDING-0EA5E9?style=flat-square" alt="Language understanding"/>
<img src="https://img.shields.io/badge/02-RETRIEVAL%20%26%20EVIDENCE-14B8A6?style=flat-square" alt="Retrieval and evidence"/>
<img src="https://img.shields.io/badge/03-RELIABILITY-8B5CF6?style=flat-square" alt="Reliability"/>
<img src="https://img.shields.io/badge/04-REAL--WORLD%20IMPACT-F59E0B?style=flat-square" alt="Real-world impact"/></div>My research plan connects five projects rather than treating them as five unrelated portfolio exercises.

flowchart TD
    A["Urdu, Roman Urdu and Mixed Text"] --> B["P1: Urdu-RomanX"]
    B --> C["P2: UrduQA-Reason"]
    C --> D["P3: UrduCodeSwitch-Bench"]
    B --> E["P4: UrduIE-KG"]
    C --> F["P5: PAKGOV-RAG-X"]
    D --> F
    E --> F
    F --> G["Open-source tools and datasets"]
    F --> H["Research papers and reproducible evaluation"]
    G --> I["Feedback from real users"]
    H --> J["Further research"]
    I --> J

The five projects are planned research directions, not five completed results. Each project must earn its place through a clear research question, suitable baselines, valid experiments, and a useful contribution.

---

03. Research Projects

Project 1 — Urdu-RomanX

Working title: Robust Representation Learning Across Urdu, Roman Urdu, and Urdu-English Code-Switched Text.

Planned period: Year 1–Year 2.

Research question: How much does model performance change when the same language is written in Urdu script, Roman Urdu, or mixed Urdu-English text?

Planned work

- Collect or identify legally usable datasets.
- Document differences in spelling, transliteration, and code-switching.
- Establish baseline models before testing more advanced methods.
- Compare performance across scripts and language mixtures.
- Measure where models fail and which examples are difficult.
- Investigate cross-script transfer and parameter-efficient fine-tuning where justified.

Initial model candidates: multilingual BERT, XLM-R, and appropriate existing Urdu-language models.

Evaluation: task-specific F1, precision, recall, accuracy, and cross-script performance differences.

Planned outputs: research repository, documented evaluation suite, dataset or data-processing tools where permitted, model comparisons, and a research manuscript if the results justify publication.

Main learning areas: Python, data processing, tokenization, PyTorch, Transformers, statistics, and experimental design.

Status: Planned.

---

Project 2 — UrduQA-Reason

Working title: Evidence-Grounded Question Answering for Urdu and Urdu-English Public Information.

Planned period: Year 2.

Research question: Can a question-answering system identify relevant evidence, answer multi-step questions, and abstain when the available documents do not support an answer?

Planned work

- Build a carefully documented question-answering evaluation set.
- Include answerable, unanswerable, and multi-step questions.
- Test whether retrieved passages actually support generated answers.
- Investigate conflicting evidence and document-version differences.
- Compare retrieval methods and answer-generation approaches.
- Analyze incorrect answers and unsupported claims.

Evaluation: Exact Match, token-level F1, Recall@5, Recall@10, MRR, nDCG, evidence recall, citation correctness, and abstention quality.

Planned outputs: dataset or benchmark, baseline implementations, evaluation scripts, documentation, and a possible research paper.

Main learning areas: information retrieval, question answering, evaluation methodology, language models, and data annotation.

Status: Planned.

---

Project 3 — UrduCodeSwitch-Bench

Working title: Reliability, Factuality, and Robustness Evaluation Across Urdu, Roman Urdu, and Urdu-English Code-Switched Text.

Planned period: Year 2–Year 3.

Research question: Do AI systems maintain comparable quality and factual reliability when questions are written in different scripts or mixed languages?

Planned work

- Define controlled evaluation tasks.
- Create comparable examples across language forms.
- Evaluate factual consistency and evidence grounding.
- Test robustness to spelling variations and transliteration.
- Examine appropriate safety and refusal behavior.
- Publish a transparent model-comparison methodology.

Evaluation: task accuracy, F1, consistency across language forms, groundedness, unsupported-claim rate, and carefully defined safety measures.

Planned outputs: benchmark, evaluation framework, baseline results, model-comparison tables, and a possible research paper.

Research requirement: the benchmark must provide a defensible contribution beyond simply translating existing English tests into Urdu.

Status: Planned.

---

Project 4 — UrduIE-KG

Working title: Urdu Information Extraction, Entity Linking, Relation Extraction, and Knowledge-Graph Construction.

Planned period: Year 3.

Research question: How reliably can structured information be extracted from Urdu documents and linked to the correct entities?

Planned pipeline

flowchart LR
    A["Urdu Documents"] --> B["Text Cleaning"]
    B --> C["Named Entity Recognition"]
    C --> D["Entity Linking"]
    D --> E["Relation Extraction"]
    E --> F["Knowledge Graph"]
    F --> G["Validation and Evaluation"]

Planned entities: people, organizations, locations, dates, laws, policies, and events.

Planned work

- Identify a permitted and clearly scoped document collection.
- Establish extraction baselines.
- Create a documented annotation and evaluation procedure.
- Evaluate entity recognition and relation extraction separately.
- Measure entity-linking errors.
- Test graph consistency and source traceability.

Evaluation: entity-level precision, recall, F1, relation extraction F1, linking accuracy, and graph-quality checks.

Planned outputs: extraction pipeline, evaluation data where permitted, documentation, visualizations, and a possible research paper.

Status: Planned.

---

Project 5 — PAKGOV-RAG-X

Working title: Evidence-Grounded Bilingual Retrieval-Augmented Generation for Pakistani Government, Legal, and Public Information.

Planned period: Year 3–Year 4.

Relationship to previous work: PAKGOV-RAG-X is the planned next stage of my earlier PAKGOV-RAG pilot. The pilot and the future version will be documented separately so that results are not confused.

Research question: How can a retrieval-augmented generation system provide useful answers in English, Urdu, and Roman Urdu while clearly identifying supporting official documents?

Planned sources: suitable official Pakistani government and legal documents, subject to source availability, permissions, and document-specific terms.

Planned engineering pipeline

flowchart TD
    A["Official Source Documents"] --> B["Ingestion and Version Tracking"]
    B --> C["Cleaning and Chunking"]
    C --> D["BM25 Retrieval"]
    C --> E["Dense Retrieval"]
    D --> F["Hybrid Retrieval"]
    E --> F
    F --> G["Optional Reranking"]
    G --> H["Answer Generation"]
    H --> I["Evidence and Citation Verification"]
    I --> J["Answer with Sources"]
    I --> K["Abstain or Flag Unsupported Answer"]

Planned comparisons

1. BM25 retrieval.
2. Dense-vector retrieval.
3. Hybrid retrieval.
4. Hybrid retrieval with reranking.
5. Retrieval-augmented generation.
6. Retrieval-augmented generation with evidence verification.

Planned evaluation

Category| Measures
Retrieval| Recall@5, Recall@10, MRR, nDCG
Answer quality| Exact Match, F1, and task-appropriate correctness checks
Evidence| Evidence recall and support for generated claims
Citations| Citation precision, citation recall, and source correctness
Reliability| Unsupported-claim rate, abstention quality, and failure analysis
Engineering| Latency, throughput where relevant, and inference cost

These are planned measurements. Results will be reported only after the corresponding experiments have been run.

Planned outputs: reproducible research code, a documented benchmark, a web application, an API where practical, an evaluation dashboard, and a possible research paper.

Status: Pilot work exists; the expanded research version is planned.

---

04. Research Papers

Three papers are planned. None is presented as accepted, published, or under review unless that status is independently established.

Paper| Working title| Connected project| Current status
1| Urdu-RomanX: Robust Representation Learning Across Urdu, Roman Urdu, and Urdu-English Text| Project 1| Planned
2| UrduCodeSwitch-Bench: Reliability, Factuality, and Robustness Evaluation Across Language Forms| Project 3| Planned
3| PAKGOV-RAG-X: Evidence-Grounded Bilingual RAG for Pakistani Public Information| Project 5| Planned

Potential publication venues

Research area| Venues to evaluate
NLP and multilingual language technology| ACL, EMNLP, NAACL, COLING
Information retrieval| SIGIR
Machine learning evaluation and datasets| NeurIPS Datasets and Benchmarks, where the work fits its scope

Submission principle: venue selection will depend on novelty, experimental quality, ethical compliance, dataset quality, and the venue's current call for papers. A project title alone does not establish conference-level novelty.

Before submission, each manuscript must include related work, a precise research question, a defensible methodology, baseline comparisons, limitations, reproducibility information, and required ethical disclosures.

---

05. Research Internships and External Experience

The following opportunities are targets, not confirmed placements. Eligibility, funding, application dates, and project availability must be checked against each program's official announcement for the relevant year.

Target| Intended period| Purpose
LUMS research opportunity| Summer 2028| Seek supervised research experience in NLP or related AI areas
Funded international research program| Summer 2029| Apply for a suitable undergraduate research placement
Remote research collaboration| Winter 2028–2029, if available| Contribute to a legitimate research project with clear supervision and authorship expectations

Programs to monitor

- "LUMS — official university website" (https://lums.edu.pk/)
- "NUST — official university website" (https://nust.edu.pk/)
- "KAUST — official university website" (https://www.kaust.edu.sa/)
- "ETH Zurich — official university website" (https://ethz.ch/)
- "EPFL — official university website" (https://www.epfl.ch/)
- "MBZUAI — official university website" (https://mbzuai.ac.ae/)
- "Cohere — official website" (https://cohere.com/)

These links are starting points, not confirmation that a particular internship is currently open, fully funded, available to Pakistani undergraduates, or suitable for my year of study.

Application preparation

Before applying, I intend to prepare:

1. An accurate academic CV.
2. An official transcript.
3. A concise research statement.
4. Links to reproducible projects and experiments.
5. A short explanation of my contribution to each project.
6. Recommendation letters, when appropriate.
7. English-language evidence and other documents if required.
8. Funding, travel, visa, and accommodation information for the specific program.

I will apply only when I satisfy the actual eligibility requirements.

---

06. Three Research-Based AI Products

These are possible products that may emerge from the research. They are not three existing commercial businesses.

flowchart TD
    A["Research and Evaluation"] --> B["AI Reliability Lab"]
    A --> C["GovAI Studio"]
    A --> D["UrduAI Enterprise"]
    B --> E["Research and Engineering Feedback"]
    C --> E
    D --> E
    E --> A

AI Reliability Lab

Purpose: evaluate AI applications for evidence grounding, citation correctness, multilingual quality, and unsupported answers.

Possible users include research teams, developers, and AI startups.

GovAI Studio

Purpose: provide document search and question answering for authorized public or organizational documents, with traceable sources.

Possible users include educational institutions, researchers, NGOs, and legal-information teams.

UrduAI Enterprise

Purpose: develop Urdu and Roman Urdu tools for search, classification, question answering, summarization, and information extraction.

Possible users include education, media, and organizations that work with Urdu text.

Product development rules

- Validate a real user problem before building a commercial product.
- Respect document access rights and privacy requirements.
- Test performance on real, permitted examples.
- Publish limitations and avoid unsupported accuracy claims.
- Do not claim customers, revenue, or adoption without evidence.

---

07. Four-Year Academic & Research Roadmap

Academic period: October 2026–2030, subject to the university's official academic calendar.

The curriculum tables below preserve the courses and credit allocations in my supplied study plan. Course codes, semester placement, electives, and the pre-medical deficiency requirements should be checked against the applicable official Iqra University prospectus and approved individual study plan before being described as officially verified.

Year 1 — Foundations

Main priorities: academic performance, programming, mathematics, research habits, and one manageable research project.

<details open>
<summary><strong>Semester 1 — Fall 2026</strong></summary>Code| Course| Credits
CMC111| Programming Fundamentals| 3+0
CMC111-L| Programming Fundamentals (Lab)| 0+1
GER111| Application of ICT| 2+0
GER111-L| Application of ICT (Lab)| 0+1
GER121| Functional English| 3+0
IDS111| IDS-I (Calculus & Analytic Geometry)| 3+0
GERxxx| Natural Science*| 2+0
GERxxx-L| Natural Science (Lab)| 0+1

Academic focus

- Learn programming fundamentals and solve problems independently.
- Build strong calculus foundations.
- Learn Git, GitHub, and basic command-line use.
- Develop a consistent study and revision system.
- Review the existing PAKGOV-RAG pilot and document its limitations.

Research focus: establish a realistic project scope and baseline plan. Do not rush into a new large model or a paper before the fundamentals are in place.

</details><details>
<summary><strong>Semester 2 — Spring 2027</strong></summary>Code| Course| Credits
GERxxx| Arts & Humanities*| 2+0
CMC112| Object-Oriented Programming| 3+0
CMC112-L| Object-Oriented Programming (Lab)| 0+1
CMC121| Digital Logic Design| 3+0
CMC121-L| Digital Logic Design (Lab)| 0+1
IDS112| IDS-II (Linear Algebra)| 3+0
GERxxx| Quantitative Reasoning-I*| 3+0
GER241| Pakistan Studies| 2+0
GEN111| Understanding of the Holy Quran-I*| 0+1

Academic focus

- Strengthen object-oriented programming and problem solving.
- Study linear algebra carefully.
- Begin Python for data processing and experiments.
- Learn basic probability and statistics alongside coursework.

Research focus: start Project 1, Urdu-RomanX, with a narrow task and an existing baseline. Begin with data inspection and evaluation before fine-tuning models.

</details>Year 2 — Core Computer Science and Initial Research

<details>
<summary><strong>Semester 3</strong></summary>Code| Course| Credits
GERxxx| Quantitative Reasoning-II*| 3+0
CMC331| Database Systems| 3+0
CMC331-L| Database Systems (Lab)| 0+1
CMC251| Data Structures| 3+0
CMC251-L| Data Structures (Lab)| 0+1
GERxxx| Social Science*| 2+0
CMC262| Computer Networks| 2+0
CMC262-L| Computer Networks (Lab)| 0+1
GEN112| Understanding of the Holy Quran-II*| 0+1
GER122| Expository Writing| 3+0

Academic focus

- Master data structures, database design, and algorithmic thinking.
- Use writing assignments to practice clear technical explanations.
- Learn reproducible experiments and version control.

Research focus: continue Urdu-RomanX and plan Project 2, UrduQA-Reason. Define the datasets, questions, metrics, and baselines before expanding the scope.

</details><details>
<summary><strong>Semester 4</strong></summary>Code| Course| Credits
GER443| Civics and Community Engagement| 2+0
GER141| Islamic Studies| 2+0
GER464| Entrepreneurship| 2+0
CMC241| Operating Systems| 3+0
CMC241-L| Operating Systems (Lab)| 0+1
CMC254| Design & Analysis of Algorithms| 3+0
GER142| Ideology & Constitution of Pakistan| 2+0
CMC371| Software Engineering| 3+0

Academic focus

- Strengthen algorithms, operating systems, and software engineering.
- Improve code quality, testing, and project documentation.
- Build a research CV containing only demonstrated work.

Research focus: aim
