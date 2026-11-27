### Claudio Demaria

Clinical NLP researcher in the Neuroinformatics Unit of IRCCS Fatebenefratelli (Brescia, Italy). I build LLM pipelines for clinical documents and ML models for neuroimaging, mostly on self-hosted models. Before this I did robotics: MSc in Robotics Engineering in Genoa, with a thesis on EMG/IMU sensor fusion for prosthesis control at the Center for Bionics and Pain Research in Gothenburg.

What I work on:

- LLM pipelines on vLLM: OCR and extraction from medical documents, RAG, tool calling, evaluation against annotated data
- neuroimaging ML: ViT models for modality classification and automated quality control
- robotics: ROS2, sensor fusion, LiDAR and GNSS/RTK localization for a field rover

| Project | What it is | Stack |
|---|---|---|
| [Sensor fusion for prosthesis control](https://github.com/claudioDema99/SensorFusion_and_ML_NeuroProsthesisControl) | MSc thesis. IMU orientation features for EMG grasp recognition: 88.4% offline accuracy vs 23.9% with EMG only (15 participants) | PyTorch, ROS2 |
| [Open-weight LLMs for brain MRI report classification](https://github.com/claudioDema99/brain-mri-report-llm) | First-author paper, Academic Radiology 2026 ([DOI](https://doi.org/10.1016/j.acra.2026.09.053) · [PubMed](https://pubmed.ncbi.nlm.nih.gov/42875268/)). Four open-weight models, prompting vs QLoRA fine-tuning, on Italian reports | vLLM, QLoRA |
| [ctgov-extract](https://github.com/claudioDema99/ctgov-extract) | Turns a ClinicalTrials.gov record into structured data: eligibility text split into atomic criteria, each with a quote checked against the source, or extraction with your own YAML schema. CLI, web UI, evaluation harness, works with any OpenAI-compatible model | Python, FastAPI, vLLM |
| [Movie Language Helper](https://github.com/claudioDema99/movie-language-helper) | Web app that turns a subtitle file into a ranked study list of the idioms, phrasal verbs and slang in a chosen scene. LLM output is schema-validated and must quote the exact line it cites. Offline demo mode, 100% backend test coverage | Python, FastAPI, React, TypeScript |
| [R.O.M.A.](https://roma-rover.netlify.app/) | Low-cost multipurpose rover for agricultural and field work: navigation, localization, area coverage | ROS2, LiDAR, GNSS/RTK |

Also in progress, without public code:

- Vision Transformers for neuroimaging modality classification (first-author manuscript, under review)
- LLM-assisted pre-screening of patients for clinical trials, an institutional project ([demo](https://drive.google.com/file/d/1LWvUdfk-4lSVVGD-VMxJHkACWfC-XFMA/view?usp=sharing))

University projects (ROS/ROS2, C, PDDL planning) are collected in [robotics_projects](https://github.com/claudioDema99/robotics_projects).

[Google Scholar](https://scholar.google.com/citations?user=Z2cegQ8AAAAJ) · [ORCID](https://orcid.org/0009-0003-8006-3078) · [LinkedIn](https://www.linkedin.com/in/claudio-demaria/)
