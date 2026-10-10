Salik Hussain | AI Research, Urdu NLP & Trustworthy AI

<div align="center"><img src="https://capsule-render.vercel.app/api?type=waving&color=0:101827,50:164e63,100:0891b2&height=230&section=header&text=SALIK%20HUSSAIN&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=Computer%20Science%20%7C%20Multilingual%20AI%20%7C%20Research%20Engineering&descSize=16&descAlignY=61" width="100%" alt="Salik Hussain profile banner"/>BS Computer Science Student · Iqra University Islamabad · Fall 2026–2030

Building reliable AI systems for Urdu, Roman Urdu, and multilingual public information.

"GitHub" (https://github.com/salikhussain71-code) · "LinkedIn" (https://www.linkedin.com/in/salik-hussain-7822a1388) · "Kaggle" (https://www.kaggle.com/salikhussain) · "X" (https://x.com/salikhussain71) · "Portfolio" (https://salik.dev)

<img src="https://img.shields.io/badge/Focus-Urdu%20NLP-0e7490?style=for-the-badge" alt="Urdu NLP"/>
<img src="https://img.shields.io/badge/Focus-LLM%20Evaluation-334155?style=for-the-badge" alt="LLM evaluation"/>
<img src="https://img.shields.io/badge/Focus-RAG%20Systems-166534?style=for-the-badge" alt="RAG systems"/>
<img src="https://img.shields.io/badge/Location-Pakistan-166534?style=for-the-badge" alt="Pakistan"/></div>---

1. About Me

I am a Computer Science undergraduate at Iqra University Islamabad, Pakistan, beginning my BSCS degree in Fall 2026.

My long-term goal is to become an AI researcher and engineer working on multilingual language models, trustworthy AI systems, and machine learning for languages that receive limited attention in modern AI research.

My main research interest is the Urdu language ecosystem, including Urdu script, Roman Urdu, Urdu-English code-switching, and, in later work, Pashto.

I am interested in a practical but research-driven question:

How can we build AI systems that understand different language forms, retrieve reliable evidence, produce accurate answers, and clearly identify what they do not know?

My work connects four areas:

- Research: multilingual NLP, information retrieval, model evaluation, and reproducible experiments.
- Engineering: Python, data pipelines, retrieval systems, APIs, testing, and deployment.
- Open source: public code, documented experiments, useful datasets, and reproducible results.
- Real-world impact: making reliable public and institutional information easier to access.

I aim to build these skills throughout my undergraduate degree and prepare for competitive, fully funded graduate research opportunities.

2. Research Interests

Area| Research direction
Low-resource NLP| Better language technology for Urdu and other underrepresented languages
Multilingual AI| Cross-lingual transfer and language representation
Roman Urdu| Script variation, transliteration, and spelling robustness
Code-switching| Urdu-English mixed-language understanding
Information retrieval| Sparse, dense, hybrid, and reranking methods
Retrieval-Augmented Generation| Evidence-grounded answers with traceable sources
LLM evaluation| Factuality, citation correctness, robustness, and abstention
AI reliability| Testing models, detecting failures, and measuring regressions
Document intelligence| Extracting information and detecting changes in official documents
Responsible AI| Privacy, data permissions, transparency, and careful evaluation

My research direction is deliberately focused. I want to investigate related problems deeply rather than create many disconnected projects.

---

3. Current Work and Verified Progress

PAKGOV-RAG — Existing Project Foundation

My existing PAKGOV-RAG project is the starting point for my research roadmap.

It explores bilingual retrieval-augmented generation for Pakistani government and public-information documents.

The documented project work includes:

- Six official PDF documents.
- A corpus of 2,111 source pages.
- 6,711 text chunks.
- A 50-question evaluation set covering English, Urdu, and mixed-language queries.
- Sparse retrieval using BM25.
- Dense retrieval using multilingual embeddings.
- Hybrid retrieval using reciprocal rank fusion.
- Retrieval metrics, including Recall@k, MRR, and nDCG.
- Source-grounded answer assessment and documented failure analysis.
- A Streamlit demonstration.

The existing evaluation reported the following results:

Retrieval method| Recall@5| Recall@10| MRR| nDCG@10
BM25| 0.360| 0.580| 0.640| 0.680
Dense retrieval| 0.440| 0.600| 0.620| 0.740
Hybrid retrieval| 0.500| 0.660| 0.740| 0.820

The hybrid method performed best on these reported retrieval measures in the existing 50-question evaluation.

These results are preliminary and limited to the documented corpus and test set. They do not establish performance on all Pakistani government documents or all Urdu queries.

The existing answer assessment recorded 37 cited answers and 13 cases marked insufficient, out of 50 questions. Citation presence alone does not establish that every answer is factually correct or fully supported.

Next step: expand the evaluation carefully, strengthen the evidence checks, add more diverse test cases, and compare methods under controlled conditions.

Repository: "PAKGOV-RAG Project" (https://github.com/salikhussain71-code/PAKGOV-RAG-project)

---

4. Five Flagship Research Projects

These are five connected projects planned for development during my BSCS degree. Their research claims and results will be reported only after the corresponding work has been completed and evaluated.

Project 1 — Urdu-RomanX

Full title: Robust Representation Learning Across Urdu, Roman Urdu, and Urdu-English Code-Switched Text.

Research question: How much does AI performance change when the same meaning is expressed in Urdu script, Roman Urdu, or mixed Urdu-English text?

Work plan

- Establish baseline results using existing multilingual models.
- Study differences in tokenization and spelling variation.
- Evaluate classification, semantic similarity, and retrieval.
- Test transliteration and cross-script transfer methods.
- Investigate parameter-efficient fine-tuning when justified.
- Analyze which language forms cause the largest performance gaps.

Planned outputs

- Reproducible experiments.
- A carefully documented evaluation dataset.
- Baseline comparisons.
- An evaluation toolkit.
- A technical report and, if the results justify it, a research paper.

Skills to develop: Python, PyTorch, Transformers, linear algebra, probability, statistics, and experimental design.

Target period: Years 1–2.

Project 2 — UrduQA-Reason

Full title: Evidence-Grounded Multi-Hop and Unanswerable Question Answering for Urdu and Urdu-English Public Information.

Research question: Can an AI system answer complex questions using verifiable evidence, and can it recognize when the available documents do not contain enough information?

Work plan

- Create questions that require one or more pieces of evidence.
- Include answerable and unanswerable questions.
- Include questions requiring comparison across documents.
- Test English, Urdu, Roman Urdu, and mixed-language queries where appropriate.
- Compare retrieval, reranking, and answer-generation methods.
- Verify whether cited passages actually support each answer.

Evaluation measures

Recall@5, Recall@10, MRR, nDCG, exact match where appropriate, answer F1, evidence recall, citation correctness, and unsupported-claim rate.

Planned outputs: evaluation dataset, baseline systems, question-answering pipeline, documentation, and a possible research paper.

Target period: Year 2.

Project 3 — UrduCodeSwitch-Bench

Full title: Reliability, Factuality, Safety, and Robustness Evaluation Across Urdu, Roman Urdu, and Code-Switched Text.

Research question: Do AI systems preserve their accuracy, evidence quality, and safety when users change scripts or mix languages?

Work plan

- Evaluate multiple model families.
- Compare equivalent questions across language forms.
- Measure factual consistency and evidence support.
- Test unanswerable questions and appropriate refusal.
- Investigate robustness to spelling changes and linguistic variation.
- Evaluate carefully controlled prompt-injection scenarios.
- Document failure categories and reproducible test cases.

Planned outputs

- A benchmark with a documented evaluation protocol.
- Baseline results.
- A public leaderboard, if feasible.
- A reproducible evaluation package.
- A possible research paper.

The benchmark will distinguish measured results from hypotheses. It will not claim that an approach improves safety or reliability until experiments support that conclusion.

Target period: Years 2–3.

Project 4 — UrduIE-KG

Full title: Urdu Information Extraction, Entity Linking, Relation Extraction, and Knowledge-Graph Construction.

Research question: Can structured information be extracted reliably from Urdu documents and connected to identifiable entities and relationships?

Work plan

- Identify entities such as organizations, people, locations, dates, and laws.
- Develop or evaluate Urdu named-entity recognition.
- Investigate entity linking and relation extraction.
- Build a structured representation of verified information.
- Evaluate extraction errors and entity-matching accuracy.
- Document uncertainty and source provenance.

Planned outputs: annotated data where permitted, extraction models, evaluation scripts, a knowledge-graph prototype, and technical documentation.

Target period: Year 3.

Project 5 — PAKGOV-RAG-X

Full title: Evidence-Grounded Multilingual Retrieval-Augmented Generation for Pakistani Government, Legal, and Public Information.

Research question: How can retrieval and verification methods make public-information AI systems more accurate, traceable, and robust across Urdu and English?

This project extends my existing PAKGOV-RAG foundation rather than starting a disconnected repository.

Work plan

1. Improve the quality and diversity of the document collection.
2. Record document titles, source URLs, dates, versions, and page references.
3. Establish stronger retrieval baselines.
4. Compare BM25, dense retrieval, hybrid retrieval, and reranking.
5. Evaluate generation using retrieved evidence.
6. Implement citation verification and answerability checks.
7. Test Urdu, English, Roman Urdu, and mixed-language queries as the dataset permits.
8. Conduct error analysis and publish reproducible evaluation results.
9. Develop a web application and API after the research pipeline is stable.

Evaluation measures: retrieval recall, MRR, nDCG, answer correctness, evidence support, citation precision, citation recall, unsupported claims, abstention quality, latency, and cost.

Planned outputs: open-source software, evaluation data where licensing permits, a web demonstration, an API, a technical report, and a possible research paper.

Target period: Years 3–4.

---

5. Three Planned Research Papers

These are research objectives, not claims of accepted or published papers.

Paper 1 — Urdu-RomanX

Proposed title: Robust Representation Learning Across Urdu, Roman Urdu, and Urdu-English Code-Switched Text.

Main contribution sought: A rigorous comparison of model performance across language forms, supported by reproducible experiments and a clear analysis of cross-script weaknesses.

Possible venues: ACL, EMNLP, NAACL, or COLING, depending on the contribution and submission requirements.

Target period: 2028–2029.

Paper 2 — UrduCodeSwitch-Bench

Proposed title: Measuring Reliability, Factuality, and Safety Across Urdu, Roman Urdu, and Urdu-English Code-Switching.

Main contribution sought: A well-designed benchmark that measures how language variation affects model reliability, with clear baselines and detailed failure analysis.

Possible venues: ACL, EMNLP, NAACL, or the NeurIPS Evaluations & Datasets track if the final work fits its scope.

Target period: 2029.

Paper 3 — PAKGOV-RAG-X

Proposed title: Evidence-Grounded Retrieval-Augmented Generation for Urdu and English Public Information.

Main contribution sought: A controlled study of retrieval, reranking, citation verification, and answerability for public-information question answering.

Possible venues: ACL, EMNLP, NAACL, SIGIR, or NeurIPS Evaluations & Datasets, depending on the scientific contribution.

Target period: 2029–2030.

Publication standard: A project does not automatically become a paper. Each submission must provide a clear research question, a review of related work, appropriate baselines, reproducible methods, honest limitations, and results that support its claims.

---

6. Three Proposed AI Products

The commercial roadmap will reuse the research rather than duplicate it.

Product 1 — PAKAI Verify

AI Reliability and Evaluation Platform

A tool for developers and research teams to evaluate LLM and RAG applications.

Potential capabilities:

- Retrieval-quality evaluation.
- Citation verification.
- Evidence-grounding checks.
- Multilingual test suites.
- Regression testing between model versions.
- Failure reports with examples.
- Latency and cost measurement.

Research connection: UrduCodeSwitch-Bench and PAKGOV-RAG-X.

Initial version: a local evaluation tool and report generator.

Later versions: a dashboard, API, and team workflow if users demonstrate a need.

Product 2 — GovAI Studio

Evidence-Grounded Document Intelligence

A document assistant for authorized institutional documents.

Potential capabilities:

- Search across documents.
- Answers with source references.
- Document summarization.
- Comparison between document versions.
- Structured information extraction.
- Change notifications.

Research connection: PAKGOV-RAG-X and UrduIE-KG.

The product will respect document permissions, privacy, licensing, and applicable terms of use.

Product 3 — UrduAI Enterprise

Multilingual AI Infrastructure

A potential API and software platform for Urdu, Roman Urdu, and Urdu-English workflows.

Possible services:

- Search.
- Question answering.
- Text classification.
- Information extraction.
- Summarization.
- RAG.
- Reliability evaluation.

Research connection: Urdu-RomanX, UrduCodeSwitch-Bench, and PAKGOV-RAG-X.

These products are proposed directions. Commercial demand, pricing, revenue, and customer numbers will not be claimed before they are measured.

---

7. Research Models, Datasets, and Benchmarks

The following are planned outputs, subject to research progress and data permissions.

Planned asset| Purpose| Connected project
Urdu-Roman representation model| Improve representations across scripts and language forms| Urdu-RomanX
PAK-RAG reranker| Improve evidence retrieval for public-information queries| PAKGOV-RAG-X
Reliability evaluator| Identify evidence, citation, and answerability failures| UrduCodeSwitch-Bench
PAK-AI-Bench| Evaluate multilingual RAG systems| PAKGOV-RAG-X
PAK-MultiBench| Compare performance across Urdu, Roman Urdu, and English| Urdu-RomanX
PAK-ReliabilityBench| Test grounding, robustness, and reliability| UrduCodeSwitch-Bench
Urdu information extraction dataset| Evaluate entities and relationships in Urdu documents| UrduIE-KG

Pashto may be added later if sufficient data, appropriate permissions, and suitable evaluation resources are available.

I will not release datasets or model weights unless the relevant source licences and release conditions permit it.

---

8. Technology Stack

The tools below form a learning and implementation roadmap. They are not all claims of current expertise.

Area| Tools to learn and use
Programming| Python, C++, SQL, Bash
Version control| Git, GitHub
Development| VS Code, Linux, virtual environments
Data processing| pandas, NumPy, PDF extraction tools
Machine learning| scikit-learn, PyTorch
NLP| Hugging Face Transformers, tokenizers
Information retrieval| BM25, vector search, FAISS
RAG| Hybrid retrieval, reranking, evidence evaluation
APIs| FastAPI
Applications| Streamlit; TypeScript where needed
Storage| SQLite or PostgreSQL, with vector storage when justified
Testing| pytest, data validation, regression tests
Research| Jupyter, LaTeX, experiment tracking
Deployment| GitHub Actions, Docker, and suitable hosting

Learning order

1. Programming fundamentals and problem solving.
2. Data structures and algorithms.
3. Mathematics for machine learning.
4. Python, NumPy, pandas, and data analysis.
5. Probability, statistics, and linear algebra.
6. Classical machine learning.
7. Deep learning and PyTorch.
8. NLP and transformer models.
9. Information retrieval and RAG.
10. Research methodology, reproducibility, and evaluation.
11. Deployment, APIs, and software engineering.
12. Advanced multilingual research.

---

9. Official BS Computer Science Curriculum

University: Iqra University Islamabad Campus
Degree: Bachelor of Science in Computer Science
Expected study period: 2026–2030
Curriculum basis: The BSCS curriculum supplied from the university website.

The university's supplied curriculum lists 130 credit hours for the standard BSCS route and 136 credit hours for the pre-medical route, including the additional mathematics-deficiency requirement.

The semester sequence below preserves the course titles, course codes, prerequisites, and structure provided in that curriculum. University decisions about course offerings, pools, and prerequisites take priority.

Semester 1 — Foundation

Course| Code| Credit hours
Programming Fundamentals| CMC111| 3+0
Programming Fundamentals Lab| CMC111-L| 0+1
Application of ICT| GER111| 2+0
Application of ICT Lab| GER111-L| 0+1
Functional English| GER121| 3+0
IDS-I: Calculus & Analytic Geometry| IDS111| 3+0
Natural Science| GERxxx| 2+0
Natural Science Lab| GERxxx-L| 0+1

Research and career additions

- Build a consistent programming practice routine.
- Learn Git and GitHub fundamentals.
- Strengthen algebra, functions, and precalculus.
- Understand basic command-line use.
- Maintain clear notes and a record of coursework.
- Read the existing PAKGOV-RAG code and documentation.
- Prioritize grades and understanding over starting several new projects.

Primary goal: strong fundamentals and a strong first-semester CGPA.

Semester 2 — Programming and Mathematics

Course| Code| Credit hours
Arts & Humanities| GERxxx| 2+0
Object-Oriented Programming| CMC112| 3+0
Object-Oriented Programming Lab| CMC112-L| 0+1
Digital Logic Design| CMC121| 3+0
Digital Logic Design Lab| CMC121-L| 0+1
IDS-II: Linear Algebra| IDS112| 3+0
Quantitative Reasoning-I| GERxxx| 3+0
Pakistan Studies| GER241| 2+0
Understanding of the Holy Quran-I| GEN111| 0+1

Research and career additions

- Improve C++ and object-oriented programming.
- Learn Python if the semester workload permits.
- Practise vectors, matrices, and linear transformations.
- Complete small, tested programming projects.
- Study the fundamentals of text processing.
- Begin reading introductory NLP papers.

Primary goal: programming competence and mathematical foundations.

Semester 3 — Data and Algorithms

Course| Code| Credit hours
Quantitative Reasoning-II| GERxxx| 3+0
Database Systems| CMC331| 3+0
Database Systems Lab| CMC331-L| 0+1
Data Structures| CMC251| 3+0
Data Structures Lab| CMC251-L| 0+1
Social Science| GERxxx| 2+0
Computer Networks| CMC262| 2+0
Computer Networks Lab| CMC262-L| 0+1
Understanding of the Holy Quran-II| GEN112| 0+1
Expository Writing| GER122| 3+0

Research and career additions

- Learn Python data analysis.
- Study probability and statistics.
- Learn SQL and database design.
- Implement basic search and ranking algorithms.
- Start Urdu-RomanX with a narrowly defined research question.
- Reproduce one manageable experiment from an existing paper.

Primary goal: turn programming skills into measurable technical work.

Semester 4 — Systems and Algorithmic Thinking

Course| Code| Credit hours
Civics and Community Engagement| GER443| 2+0
Islamic Studies| GER141| 2+0
Entrepreneurship| GER464| 2+0
Operating Systems| CMC241| 3+0
Operating Systems Lab| CMC241-L| 0+1
Design & Analysis of Algorithms| CMC254| 3+0
Ideology & Constitution of Pakistan| GER142| 2+0
Software Engineering| CMC371| 3+0

Research and career additions

- Study classical machine learning.
- Practise algorithm analysis and complexity.
- Learn PyTorch fundamentals.
- Develop an experimental pipeline with fixed datasets and documented settings.
- Review related Urdu NLP and QA research.
- Contact relevant faculty about supervised undergraduate research when eligible.

Primary goal: build the ability to understand and evaluate algorithms, not just use libraries.

Semester 5 — Artificial Intelligence and Security

Course| Code| Credit hours
Computer Organization & Architecture| CMC224| 2+0
Computer Organization & Architecture Lab| CMC224-L| 0+1
Information Security| CMC363| 2+0
Information Security Lab| CMC363-L| 0+1
Theory of Automata| CSC341| 3+0
Artificial Intelligence| CMC383| 2+0
Artificial Intelligence Lab| CMC383-L| 0+1
IDS-III| IDSxxx| 3+0
IDS-IV| IDSxxx| 3+0

Research and career additions

- Study deep learning and transformers.
- Develop Urdu-RomanX or UrduQA-Reason experiments.
- Learn experiment tracking and rigorous error analysis.
- Investigate research internships and faculty-supervised work.
- Prepare a research CV and a concise technical portfolio.
- Consider submitting a paper only when the results are mature enough.

Primary goal: move from tutorial-based development to controlled experiments.

Semester 6 — Advanced Engineering and Specialization

Course| Code| Credit hours
Cloud Computing| CMC355| 3+0
Elective I| University-assigned| 3+0
Elective II| University-assigned| 3+0
Elective III| University-assigned| 3+0
Elective IV| University-assigned| 3+0

Research and career additions

- Select electives relevant to AI, ML, NLP, data science, or related foundations when offered.
- Extend multilingual evaluation.
- Improve retrieval, reranking, and citation verification.
- Apply for suitable research internships or supervised projects.
- Develop a reliable software release and documentation process.

Primary goal: demonstrate depth in a defined research direction.

Semester 7 — Research and Internship

Course| Code| Credit hours
Elective V| University-assigned| 3+0
Elective VI| University-assigned| 3+0
Elective VII| University-assigned| 3+0
Field Experience / Internship| CMC493| 3+0
Final Year Design Project I| CMC491| 0+3

Research and career additions

- Complete an approved internship or field experience.
- Begin the final-year project under an appropriate supervisor.
- Consolidate the strongest benchmark and research findings.
- Prepare a research manuscript if the work supports a meaningful contribution.
- Seek detailed feedback from research mentors.
- Prepare a graduate-school shortlist based on published eligibility and funding policies.

Primary goal: demonstrate research independence and engineering reliability.

Semester 8 — Research Completion

Course| Code| Credit hours
Final Year Design Project II| CMC492| 0+3
Elective VIII| University-assigned| 3+0
Professional Certification| CMC494| 3+0

Research and career additions

- Complete and defend the final-year project.
- Release clean documentation and reproducible code where appropriate.
- Submit research to suitable venues when justified.
- Prepare recommendation requests well before application deadlines.
- Complete official graduate-school applications.
- Present a portfolio that distinguishes completed work from future plans.

Primary goal: graduate with strong fundamentals, evidence of research ability, and a credible record of technical contributions.

Mathematics deficiency for pre-medical students

The supplied university curriculum lists an additional six-credit mathematics-deficiency block for the pre-medical route. The precise course placement and registration must be confirmed with the university.

My additional preparation plan is to strengthen:

1. Algebra and functions.
2. Trigonometry and precalculus.
3. Calculus.
4. Vectors and matrices.
5. Linear algebra.
6. Probability and statistics.
7. Discrete mathematics.
8. Optimization.
9. Mathematics used in machine learning.

These are supplementary learning priorities, not replacements for official degree requirements.

---

10. Four-Year Research and Career Roadmap

<details>
<summary><strong>Year 1 — 2026–2027: Foundations</strong></summary>Main priorities

- Maintain strong academic performance.
- Learn C++, Python, Git, and Linux.
- Strengthen mathematics for computer science.
- Improve the existing PAKGOV-RAG project.
- Begin a small, testable Urdu-RomanX experiment.
- Read research papers with guidance.
- Learn how to document experiments and technical limitations.

Deliverables

- Consistent programming practice.
- Well-documented repositories.
- Reproducible baseline experiments.
- Strong semester results.
- A clear research notebook.

Do not start five major projects at once.

</details><details>
<summary><strong>Year 2 — 2027–2028: Research Foundations</strong></summary>Main priorities

- Complete introductory ML and NLP study.
- Develop Urdu-RomanX.
- Start UrduQA-Reason if the first project is under control.
- Learn academic writing and literature review.
- Seek a suitable research mentor.
- Apply for internships and summer research opportunities whose official eligibility you meet.

Deliverables

- A reproducible experiment.
- A technical report.
- A clearly documented dataset or evaluation protocol.
- A credible application portfolio.

A publication is possible only if the work makes a meaningful contribution; it is not guaranteed by the timeline.

</details><details>
<summary><strong>Year 3 — 2028–2029: Research Depth</strong></summary>Main priorities

- Expand UrduCodeSwitch-Bench.
- Develop UrduIE-KG where data and supervision permit.
- Extend PAKGOV-RAG-X.
- Pursue research internships or faculty-supervised projects.
- Prepare manuscript submissions when results justify them.
- Develop relationships with supervisors who directly observe the work.

Deliverables

- Rigorous benchmark results.
- A clear research contribution.
- Reproducible code and documentation.
- Stronger academic references based on actual supervision.

</details><details>
<summary><strong>Year 4 — 2029–2030: Flagship Research and Applications</strong></summary>Main priorities

- Complete the strongest research project.
- Finish the final-year design project.
- Submit mature research to suitable venues.
- Build a professional research CV.
- Request recommendations from faculty who know the work.
- Apply to appropriate funded MS or direct PhD programmes.

Deliverables

- A completed final-year project.
- A polished research portfolio.
- A record of actual research outcomes.
- A realistic graduate application strategy.

</details>---

11. Research Internship Strategy

The objective is to gain meaningful supervised research experience, not simply to collect internship titles.

Priority 1 — Undergraduate research in Pakistan

Investigate relevant research groups at:

- "NUST School of Electrical Engineering and Computer Science" (https://seecs.nust.edu.pk/)
- "LUMS" (https://lums.edu.pk/)
- "Iqra University Islamabad" (https://iuisl.iqra.edu.pk/)

Look for faculty working on NLP, machine learning, information retrieval, speech, or multilingual systems.

External-student eligibility, availability, funding, and application dates must be confirmed from the official programme or faculty source.

Priority 2 — International research programmes

Monitor the official programme pages for:

- "MBZUAI Global Research Internship Program" (https://mbzuai.ac.ae/academics/pathway-programs/mbzuai-global-research-internship-program)
- "KAUST Visiting Student Research Program" (https://admissions.kaust.edu.sa/study/internships)
- "ETH Zurich Student Summer Research Fellowship" (https://inf.ethz.ch/studies/summer-research-fellowship.html)
- "EPFL Summer Research Programmes" (https://www.epfl.ch/education/international/en/)

These are opportunities to investigate, not confirmed future placements. Eligibility, funding, programme availability, and deadlines can change between cycles.

Internship quality standard

For every placement, aim to produce:

- A defined research or engineering contribution.
- A record of work and results.
- Reproducible code or documentation where permitted.
- Feedback from a direct supervisor.
- A recommendation request only when the supervisor has sufficient evidence to evaluate the work.

---

12. Graduate Research Goals

My long-term objective is to pursue advanced study in AI, machine learning, or computer science at a research-intensive university.

Institutions I intend to investigate include:

- "MBZUAI" (https://mbzuai.ac.ae/)
- "KAUST" (https://www.kaust.edu.sa/)
- "Carnegie Mellon University" (https://www.cmu.edu/)
- "Stanford University" (https://www.stanford.edu/)
- "ETH Zurich" (https://ethz.ch/)
- "EPFL" (https://www.epfl.ch/)
- "National University of Singapore" (https://nus.edu.sg/)
- "KAIST" (https://www.kaist.ac.kr/)

These are target institutions, not predictions of admission.

My application strategy will depend on the official programme requirements at the time of application, including academic results, mathematical preparation, English proficiency, research experience, recommendation letters, and funding eligibility.

MS or direct PhD?

I will evaluate both routes rather than assume one is always superior.

A research-focused MS may be appropriate if I need deeper mathematical preparation, more research experience, or a stronger academic record before applying for a PhD.

Direct PhD applications may be appropriate if my academic preparation, research contributions, recommendations, and the target programme's eligibility requirements support that route.

I will compare the actual funding packages, programme structures, research fit, and eligibility rules before deciding.

---

13. Academic Standards and Research Principles

My target is strong academic performance, with a personal CGPA goal of 3.85/4.00 or higher where the university's grading scale permits that target.

This is a goal, not a claim about my current CGPA or a guarantee of future grades.

I will prioritize:

- Understanding mathematics rather than memorizing formulas.
- Strong programming fundamentals.
- Reliable data and evaluation practices.
- Reading relevant research before claiming novelty.
- Comparing against appropriate baselines.
- Reporting negative findings honestly.
- Respecting source permissions and data privacy.
- Documenting limitations and reproducibility.
- Publishing only when the contribution meets the venue's standards.

No project, certificate, internship, or paper guarantees admission to an elite university.

---

14. Open-Source Project Structure

As the work matures, the repository ecosystem may include:

salikhussain71-code/
|
|-- PAKGOV-RAG-project/
|-- Urdu-RomanX/
|-- UrduQA-Reason/
|-- UrduCodeSwitch-Bench/
|-- UrduIE-KG/
|-- PAKGOV-RAG-X/
|-- PAKAI-Verify/
|-- GovAI-Studio/
|-- UrduAI-Enterprise/

These names represent the planned ecosystem. They should not be treated as evidence that every repository is already implemented or publicly available.

Each repository should have:

- A clear problem statement.
- Installation instructions.
- A defined scope.
- A reproducible example.
- Appropriate tests.
- Source and dataset documentation.
- Honest evaluation results.
- Known limitations.
- Licensing and citation information.

I will create repositories when there is real work to share, rather than creating empty repositories to increase their number.

---

15. Professional Development and Public Impact

I aim to make my work useful to researchers, students, and developers working with Urdu and related languages.

Potential contributions include:

- Improving access to public information through evidence-grounded search.
- Publishing reproducible evaluation methods.
- Documenting model failures across language forms.
- Contributing to relevant open-source NLP tools.
- Sharing research notes and technical explanations.
- Building accessible demonstrations that clearly explain their limitations.

I will measure impact through verifiable evidence such as completed releases, documented experiments, external contributions, research feedback, and actual usage where available.

GitHub stars, downloads, users, revenue, citations, and publication counts will be reported only when they can be verified.

---

16. Current Learning Priorities

My immediate priorities are:

1. Programming Fundamentals and C++.
2. Calculus and precalculus preparation.
3. Linear algebra and probability as the curriculum progresses.
4. Python and scientific computing.
5. Git, GitHub, and Linux.
6. Data structures and algorithms.
7. Machine learning foundations.
8. Reproducible research practices.
9. Improving the existing PAKGOV-RAG project.
10. Building the first controlled experiments for Urdu-RomanX.

The order may change to fit university assessments, prerequisites, and research opportunities.

---

17. Contact and Collaboration

I welcome thoughtful discussions about Urdu NLP, multilingual AI, retrieval-augmented generation, evaluation methodology, and open-source research.

I am particularly interested in collaborations where the research question is clear, the work can be evaluated rigorously, and contributions can be documented honestly.

GitHub: "salikhussain71-code" (https://github.com/salikhussain71-code)
LinkedIn: "Salik Hussain" (https://www.linkedin.com/in/salik-hussain-7822a1388)
Kaggle: "salikhussain" (https://www.kaggle.com/salikhussain)
X: "@salikhussain71" (https://x.com/salikhussain71)
Portfolio: "salik.dev" (https://salik.dev)

---

<div align="center"><img src="https://capsule-render.vercel.app/api?type=waving&color=0:101827,50:164e63,100:0891b2&height=120&section=footer" width="100%" alt="Profile footer"/>Learn the foundations. Test the evidence. Build useful systems. Publish honest research.

Last updated: October 2026

</div>
