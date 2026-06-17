# Xianan Li / 李夏楠

<img src="profile.jpg" alt="Xianan Li" width="320" align="right" style="border-radius: 14px; margin-left: 24px; margin-bottom: 12px;" />

M.S. student in Computer Technology at Beijing Jiaotong University  
Focus: **Large Language Models · Agent Systems · Data Intelligence · Medical AI**

[GitHub](https://github.com/lxn-maker) · [Email](mailto:xiananli@bjtu.edu.cn)

---

## About Me

I am a master's student in Computer Technology at Beijing Jiaotong University.  
My interests focus on large language models, agent systems, medical AI, data intelligence, and AI engineering for real-world business scenarios.

I have worked on projects involving medical LLM fine-tuning, multi-agent clinical decision support, table agents for complex spreadsheets, drug repurposing with graph contrastive learning, and clinical risk prediction.

I am especially interested in building AI systems that are not only accurate, but also **stable, traceable, evaluable, and safe for real-world deployment**.

---

## Featured Projects

### DeepRepurpose: LLM-Enhanced Drug Repurposing Platform

DeepRepurpose is a clinical effectiveness-aware drug repurposing platform based on LLM-enhanced graph contrastive learning.

The project integrates biomedical semantic representations from large language models, disease-drug graph structural learning, and effectiveness-aware ranking learning to identify potential drug-disease associations.

- Proposed an LLM-enhanced graph contrastive learning framework for drug repurposing
- Integrated drug and disease textual semantics with heterogeneous graph structural representations
- Introduced effectiveness-aware ranking learning for candidate drug prioritization
- Identified **909,323 high-confidence drug-disease associations**
- Covered **1,944 diseases** and **23,402 candidate drugs**
- Developed a public drug repurposing platform for browsing known and predicted drug-disease associations
- Supported bidirectional search from disease to candidate drugs and from drug to candidate diseases

Links:

- Platform: [DeepRepurpose Web Platform](http://dr.symmap.org)
- Code: [DeepRepurpose GitHub Repository](https://github.com/2020MEAI/DeepRepurpose)
- Paper: *DeepRepurpose: A Clinical Effectiveness-Aware Drug Repurposing Platform via LLM-Enhanced Graph Contrastive Learning*

---

### TableClaw: Table Agent for Complex Spreadsheets

TableClaw is a table agent system designed for complex Excel and industrial spreadsheet analysis.

Instead of asking an LLM to directly read and calculate from spreadsheets, TableClaw combines agent planning with deterministic table tools, schema inspection, domain knowledge, memory, and evaluation traces.

- Built an Agent Loop for natural language spreadsheet analysis
- Designed table retrieval, schema inspection, column locating, ranking, filtering, matrix extraction, and time-series tools
- Used Domain Pack to manage business terminology, indicator aliases, cohorts, and ranking policies
- Added trace and evaluation harness for error attribution and regression testing
- Improved reliability by separating LLM planning from deterministic table computation
- Focused on real-world spreadsheet challenges such as multi-sheet workbooks, merged cells, multi-row headers, horizontal months, percentage normalization, and summary-row filtering

Links:

- Code: [TableAgent Repository](https://github.com/Cutesxy/TableAgent)

---

### Disease-Specific Medical LLM and Multi-Agent Clinical Decision Support

Industry internship project in collaboration with a clinical partner from Peking Union Medical College Hospital.

Due to company confidentiality and medical data privacy requirements, the source code, datasets, and internal documents are not publicly available.

The project focused on building a disease-specific medical LLM and a multi-agent clinical decision support workflow for diagnosis and treatment assistance.

- Designed a Label-guided CoT data distillation pipeline for structured medical reasoning data construction
- Fine-tuned Qwen3-14B with full-parameter supervised fine-tuning for disease-specific medical reasoning
- Designed Assistant-only Loss Mask to improve supervision on model-generated reasoning and answers
- Built a LangGraph-based multi-agent workflow covering case analysis, diagnosis suggestion, test planning, treatment draft, and safety checking
- Integrated RAG-style medical knowledge retrieval, patient memory, and clinical safety rules for safer decision support
- Designed safety control mechanisms for scenarios such as allergy risk, drug conflict, contraindication, and high-risk clinical alerts
- Produced a comprehensive **100+ page technical documentation package** covering data construction, model training, evaluation, agent workflow design, and safety control mechanisms

Note: Code, datasets, and internal documents are not publicly available due to company confidentiality and medical privacy requirements.

---

### Dynamic Pneumonia Survival Risk Prediction

A clinical risk prediction project for dynamically identifying high-risk pneumonia patients.

- Integrated heterogeneous clinical data from patient records
- Built temporal inputs using sliding time windows
- Applied Lasso and AUC-SHAP for feature selection
- Designed a multi-head self-attention model for dynamic risk prediction
- Used Mask and Focal Loss to improve high-risk patient identification under imbalanced data settings
- Completed the full modeling and evaluation workflow as project leader

---

## Research

### Drug Repurposing with LLM-Enhanced Graph Contrastive Learning

- Built biomedical entity representations by combining textual semantics and graph structural information
- Applied graph contrastive learning to improve drug-disease association modeling
- Designed ranking-based learning for clinical effectiveness-aware drug prioritization
- Contributed to methodology design, software implementation, validation, visualization, formal analysis, and data curation

### Knowledge Graph Completion under Few-Shot Uncertainty

- Participated in research on few-shot uncertain knowledge graph completion
- Explored metric learning and meta-relation-aware representation methods
- Related paper accepted/submitted to high-level academic venue

---

## Experience

### China Telecom Artificial Intelligence Research Institute  
Large Model Intern

- Participated in AI coding data production and acceptance standard design
- Contributed to data delivery specifications and quality control workflows
- Established multi-level validation mechanisms including testing, manual review, and deduplication
- Standardized deliverables such as code patches, interaction traces, environment configuration, and documentation
- Improved data usability and consistency for downstream model training

### Digital Health / Medical AI Internship  
Algorithm Intern

- Participated in disease-specific medical LLM development
- Worked on medical reasoning data construction, model fine-tuning, evaluation, and multi-agent workflow design
- Focused on medical CoT distillation, long-context training, RAG, safety rules, and clinical decision support

---

## Skills

### Programming

- Python
- Java
- SQL
- Git
- Linux

### Machine Learning

- XGBoost
- LightGBM
- Scikit-learn
- Feature Engineering
- Time-series Modeling
- Risk Prediction
- AUC-SHAP
- Focal Loss

### Deep Learning

- Attention Mechanism
- Graph Neural Networks
- Graph Contrastive Learning
- Multi-task Learning
- Representation Learning

### Large Language Models

- Supervised Fine-tuning
- Chain-of-Thought Distillation
- RAG
- Multi-Agent Systems
- LangGraph
- Loss Masking
- DeepSpeed ZeRO-3
- Gradient Checkpointing
- Flash Attention

### Data and AI Engineering

- Pandas
- NumPy
- MySQL
- Table Agent
- Tool Calling
- Evaluation Harness
- Trace Analysis
- Data Quality Control
- Technical Documentation

---

## Education

### Beijing Jiaotong University  
M.S. in Computer Technology  
2024 - 2027

- Recommended admission as a graduate student
- Ranked in the top 7% academically
- Huawei Scholarship
- First-class Academic Scholarship
- Outstanding Student Leader
- Outstanding Communist Party Member

### Yanshan University  
B.E. in Software Engineering  
2020 - 2024

- GPA: 3.87 / 4.5
- Ranked in the top 7%
- Multiple academic scholarships
- National Third Prize, China Collegiate Computing Contest

---

## Honors

- Huawei Scholarship
- Beijing Jiaotong University First-class Academic Scholarship
- Outstanding Communist Party Member
- Outstanding Graduate Student Cadre
- National Third Prize, China Colleg Computing Contest
- National Third Prize, National English Competition for College Students
- Provincial Third Prize, Lanqiao Cup Software and IT Contest
- Multiple academic and student leadership awards

---

## Contact

- Email: [xiananli@bjtu.edu.cn](mailto:xiananli@bjtu.edu.cn)
- GitHub: [lxn-maker](https://github.com/lxn-maker)
- Homepage: [https://lxn-maker.github.io](https://lxn-maker.github.io)
