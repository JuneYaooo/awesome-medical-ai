# Awesome Medical AI 🏥🤖🌍

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--03--22-blue.svg)](#)

> 🔧 **Looking for AI Agent Skills & MCP servers?** See [awesome-medical-ai-skills](https://github.com/JuneYaooo/awesome-medical-ai-skills) — Skills you can install directly into Claude Code, Cursor, OpenClaw, etc.

> 🇨🇳 **国内版** See [awesome-medical-ai-cn](https://github.com/JuneYaooo/awesome-medical-ai-cn) — 国内医疗 AI 项目合集

> A curated list of open-source **medical & healthcare AI projects** — LLMs, imaging systems, multi-agent frameworks, clinical software, and research tools.

---

## Table of Contents

- [Medical LLMs & Foundation Models](#medical-llms--foundation-models)
- [Medical Imaging & Radiology](#medical-imaging--radiology)
- [Multi-Agent Medical Systems](#multi-agent-medical-systems)
- [Clinical Software & EHR](#clinical-software--ehr)
- [Research & Paper Collections](#research--paper-collections)
- [Related Resources](#related-resources)

---

## Medical LLMs & Foundation Models

> Large language models fine-tuned or designed for medical/healthcare domains.

| Project | Stars | Team | Description |
|---------|-------|------|-------------|
| [HuatuoGPT](https://github.com/FreedomIntelligence/HuatuoGPT) | ![](https://img.shields.io/github/stars/FreedomIntelligence/HuatuoGPT?style=flat-square) | CUHK-SZ | Chinese medical LLM for clinical dialogue and medical Q&A. |
| [HuatuoGPT-o1](https://github.com/FreedomIntelligence/HuatuoGPT-o1) | ![](https://img.shields.io/github/stars/FreedomIntelligence/HuatuoGPT-o1?style=flat-square) | CUHK-SZ | Medical complex reasoning with o1-style thinking. |
| [DISC-MedLLM](https://github.com/FudanDISC/DISC-MedLLM) | ![](https://img.shields.io/github/stars/FudanDISC/DISC-MedLLM?style=flat-square) | Fudan DISC | Medical dialogue LLM: smart consultation, medical Q&A, clinical record structuring. |
| [Awesome-LLM-Healthcare](https://github.com/mingze-yuan/Awesome-LLM-Healthcare) | ![](https://img.shields.io/github/stars/mingze-yuan/Awesome-LLM-Healthcare?style=flat-square) | — | Comprehensive curated paper list: LLMs in medicine. |

---

## Medical Imaging & Radiology

> AI systems for medical image analysis, radiology, and pathology.

| Project | Stars | Grade | Description |
|---------|-------|-------|-------------|
| [MedRAX](https://github.com/bowang-lab/MedRAX) | ![](https://img.shields.io/github/stars/bowang-lab/MedRAX?style=flat-square) | ⭐⭐⭐ A- | **ICML 2025**. First versatile AI agent for chest X-ray. Integrates CheXagent, LLaVA-Med, MedSAM, Maira-2, DenseNet-121. ChestAgentBench (2,500 queries). LangChain-based. |
| [radiology-swarm](https://github.com/The-Swarm-Corporation/radiology-swarm) | ![](https://img.shields.io/github/stars/The-Swarm-Corporation/radiology-swarm?style=flat-square) | ⭐ C | Multi-agent radiology analysis concept/demo. 6 specialized agents (Image Analysis, Diagnostician, Intervention Planner, QA, Clinical Integrator, Treatment). *(Note: conceptual — minimal implementation)* |
| [EasyLung](https://github.com/TommyZihao/EasyLung) | ![](https://img.shields.io/github/stars/TommyZihao/EasyLung?style=flat-square) | ⭐⭐ B | AI pneumonia detection from chest X-rays. Web, WeChat mini-program, and APP. |
| [liver_cancer_classify](https://github.com/wuwusky/liver_cancer_classify) | — | ⭐ C | Liver cancer imaging diagnosis (3D-Conv deep learning). |
| [Lambar_Spine_Slicer](https://github.com/Keyon-2580/Lambar_Spine_Slicer) | — | ⭐ C | Lumbar spine intelligent segmentation system. Vue+Django+3DUNet. |
| [paddle-fl-gui](https://github.com/yyyanbj/paddle-fl-gui) | — | ⭐ C | Federated learning medical imaging GUI based on PaddleFL (Baidu). |

---

## Multi-Agent Medical Systems

> Multi-agent frameworks and research systems for medical AI.

| Project | Stars | Grade | Description |
|---------|-------|-------|-------------|
| [Multi-Agent-Medical-Assistant](https://github.com/souvikmajumder26/Multi-Agent-Medical-Assistant) | ![](https://img.shields.io/github/stars/souvikmajumder26/Multi-Agent-Medical-Assistant?style=flat-square) | ⭐⭐ B | Multi-agent diagnostics and healthcare research chatbot. |
| [cyber-doctor（赛博华佗）](https://github.com/Warma10032/cyber-doctor) | ![](https://img.shields.io/github/stars/Warma10032/cyber-doctor?style=flat-square) | ⭐⭐ B | Multi-modal medical agent with knowledge graph. Local deployment, Chinese native. Disease diagnosis, medical record analysis. |
| [MedgeClaw](https://github.com/xjtulyc/MedgeClaw) | ![](https://img.shields.io/github/stars/xjtulyc/MedgeClaw?style=flat-square) | ⭐⭐ B+ | XJTU — Biomedical AI research orchestrator. Integrates 140+ K-Dense scientific skills via Claude Code + OpenClaw. Supports WhatsApp/Slack/Feishu/Discord interfaces. |
| [medgraph-ai](https://github.com/asanmateu/medgraph-ai) | — | ⭐⭐ B | Healthcare RAG with Neo4j knowledge graphs. LangChain + FastAPI. |
| [SOLVE-Med](https://github.com/PRAISELab-PicusLab/SOLVE-Med) | — | ⭐ C | Privacy-oriented multi-agent SLM for medical Q&A. Cloud-free, offline capable. |
| [Isaree-Platform](https://github.com/Isaree-ai/Isaree-Platform) | — | ⭐ C | Open-source medical-compliant AI assistant and orchestration engine. |
| [Multi_Agent_Medical_System](https://github.com/joyceannie/Multi_Agent_Medical_System) | — | ⭐ C | ICD-10 extractor, SOAP docs, medical image reports. Uses MedGemma. |
| [Prescriptly-AI](https://github.com/warshit/Prescriptly-AI) | — | ⭐ C | Autonomous agent for prescription interpretation. |
| [Doctor_Agent](https://github.com/Ho3seinTork/Doctor_Agent) | — | ⭐ C 🔴 | AI medical assistant: symptom analysis, health data management. *(Stale)* |
| [crewai-health-advisor](https://github.com/AjayKuchhadiya/crewai-health-advisor) | — | ⭐ C 🔴 | CrewAI for medical report summarization. *(Stale)* |
| [MediCARE](https://github.com/giuseppericcio/MediCARE) | — | ⭐ C 🔴 | Collaborative agents over heterogeneous medical graphs. *(Stale)* |

---

## Clinical Software & EHR

> Open-source clinical systems, EMR editors, and hospital information systems.

| Project | Stars | Description |
|---------|-------|-------------|
| [SoDiaoEditor](https://github.com/tlzzu/SoDiaoEditor) | ![](https://img.shields.io/github/stars/tlzzu/SoDiaoEditor?style=flat-square) | Generic structured document editor widely adopted as EMR editor in Chinese hospitals. |
| [HIS (ZainZhao)](https://github.com/ZainZhao/HIS) | ![](https://img.shields.io/github/stars/ZainZhao/HIS?style=flat-square) | Hospital Information System. Outpatient/pharmacy/finance/patient workstations. Spring Boot. |
| [HIS (TANGKUO)](https://github.com/TANGKUO/HIS) | ![](https://img.shields.io/github/stars/TANGKUO/HIS?style=flat-square) | Hospital Information System. Clinical, drug, finance, patient management. |
| [Cloud Medical System](https://github.com/Rain-Ricky/cloud) | ![](https://img.shields.io/github/stars/Rain-Ricky/cloud?style=flat-square) | Online appointment, telemedicine, report lookup, billing. Spring Boot + frontend/backend separation. |

---

## NLP & Text Mining

> Medical NLP models and clinical text processing.

| Project | Stars | Description |
|---------|-------|-------------|
| [Chinese-clinical-NER](https://github.com/MenglinLu/Chinese-clinical-NER) | ![](https://img.shields.io/github/stars/MenglinLu/Chinese-clinical-NER?style=flat-square) | CCKS2019 Chinese clinical NER: diseases, anatomy, imaging, lab tests, surgery, drugs (6 entity types). |

---

## Research & Paper Collections

| Resource | Stars | Description |
|----------|-------|-------------|
| [Awesome-LLM-Healthcare](https://github.com/mingze-yuan/Awesome-LLM-Healthcare) | ![](https://img.shields.io/github/stars/mingze-yuan/Awesome-LLM-Healthcare?style=flat-square) | Curated paper list: LLMs in medicine. |
| [Awesome-MCP-ZH](https://github.com/yzfly/Awesome-MCP-ZH) | ![](https://img.shields.io/github/stars/yzfly/Awesome-MCP-ZH?style=flat-square) | MCP Chinese resource collection (includes some medical MCP servers). |
| [ai-guide (鱼皮)](https://github.com/liyupi/ai-guide) | ![](https://img.shields.io/github/stars/liyupi/ai-guide?style=flat-square) | AI resource collection + tutorials. Includes OpenClaw/Claude Code guides. |

---

## Related Resources

### Sibling Repos

| Repo | Description |
|------|-------------|
| [awesome-medical-ai-skills](https://github.com/JuneYaooo/awesome-medical-ai-skills) | 🔧 AI Agent Skills & MCP servers (International Edition) |
| [awesome-medical-ai-skills-cn](https://github.com/JuneYaooo/awesome-medical-ai-skills-cn) | 🔧 AI Agent Skills & MCP 服务器（国内版） |
| [awesome-medical-ai-cn](https://github.com/JuneYaooo/awesome-medical-ai-cn) | 🇨🇳 国内医疗 AI 项目合集 |

### Standards & Protocols

- [HL7 FHIR](https://www.hl7.org/fhir/) — Fast Healthcare Interoperability Resources
- [DICOM](https://www.dicomstandard.org/) — Digital Imaging and Communications in Medicine
- [OMOP CDM](https://ohdsi.github.io/CommonDataModel/) — Observational Medical Outcomes Partnership Common Data Model

---

## ⚠️ Disclaimer

> The projects listed here are for **informational and research purposes only**. They are NOT validated clinical tools and should NOT be used for actual medical diagnosis or treatment decisions. Always consult qualified healthcare professionals for medical advice.

---

## Contributing

We welcome contributions! Please submit a PR with the following format:

```markdown
| [Project Name](link) | Stars | Grade | One-line description |
```

### 💡 Used a Great Medical AI Project? Recommend It!

If you've used a medical AI project and found it genuinely useful, [open an Issue](../../issues/new?title=Recommend:+PROJECT_NAME) to recommend it!

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

This list is released under [CC0 1.0 Universal](LICENSE).
