# Jitesh Nagaraj Jalla
### AI / ML Engineer · Computer Vision · NLP · Retrieval and Evaluation

I build Python-based AI applications and investigate how to make model outputs measurable, grounded and useful.

**2 years 9 months of industry AI engineering experience** at Maleotech Solutions, Bengaluru, followed by an **MSc in Artificial Intelligence at IU International University** — completed **5 October 2026**, 120 ECTS, overall grade **2.3 (Good)**.

My work spans manufacturing defect inspection, business-system chatbot integrations and document processing. My master's thesis combines **3D MRI segmentation, TinyLlama adaptation with LoRA, and training-only FAISS retrieval** for structured brain-tumor report generation.

[LinkedIn](https://www.linkedin.com/in/jitesh-nagaraj-jalla-409a0813b/) · [Thesis code and results](https://github.com/JiteshNani/thesis_project_SUBMISSION)

## Start here

| Project | Engineering focus | Evidence to review |
| --- | --- | --- |
| **[Grounded Brain MRI Reporting](https://github.com/JiteshNani/thesis_project_SUBMISSION)** | PyTorch/MONAI segmentation, PEFT/LoRA, structured findings and FAISS retrieval | 368 paired cases; explicit train/validation/test splits; saved metrics and reproduction instructions |
| **[Evidence Desk](https://github.com/JiteshNani/evidence-desk)** | TF-IDF + BM25 rank fusion, exact quotations, abstention and FastAPI | Runnable local demo, retrieval comparison, regression tests and documented failure case |
| **[Vision Inspection Lab](https://github.com/JiteshNani/vision-inspection-lab)** | Normal-only anomaly detection and pixel localization | Synthetic data generator, separate test seeds, AUROC/IoU and false-positive reporting |
| **[ModelOps Watch](https://github.com/JiteshNani/modelops-watch)** | Reproducible training, JSON inference artifacts and feature-drift diagnostics | Inference parity checks, artifact fingerprints, API validation and PSI limitations |

**Project context:** the thesis is academic research, not a clinically validated system. The three October 2026 portfolio projects are AI-assisted learning prototypes with local tests and evaluation; they are separate from paid industry experience. Their results are specific to the documented small or synthetic datasets.

## Industry experience

**AI Research Engineer · Maleotech Solutions Pvt Ltd · Bengaluru**  
October 2020 – June 2023 · Earlier internship: February – September 2020

- **Visual inspection:** trained ResNet-50, VGG-16 and VGG-19 models for packaging-roll defect detection/classification and deployed the solution on a local computer.
- **NLP and integrations:** built IntelliConduit, a Python/NLTK Slack chatbot connected to Jira and Salesforce REST APIs, using tag-pattern-response training data.
- **Document workflows:** developed a Django/MySQL application extracting bill-of-materials tables from PDFs with Tabula, with authentication, uploads, filtered search and CSV export.
- **Application delivery:** deployed Django applications on Windows Server and automated Jira/Salesforce reporting in Python.

## Technical toolkit

| Area | Technologies used |
| --- | --- |
| Deep learning and vision | Python, PyTorch, MONAI, OpenCV, CNN classification and segmentation |
| NLP and language models | NLTK, Hugging Face Transformers, PEFT/LoRA, TinyLlama, Sentence Transformers, FAISS |
| ML and data | scikit-learn, XGBoost, Pandas, NumPy, MySQL |
| Applications and integration | Django, Flask, REST APIs, Tabula, Slack/Jira/Salesforce integrations |
| Portfolio engineering | FastAPI, pytest, retrieval evaluation, model artifact checks and drift diagnostics |

## Research approach

I focus on questions that matter beyond a model score:
- Is retrieval restricted to the training data?
- Does the comparison include a meaningful baseline?
- Which classes or segmentation regions underperform?
- Can an answer be traced to its evidence, and when should the system abstain?
- Can another person reproduce the evaluation and inspect its limitations?

For example, my thesis reports structured-slot micro accuracy **0.9107** against a majority baseline **0.7536**, alongside informative-slot macro balanced accuracy **0.6881**. Whole-tumor Dice is **0.8411**, while tumor-core and enhancing-tumor results are lower. The [repository](https://github.com/JiteshNani/thesis_project_SUBMISSION#dataset-and-evaluation) gives the complete results and boundaries.

## Opportunities

Seeking **AI/ML Engineer, Applied AI Engineer, Computer Vision Engineer, NLP Engineer and Research Engineer** roles, prioritizing **Bengaluru and India remote**.

Currently based in Berlin; available for remote interviews. Targeting a **mid-December 2026** Bengaluru start, subject to notice and relocation. Open to suitable Germany opportunities; a German full-time start depends on the required work authorization.

English C1 · German A1

*Reproducible experiments. Useful applications. Clear evidence.*
