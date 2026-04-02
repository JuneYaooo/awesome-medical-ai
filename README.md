# Awesome Medical AI 🏥🤖🌍

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--04--02-blue.svg)](#)

> 🔧 **Looking for AI Agent Skills & MCP servers?** See [awesome-medical-ai-skills](https://github.com/JuneYaooo/awesome-medical-ai-skills) — Skills you can install directly into Claude Code, Cursor, OpenClaw, etc.

> 🇨🇳 **国内版** See [awesome-medical-ai-cn](https://github.com/JuneYaooo/awesome-medical-ai-cn) — 国内医疗 AI 项目合集

> A curated list of open-source **medical & healthcare AI projects** — LLMs, imaging systems, multi-agent frameworks, clinical software, and research tools.

---

## Table of Contents

- [Medical LLMs & Foundation Models](#medical-llms--foundation-models)
- [Medical Imaging & Radiology](#medical-imaging--radiology)
- [Multi-Agent Medical Systems](#multi-agent-medical-systems)
- [Clinical Software & EHR](#clinical-software--ehr)
- [NLP & Text Mining](#nlp--text-mining)
- [Biomedical Research & Drug Discovery](#biomedical-research--drug-discovery)
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
| [ChatDoctor](https://github.com/Kent0n-Li/ChatDoctor) | ![](https://img.shields.io/github/stars/Kent0n-Li/ChatDoctor?style=flat-square) | UTSW + UIUC | Medical chat model fine-tuned on LLaMA with released healthcare dialogue data, disease-database tools, demo, and checkpoint links. |
| [Meditron](https://github.com/epfLLM/meditron) | ![](https://img.shields.io/github/stars/epfLLM/meditron?style=flat-square) | EPFL | Suite of open medical LLMs adapted from Llama-2 via continued pretraining on PubMed, guidelines, and curated medical corpora. |
| [medAlpaca](https://github.com/kbressem/medAlpaca) | ![](https://img.shields.io/github/stars/kbressem/medAlpaca?style=flat-square) | Open-source | Finetuned medical QA/dialogue LLM suite derived from Alpaca and Alpaca-LoRA, with reproducible training and inference code. |
| [NYUTron](https://github.com/nyuolab/NYUTron) | ![](https://img.shields.io/github/stars/nyuolab/NYUTron?style=flat-square) | NYU Langone | Health-system-scale language model for clinical prediction from EHR data, with synthetic data, experiment scripts, and docs. |
| [MING](https://github.com/MediaBrain-SJTU/MING) | ![](https://img.shields.io/github/stars/MediaBrain-SJTU/MING?style=flat-square) | SJTU MediaBrain | Chinese medical instruction-tuned LLM family for medical QA and multi-turn consultation. Includes MING-MOE and linked clinical-agent papers. |
| [QiZhenGPT](https://github.com/CMKRG/QiZhenGPT) | ![](https://img.shields.io/github/stars/CMKRG/QiZhenGPT?style=flat-square) | ZJU / MedCopilot | Chinese medical LLM built from a medical knowledge base and instruction data. Extended into MedCopilot and hospital workflow integrations. |
| [HuatuoGPT-II](https://github.com/FreedomIntelligence/HuatuoGPT-II) | ![](https://img.shields.io/github/stars/FreedomIntelligence/HuatuoGPT-II?style=flat-square) | CUHK-SZ | One-stage medical domain adaptation for 7B/13B/34B models with released data, evaluation code, and benchmark results. |
| [Taiyi](https://github.com/DUTIR-BioNLP/Taiyi-LLM) | ![](https://img.shields.io/github/stars/DUTIR-BioNLP/Taiyi-LLM?style=flat-square) | DUTIR-BioNLP | Bilingual biomedical LLM for diverse biomedical tasks, with open models, datasets, demo, and benchmark results. |
| [Huatuo-Llama-Med-Chinese](https://github.com/SCIR-HI/Huatuo-Llama-Med-Chinese) | ![](https://img.shields.io/github/stars/SCIR-HI/Huatuo-Llama-Med-Chinese?style=flat-square) | HIT-SCIR | Chinese medical instruction-tuned LLM family trained on medical literature, knowledge graphs, and synthetic instruction data. Releases models, training code, papers, and bilingual docs. |
| [ChatMed](https://github.com/michael-wzhu/ChatMed) | ![](https://img.shields.io/github/stars/michael-wzhu/ChatMed?style=flat-square) | Open-source | Chinese medical consultation LLM trained on 500k+ online consultation pairs with released datasets, LoRA checkpoints, and training scripts. |
| [CareGPT](https://github.com/WangRongsheng/CareGPT) | ![](https://img.shields.io/github/stars/WangRongsheng/CareGPT?style=flat-square) | Open-source | Chinese medical LLM stack with released training, evaluation, and deployment code, plus Gradio/Next demos, domain datasets, and fine-tuning workflows across LLaMA-style backbones. |
| [Sunsimiao](https://github.com/X-D-Lab/Sunsimiao) | ![](https://img.shields.io/github/stars/X-D-Lab/Sunsimiao?style=flat-square) | X-D Lab | Chinese medical LLM series with downloadable weights, demo links, QLoRA recipes, and bilingual docs for safe general medical dialogue. |
| [ShenNong-TCM-LLM](https://github.com/michael-wzhu/ShenNong-TCM-LLM) | ![](https://img.shields.io/github/stars/michael-wzhu/ShenNong-TCM-LLM?style=flat-square) | Open-source | Traditional Chinese Medicine LLM built from entity-centric self-instruct data, released code, model weights, and linked TCM knowledge graph resources. |
| [CMLM-ZhongJing](https://github.com/pariskang/CMLM-ZhongJing) | ![](https://img.shields.io/github/stars/pariskang/CMLM-ZhongJing?style=flat-square) | CMLM | TCM foundation model with 135k+ expert-guided instructions, physician evaluation, paper, weights, and Colab deployment notebook. |
| [Zhongjing](https://github.com/SupritYoung/Zhongjing) | ![](https://img.shields.io/github/stars/SupritYoung/Zhongjing?style=flat-square) | Open-source | Chinese medical LLM covering pretraining, SFT, and RLHF, with released CMtMedQA multi-turn dialogue data and AAAI 2024 paper/code. |
| [TCMLLM](https://github.com/2020MEAI/TCMLLM) | ![](https://img.shields.io/github/stars/2020MEAI/TCMLLM?style=flat-square) | 2020MEAI | TCM prescription-recommendation LLM with 68k instruction samples built from textbooks, pharmacopoeia, and real clinical records. |
| [MedChatZH](https://github.com/tyang816/MedChatZH) | ![](https://img.shields.io/github/stars/tyang816/MedChatZH?style=flat-square) | Open-source | Baichuan-7B-based Chinese medical dialogue model spanning Western + TCM consultation, with released datasets, checkpoints, and web/demo scripts. |
| [Doctor Dignity](https://github.com/llSourcell/Doctor-Dignity) | ![](https://img.shields.io/github/stars/llSourcell/Doctor-Dignity?style=flat-square) | Open-source | Offline medical dialogue LLM packaged for local web, iOS, and Android use, with training, quantization, and deployment code. |
| [Asclepius](https://github.com/starmpcc/Asclepius) | ![](https://img.shields.io/github/stars/starmpcc/Asclepius?style=flat-square) | Research | Shareable clinical LLM family trained on synthetic clinical notes, with released ACL paper, checkpoints, and note-generation data. |
| [Visual Med-Alpaca](https://github.com/cambridgeltl/visual-med-alpaca) | ![](https://img.shields.io/github/stars/cambridgeltl/visual-med-alpaca?style=flat-square) | Cambridge | Parameter-efficient biomedical multimodal foundation model that combines medical visual understanding with LLM reasoning. |
| [BiomedGPT](https://github.com/taokz/BiomedGPT) | ![](https://img.shields.io/github/stars/taokz/BiomedGPT?style=flat-square) | Research | Generalist biomedical vision-language foundation model with a Nature Medicine 2024 paper, multi-task datasets, released training code, and checkpoints up to 930M parameters. |
| [RxLM-Med-Agent](https://github.com/tokisaka23/RxLM-Med-Agent) | ![](https://img.shields.io/github/stars/tokisaka23/RxLM-Med-Agent?style=flat-square) | Open-source | Multimodal clinical diagnostic agent for lab-report interpretation with Qwen-VL fine-tuning, hierarchical RAG, deterministic medical calculations, and System 2 self-correction with traffic-light safety alignment. |
| [PMC-LLaMA](https://github.com/chaoyi-wu/PMC-LLaMA) | ![](https://img.shields.io/github/stars/chaoyi-wu/PMC-LLaMA?style=flat-square) | Research | Medical LLM training stack with domain pretraining and instruction tuning, plus released code, benchmark results, and downloadable checkpoints. |
| [GatorTron](https://github.com/uf-hobi-informatics-lab/GatorTron) | ![](https://img.shields.io/github/stars/uf-hobi-informatics-lab/GatorTron?style=flat-square) | UF HOBI | Clinical language-model pretraining and fine-tuning scripts for EHR + PubMed corpora, covering NER, relation extraction, and de-identification tasks. |
| [MedicalGPT](https://github.com/shibing624/MedicalGPT) | ![](https://img.shields.io/github/stars/shibing624/MedicalGPT?style=flat-square) | ⭐ C | MedicalGPT: Training Your Own Medical GPT Model with ChatGPT Training Pipeline. 训练医疗大模型，实现了包括增量预训练(PT)、有监督微调(SFT)、RLHF、DPO、ORPO、GRPO。 |
| [Books-Free-Books](https://github.com/lTbgykio/Books-Free-Books) | ![](https://img.shields.io/github/stars/lTbgykio/Books-Free-Books?style=flat-square) | ⭐ C | 免费书籍汇总。　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　... |
| [Traditional_Chinese_Medicine_Agent](https://github.com/releerr/Traditional_Chinese_Medicine_Agent) | ![](https://img.shields.io/github/stars/releerr/Traditional_Chinese_Medicine_Agent?style=flat-square) | ⭐ C | 私人中医智能体是一款基于 AI 的专业中医健康问诊系统，能够模拟真实中医门诊场景，进行问诊及望诊，让用户足不出户就享受私人中医专家门诊服务。 |
| [RenShu-AI](https://github.com/yanlinPeng-code/RenShu-AI) | ![](https://img.shields.io/github/stars/yanlinPeng-code/RenShu-AI?style=flat-square) | ⭐ C | 仁术AI,一个基于 FastAPI + Vue 3 + LangGraph 构建的前后端分离多智能体中医问诊系统，支持 DeepSeek（中医微调版）、TCM-LLM 等中医领域大模型，融合 Agent 动态推理与 GraphRAG 中医知识检索能力，解决中医问诊场景下**意图识别准确率低**、**结构化 / 非结构化数据割裂**、**辨证推理不严谨**等核心痛点，覆盖中医辨证、古籍查询、医... |
| [ZJU-AI-course](https://github.com/sakurarain1213/ZJU-AI-course) | ![](https://img.shields.io/github/stars/sakurarain1213/ZJU-AI-course?style=flat-square) | ⭐ C | 浙江大学软件学院-人工智能算法与系统-2025秋-智海mo平台-三个实训作业-【金融异常检测】【手写数字识别与垃圾分类】【中医辨证系统实现】-思路与代码参考仓库 |
| [agents-zhongyi](https://github.com/oficcejo/agents-zhongyi) | ![](https://img.shields.io/github/stars/oficcejo/agents-zhongyi?style=flat-square) | ⭐ C | 多智能体ai中医大师系统，模仿张仲景、张锡纯等经方大师，根据历代名医病案及现代中医医学研究，综合给出中医治疗方案，并严格审核方剂配伍，堪比一小型中医国医大师诊所 |
| [Chinese-LLaVA-Med](https://github.com/BUAADreamer/Chinese-LLaVA-Med) | ![](https://img.shields.io/github/stars/BUAADreamer/Chinese-LLaVA-Med?style=flat-square) | ⭐ C | 中文医学多模态大模型 Large Chinese Language-and-Vision Assistant for BioMedicine |
| [AI-Medical-Scribe](https://github.com/hutchpd/AI-Medical-Scribe) | ![](https://img.shields.io/github/stars/hutchpd/AI-Medical-Scribe?style=flat-square) | ⭐ C | Local-first AI medical scribe running entirely in the browser using Chrome built-in AI (no backend) |
| [fondamenta-archcode](https://github.com/talionwar/fondamenta-archcode) | ![](https://img.shields.io/github/stars/talionwar/fondamenta-archcode?style=flat-square) | ⭐ C | Zero-dependency codebase intelligence for AI agents and humans. Static analysis → structured Markdown → readable by any LLM. 8 code health agents included. |
| [MedicalRAGChatbot](https://github.com/FCHEHIDI/MedicalRAGChatbot) | ![](https://img.shields.io/github/stars/FCHEHIDI/MedicalRAGChatbot?style=flat-square) | ⭐ C | Production-ready Medical RAG Chatbot showcasing AI/ML engineering skills with local LLM integration and vector databases |
| [LLM-Nursing-Training](https://github.com/mrpanzerr/LLM-Nursing-Training) | ![](https://img.shields.io/github/stars/mrpanzerr/LLM-Nursing-Training?style=flat-square) | ⭐ C | LLM Video Avatar for training nursing students through AI-driven simulations. Progresses from text-to-text to video-to-video interactions. Adaptive scenarios powered by GPT-4o enhance clinical skil... |
| [consultation_registration_cos](https://github.com/Fankekeke/consultation_registration_cos) | ![](https://img.shields.io/github/stars/Fankekeke/consultation_registration_cos?style=flat-square) | ⭐ C | 智慧医疗助手：基于 LLM（大语言模型）的 AI 预诊与在线挂号平台。集成 RAG（检索增强生成）医疗知识库，支持多科室智能分诊与挂号流转。大模型辅助问诊 + 自动化挂号分拨，实时预约排班挂号管理（SpringBoot + Vue 全栈） |

---

## Medical Imaging & Radiology

> AI systems for medical image analysis, radiology, and pathology.

| Project | Stars | Grade | Description |
|---------|-------|-------|-------------|
| [MedRAX](https://github.com/bowang-lab/MedRAX) | ![](https://img.shields.io/github/stars/bowang-lab/MedRAX?style=flat-square) | ⭐⭐⭐ A- | **ICML 2025**. First versatile AI agent for chest X-ray. Integrates CheXagent, LLaVA-Med, MedSAM, Maira-2, DenseNet-121. ChestAgentBench (2,500 queries). LangChain-based. |
| [LLaVA-Med](https://github.com/microsoft/LLaVA-Med) | ![](https://img.shields.io/github/stars/microsoft/LLaVA-Med?style=flat-square) | ⭐⭐⭐ A- | Biomedical vision-language assistant with GPT-4-style instruction tuning and released code/data for multimodal medical QA. |
| [RadFM](https://github.com/chaoyi-wu/RadFM) | ![](https://img.shields.io/github/stars/chaoyi-wu/RadFM?style=flat-square) | ⭐⭐ B | Generalist radiology foundation model leveraging 2D/3D medical data, with checkpoints, demos, and training/inference code. |
| [XRayGPT](https://github.com/mbzuai-oryx/XRayGPT) | ![](https://img.shields.io/github/stars/mbzuai-oryx/XRayGPT?style=flat-square) | ⭐⭐ B | Chest radiograph summarization model with demo, checkpoints, and a medical VLM training pipeline. |
| [ChatCAD](https://github.com/zhaozh10/ChatCAD) | ![](https://img.shields.io/github/stars/zhaozh10/ChatCAD?style=flat-square) | ⭐⭐ B | Interactive computer-aided diagnosis system that combines LLM dialogue with radiology and image-analysis workflows. |
| [XrayGLM](https://github.com/WangRongsheng/XrayGLM) | ![](https://img.shields.io/github/stars/WangRongsheng/XrayGLM?style=flat-square) | ⭐⭐ B- | Chinese chest X-ray multimodal model with translated report datasets, fine-tuning guides, and released academic weights. |
| [ImpressionGPT](https://github.com/MoMarky/ImpressionGPT) | ![](https://img.shields.io/github/stars/MoMarky/ImpressionGPT?style=flat-square) | ⭐ C+ | Iterative ChatGPT-based radiology report summarization framework with released code, paper link, and benchmark-oriented workflow for impression generation. |
| [Med-Flamingo](https://github.com/snap-stanford/med-flamingo) | ![](https://img.shields.io/github/stars/snap-stanford/med-flamingo?style=flat-square) | ⭐⭐ B | Medical vision-language model from Stanford with released paper code, setup instructions, and demo scripts for multimodal medical QA. |
| [SkinGPT-4](https://github.com/JoshuaChou2018/SkinGPT-4) | ![](https://img.shields.io/github/stars/JoshuaChou2018/SkinGPT-4?style=flat-square) | ⭐⭐ B- | Dermatology multimodal LLM with Nature Communications paper, training/eval code, and published test weights for skin-disease QA. |
| [TorchIO](https://github.com/TorchIO-project/torchio) | ![](https://img.shields.io/github/stars/TorchIO-project/torchio?style=flat-square) | ⭐⭐⭐ A- | Mature PyTorch toolkit for medical image preprocessing, augmentation, patch sampling, and reconstruction, with extensive docs, tutorials, and tests. |
| [TIA Toolbox](https://github.com/TissueImageAnalytics/tiatoolbox) | ![](https://img.shields.io/github/stars/TissueImageAnalytics/tiatoolbox?style=flat-square) | ⭐⭐⭐ A- | Production-grade computational pathology toolbox with whole-slide IO, patch extraction, stain normalization, pretrained models, benchmarks, and docs. |
| [PathML](https://github.com/Dana-Farber-AIOS/pathml) | ![](https://img.shields.io/github/stars/Dana-Farber-AIOS/pathml?style=flat-square) | ⭐⭐ B+ | Digital pathology toolkit with Docker images, notebooks, docs, and AI-assisted workflow examples for large whole-slide image analysis. |
| [MoPaDi](https://github.com/KatherLab/mopadi) | ![](https://img.shields.io/github/stars/KatherLab/mopadi?style=flat-square) | ⭐⭐ B | Counterfactual diffusion framework for computational pathology explainability, with training scripts, notebooks, Hugging Face model releases, and pathology workflows spanning TCGA and colorectal/breast/pancancer cohorts. |
| [Kaapana](https://github.com/kaapana/kaapana) | ![](https://img.shields.io/github/stars/kaapana/kaapana?style=flat-square) | ⭐⭐ B+ | Kubernetes-native platform for medical imaging and data-analysis workflows with PACS/DICOM integration, federated learning support, extension-based deployment, and strong operational docs. |
| [PathAsst](https://github.com/superjamessyx/Generative-Foundation-AI-Assistant-for-Pathology) | ![](https://img.shields.io/github/stars/superjamessyx/Generative-Foundation-AI-Assistant-for-Pathology?style=flat-square) | ⭐⭐ B- | Pathology multimodal assistant with 207K image-text pairs, a PathCLIP encoder, eight pathology sub-models, and released code for data construction, training, and demo workflows. |
| [LitePath](https://github.com/caiyu6666/LitePath) | ![](https://img.shields.io/github/stars/caiyu6666/LitePath?style=flat-square) | ⭐⭐ B | Efficient computational pathology framework with a distilled LiteFM backbone and adaptive patch selector for whole-slide tasks. Includes training/inference code, deployment assets, and released checkpoints/examples. |
| [MAMMOTH](https://github.com/mahmoodlab/MAMMOTH) | ![](https://img.shields.io/github/stars/mahmoodlab/MAMMOTH?style=flat-square) | ⭐⭐ B- | Computational pathology module from Mahmood Lab that replaces the MIL patch projection layer with a mixture-of-mini-experts design. Ships as a Python package with examples, PyPI release metadata, and paper-backed implementation details. |
| [MOOZY](https://github.com/AtlasAnalyticsLab/MOOZY) | ![](https://img.shields.io/github/stars/AtlasAnalyticsLab/MOOZY?style=flat-square) | ⭐ C+ | Patient-first computational pathology foundation model trained on 77K+ public whole-slide images, with released configs, notebooks, checkpoints, and reproducible pathology workflows. |
| [MedSegAgent](https://github.com/uni-medical/MedSegAgent) | ![](https://img.shields.io/github/stars/uni-medical/MedSegAgent?style=flat-square) | ⭐ C+ | Multi-agent medical image segmentation system that routes natural-language requests across 23 dataset-specific models and 343 targets spanning CT, MRI, PET/CT, and ultrasound. |
| [radiology-swarm](https://github.com/The-Swarm-Corporation/radiology-swarm) | ![](https://img.shields.io/github/stars/The-Swarm-Corporation/radiology-swarm?style=flat-square) | ⭐ C | Multi-agent radiology analysis concept/demo. 6 specialized agents (Image Analysis, Diagnostician, Intervention Planner, QA, Clinical Integrator, Treatment). *(Note: conceptual — minimal implementation)* |
| [EasyLung](https://github.com/TommyZihao/EasyLung) | ![](https://img.shields.io/github/stars/TommyZihao/EasyLung?style=flat-square) | ⭐⭐ B | AI pneumonia detection from chest X-rays. Web, WeChat mini-program, and APP. |
| [liver_cancer_classify](https://github.com/wuwusky/liver_cancer_classify) | — | ⭐ C | Liver cancer imaging diagnosis (3D-Conv deep learning). |
| [Lambar_Spine_Slicer](https://github.com/Keyon-2580/Lambar_Spine_Slicer) | — | ⭐ C | Lumbar spine intelligent segmentation system. Vue+Django+3DUNet. |
| [paddle-fl-gui](https://github.com/yyyanbj/paddle-fl-gui) | — | ⭐ C | Federated learning medical imaging GUI based on PaddleFL (Baidu). |
| [dicom-agent](https://github.com/ChristianHinge/dicom-agent) | ![](https://img.shields.io/github/stars/ChristianHinge/dicom-agent?style=flat-square) | ⭐ C | A fully agentic demo for a medical imaging assistant that uses dicom-mcp |
| [autoresearch-medimage](https://github.com/mattlungrenmd/autoresearch-medimage) | ![](https://img.shields.io/github/stars/mattlungrenmd/autoresearch-medimage?style=flat-square) | ⭐ C | Autonomous medical imaging AI research — bring any dataset, the agent runs experiments automatically. Built on karpathy/autoresearch. |
| [Wilhelm](https://github.com/ameyarad/Wilhelm) | ![](https://img.shields.io/github/stars/ameyarad/Wilhelm?style=flat-square) | ⭐ C | Free and open source medical imaging reporting AI agent |
| [AFM_kidney_cells](https://github.com/hrlblab/AFM_kidney_cells) | ![](https://img.shields.io/github/stars/hrlblab/AFM_kidney_cells?style=flat-square) | ⭐ C | AI foundation models for kidney pathology cells |
| [genbio-pathfm](https://github.com/genbio-ai/genbio-pathfm) | ![](https://img.shields.io/github/stars/genbio-ai/genbio-pathfm?style=flat-square) | ⭐ C | GenBio-PathFM is a histopathology foundation model from GenBio AI. |
| [kidney-fibrosis-grader](https://github.com/MarkBarsoumMarkarian/kidney-fibrosis-grader) | ![](https://img.shields.io/github/stars/MarkBarsoumMarkarian/kidney-fibrosis-grader?style=flat-square) | ⭐ C | ResNet-FPN deep learning classifier for kidney biopsy fibrosis grading (4 classes) with AI-generated pathology reports via LLM — Streamlit app |
| [Enso-Atlas](https://github.com/Hilo-Hilo/Enso-Atlas) | ![](https://img.shields.io/github/stars/Hilo-Hilo/Enso-Atlas?style=flat-square) | ⭐ C | Universal on-premise pathology AI platform: plug in any foundation model, dataset, or cancer task hassle free. |
| [CPMP](https://github.com/lyotvincent/CPMP) | ![](https://img.shields.io/github/stars/lyotvincent/CPMP?style=flat-square) | ⭐ C | CPMP: AI-driven computational pathology for recurrence risk assessment in early-stage breast cancer |
| [medical-ai-assistant](https://github.com/upmikodev/medical-ai-assistant) | ![](https://img.shields.io/github/stars/upmikodev/medical-ai-assistant?style=flat-square) | ⭐ C | A multi-agent AI platform for medical imaging diagnostics—integrating tumor classification, segmentation, RAG-powered patient data retrieval, and automated report generation via a FastAPI backend a... |
| [medical-imaging-ai-pneumonia-detector](https://github.com/LuthandoCandlovu/medical-imaging-ai-pneumonia-detector) | ![](https://img.shields.io/github/stars/LuthandoCandlovu/medical-imaging-ai-pneumonia-detector?style=flat-square) | ⭐ C | Deep learning system for pneumonia detection from chest X‑rays with explainable AI heatmaps (Grad‑CAM). Built with TensorFlow and Streamlit. Achieves ~90% accuracy. |
| [med-gemma-critical-imaging-copilot](https://github.com/DRZ-hang/med-gemma-critical-imaging-copilot) | ![](https://img.shields.io/github/stars/DRZ-hang/med-gemma-critical-imaging-copilot?style=flat-square) | ⭐ C+ | Physician-gated critical imaging workflow that turns MedGemma findings into emergency, outpatient, and radiology coordination actions. 8 agents, local mock mode, web dashboard, and tests. |

---

## Multi-Agent Medical Systems

> Multi-agent frameworks and research systems for medical AI.

| Project | Stars | Grade | Description |
|---------|-------|-------|-------------|
| [Multi-Agent-Medical-Assistant](https://github.com/souvikmajumder26/Multi-Agent-Medical-Assistant) | ![](https://img.shields.io/github/stars/souvikmajumder26/Multi-Agent-Medical-Assistant?style=flat-square) | ⭐⭐ B | Multi-agent diagnostics and healthcare research chatbot. |
| [MedSci Agent](https://github.com/omar-A-hassan/medsci-agent) | ![](https://img.shields.io/github/stars/omar-A-hassan/medsci-agent?style=flat-square) | ⭐⭐ B | Open-source biomedical research agent with 28 MCP tools for literature search, omics workflows, drug ADMET prediction, protein structure search, document acquisition, and medical image interpretation. Local MedGemma/TxGemma support via Ollama. |
| [Clinical Trial Matcher](https://github.com/anumsagheer01/clinical-trial-matcher) | ![](https://img.shields.io/github/stars/anumsagheer01/clinical-trial-matcher?style=flat-square) | ⭐⭐ B- | Clinical-trial matching platform with 3 MCP servers, hybrid retrieval across 92K+ trials, openFDA drug-safety checks, a Streamlit demo, and Docker/Kubernetes deployment assets. |
| [MedAgents](https://github.com/gersteinlab/MedAgents) | ![](https://img.shields.io/github/stars/gersteinlab/MedAgents?style=flat-square) | ⭐⭐ B | ACL 2024 multi-disciplinary collaboration framework where specialized LLM agents jointly reason over medical questions in staged debate. |
| [MMedAgent](https://github.com/Wangyixinxin/MMedAgent) | ![](https://img.shields.io/github/stars/Wangyixinxin/MMedAgent?style=flat-square) | ⭐ C | Learning to Use Medical Tools with Multi-modal Agent |
| [Meissa](https://github.com/Schuture/Meissa) | ![](https://img.shields.io/github/stars/Schuture/Meissa?style=flat-square) | ⭐ C | Meissa is a multi-modal medical agent, built on trajectory-based agentic behavior distillation framework. |
| [PortOS](https://github.com/atomantic/PortOS) | ![](https://img.shields.io/github/stars/atomantic/PortOS?style=flat-square) | ⭐ C | Self-hosted dev machine OS — app management, AI agent orchestration, digital twin, second brain, and health tracking from a single dashboard over Tailscale |
| [ghagga](https://github.com/JNZader/ghagga) | ![](https://img.shields.io/github/stars/JNZader/ghagga?style=flat-square) | ⭐ C | AI-powered multi-agent code review — SaaS, GitHub Action & CLI. 12+ static analysis tools (Semgrep, Trivy, Gitleaks, PMD, Biome, Ruff...), health scoring, SARIF export. |
| [MediCareAI](https://github.com/HougeLangley/MediCareAI) | ![](https://img.shields.io/github/stars/HougeLangley/MediCareAI?style=flat-square) | ⭐ C | MediCareAI 是一个基于人工智能的智能疾病管理系统，采用现代化的全栈架构设计，整合了医疗指南、AI 智能诊断、文档处理和邮件通知等功能。项目已完成主要功能开发阶段，具备生产环境部署能力。 |
| [chronic-care-ai-platform](https://github.com/ZixinYan/chronic-care-ai-platform) | ![](https://img.shields.io/github/stars/ZixinYan/chronic-care-ai-platform?style=flat-square) | ⭐ C | SpringCloud微服务项目，针对中老年慢性病的智能医疗服务项目【开发ing】 |
| [dolphin_agent](https://github.com/peanut2001/dolphin_agent) | ![](https://img.shields.io/github/stars/peanut2001/dolphin_agent?style=flat-square) | ⭐ C | 基于 AI 的多智能体医疗辅助系统，集成 RAG 知识检索、医学影像分析（胸片/皮肤病变）、网络搜索、语音交互与人机协同验证。技术栈：FastAPI + LangGraph + Qdrant |
| [med_model_learning](https://github.com/Chacha-Bing/med_model_learning) | ![](https://img.shields.io/github/stars/Chacha-Bing/med_model_learning?style=flat-square) | ⭐ C | 这是一个用于个人学习的项目，此项目基于 Transformers 从0到1训练一个医疗大模型。 |
| [EAViz](https://github.com/X-Augenstern/EAViz) | ![](https://img.shields.io/github/stars/X-Augenstern/EAViz?style=flat-square) | ⭐ C | EAViz（离线版，在线版参见EAViz-OL）是一款AI赋能的临床级癫痫分析工具，聚焦“算法易用性+临床实用性”，整合脑电/视频多模态数据与深度学习模型，构建“数据输入-模型推理-可视化输出”全链路闭环，打通科研算法与临床用户的使用壁垒，为癫痫诊断、治疗决策及科研工作提供高效自动化支持。（https://doi.org/10.1007/s11227-025-07494-2） |
| [EEG-Epilepsy-Prediction](https://github.com/IiVvYy-Nino/EEG-Epilepsy-Prediction) | ![](https://img.shields.io/github/stars/IiVvYy-Nino/EEG-Epilepsy-Prediction?style=flat-square) | ⭐ C | EEG-Epilepsy-Prediction 是一个面向多通道脑电（EEG）数据的癫痫发作检测与分型框架，集成了频谱/时域特征提取、BiLSTM 帧级分类与精细后处理（平滑、阈值判决、确认窗、冷却合并），聚焦事件级检测精度与误报控制（FA/h 限制）。项目支持 特征缓存与标签自动构建，并提供 阈值网格搜索+写回配置，实现端到端训练与推理。创新点包括：引入 Mixup/SpecAugment... |
| [AI-MEDICAL-ASSISANT](https://github.com/vibhudeshg/AI-MEDICAL-ASSISANT) | ![](https://img.shields.io/github/stars/vibhudeshg/AI-MEDICAL-ASSISANT?style=flat-square) | ⭐ C | *(no description)* |
| [MedRAG_APP](https://github.com/BHANJATANMAYA/MedRAG_APP) | ![](https://img.shields.io/github/stars/BHANJATANMAYA/MedRAG_APP?style=flat-square) | ⭐ C | AI-powered medical assistant built with Flutter and a RAG-based backend to deliver evidence-based health insights. |
| [medcare-ai](https://github.com/24pwai0032-gif/medcare-ai) | ![](https://img.shields.io/github/stars/24pwai0032-gif/medcare-ai?style=flat-square) | ⭐ C | Pakistan's First AI Medical  Platform — 9 modules, LLaVA-Med, FastAPI, React, PostgreSQL |
| [Medisense-ai](https://github.com/Anweshapplese/Medisense-ai) | ![](https://img.shields.io/github/stars/Anweshapplese/Medisense-ai?style=flat-square) | ⭐ C | Medisense AI transforms complex medical reports into clear, easy-to-understand explanations. Upload your PDF and receive structured, personalized insights in seconds. |
| [china-dictatorship](https://github.com/cirosantilli/china-dictatorship) | ![](https://img.shields.io/github/stars/cirosantilli/china-dictatorship?style=flat-square) | ⭐ C | 反中共政治宣传库。Anti Chinese government propaganda. 住在中国真名用户的网友请别给星星，不然你要被警察请喝茶。常见问答集，新闻集和饭店和音乐建议。卐习万岁卐。冠状病毒审查郝海东新疆改造中心六四事件法轮功 996.ICU709大抓捕巴拿马文件邓家贵低端人口西藏骚乱。Friends who live in China and have real name on... |
| [cihna-dictattorshrip-8](https://github.com/mRFWq7LwNPZjaVv5v6eo/cihna-dictattorshrip-8) | ![](https://img.shields.io/github/stars/mRFWq7LwNPZjaVv5v6eo/cihna-dictattorshrip-8?style=flat-square) | ⭐ C | 反中共政治宣传库。Anti Chinese government propaganda. https://github.com/cirosantilli/china-dictatorship 的备份backup. 住在中国真名用户的网友请别给星星，不然你要被警察请喝茶。常见问答集，新闻集和饭店和音乐建议。卐习万岁卐。冠状病毒审查郝海东新疆改造中心六四事件法轮功 996.ICU709大抓捕巴拿... |
| [china-dictatroship-7](https://github.com/cirosantilli/china-dictatroship-7) | ![](https://img.shields.io/github/stars/cirosantilli/china-dictatroship-7?style=flat-square) | ⭐ C | 反中共政治宣传库。Anti Chinese government propaganda. https://github.com/cirosantilli/china-dictatorship 的备份backup. 住在中国真名用户的网友请别给星星，不然你要被警察请喝茶。常见问答集，新闻集和饭店和音乐建议。卐习万岁卐。冠状病毒审查郝海东新疆改造中心六四事件法轮功 996.ICU709大抓捕巴拿... |
| [.github](https://github.com/gege-circle/.github) | ![](https://img.shields.io/github/stars/gege-circle/.github?style=flat-square) | ⭐ C | 这里是GitHub的草场，也是戈戈圈爱好者的交流地，主要讨论动漫、游戏、科技、人文、生活等所有话题，欢迎各位小伙伴们在此讨论趣事。This is GitHub grassland, and the community place for Gege circle lovers, mainly discusses anime, games, technology, lifing and othe... |
| [china-dictatorship](https://github.com/Daravai1234/china-dictatorship) | ![](https://img.shields.io/github/stars/Daravai1234/china-dictatorship?style=flat-square) | ⭐ C | 反中共政治宣传库。Anti Chinese government propaganda. 住在中国真名用户的网友请别给星星，不然你要被警察请喝茶。常见问答集，新闻集和饭店和音乐建议。卐习万岁卐。冠状病毒审查郝海东新疆改造中心六四事件法轮功 996.ICU709大抓捕巴拿马文件邓家贵低端人口西藏骚乱。Friends who live in China and have real name on... |
| [PCL2](https://github.com/b0LBwZ7r5HOeh6CBMuQIhVu3-s-random-fork/PCL2) | ![](https://img.shields.io/github/stars/b0LBwZ7r5HOeh6CBMuQIhVu3-s-random-fork/PCL2?style=flat-square) | ⭐ C | [stays mad] 反PCL宣传库。Anti PCL propaganda. 大陆修宪香港恶法台湾武统朝鲜毁约美中冷战等都是王沪宁愚弄习思想极左命运共同体的大策划中共窃国这半个多世纪所犯下的滔天罪恶，前期是毛泽东策划的，中期6.4前后是邓小平策划的，黄牛数据分析后期是毛的极左追随者三朝罪恶元凶王沪宁策划的。王沪宁高小肆业因文革政治和情报需要保送“学院外语班“红色仕途翻身，所以王的本质是极... |
| [PCL2](https://github.com/zpc1314521/PCL2) | ![](https://img.shields.io/github/stars/zpc1314521/PCL2?style=flat-square) | ⭐ C | [stays mad] 反PCL宣传库。Anti PCL propaganda. 大陆修宪香港恶法台湾武统朝鲜毁约美中冷战等都是王沪宁愚弄习思想极左命运共同体的大策划中共窃国这半个多世纪所犯下的滔天罪恶，前期是毛泽东策划的，中期6.4前后是邓小平策划的，黄牛数据分析后期是毛的极左追随者三朝罪恶元凶王沪宁策划的。王沪宁高小肆业因文革政治和情报需要保送“学院外语班“红色仕途翻身，所以王的本质是极... |
| [OpenPacketFix_](https://github.com/panbinibn/OpenPacketFix_) | ![](https://img.shields.io/github/stars/panbinibn/OpenPacketFix_?style=flat-square) | ⭐ C | 大陆修宪香港恶法台湾武统朝鲜毁约美中冷战等都是王沪宁愚弄习思想极左命运共同体的大策划中共窃国这半个多世纪所犯下的滔天罪恶，前期是毛泽东策划的，中期6.4前后是邓小平策划的，黄牛数据分析后期是毛的极左追随者三朝罪恶元凶王沪宁策划的。王沪宁高小肆业因文革政治和情报需要保送“学院外语班“红色仕途翻身，所以王的本质是极左的。他是在上海底层弄堂长大的，因其本性也促成其瘪三下三滥个性，所以也都说他有易主... |
| [funNLP](https://github.com/fighting41love/funNLP) | ![](https://img.shields.io/github/stars/fighting41love/funNLP?style=flat-square) | ⭐ C | 中英文敏感词、语言检测、中外手机/电话归属地/运营商查询、名字推断性别、手机号抽取、身份证抽取、邮箱抽取、中日文人名库、中文缩写库、拆字词典、词汇情感值、停用词、反动词表、暴恐词表、繁简体转换、英文模拟中文发音、汪峰歌词生成器、职业名称词库、同义词库、反义词库、否定词库、汽车品牌词库、汽车零件词库、连续英文切割、各种中文词向量、公司名字大全、古诗词库、IT词库、财经词库、成语词库、地名词库、... |
| [AICUP-Deidentification-of-Medical-Data](https://github.com/windsuzu/AICUP-Deidentification-of-Medical-Data) | ![](https://img.shields.io/github/stars/windsuzu/AICUP-Deidentification-of-Medical-Data?style=flat-square) | ⭐ C | Chinese NER problem that needs to capture 18 types of entities in medical conversation text. The process is divided into 4 parts that are encapsulated in high-level abstract classes. We control the... |
| [MediScribe](https://github.com/Courtzcorner/MediScribe) | ![](https://img.shields.io/github/stars/Courtzcorner/MediScribe?style=flat-square) | ⭐ C | AI medical assistant that helps physicians with note taking and clerical tasks. |
| [Doctor-Recommendation-AI-model](https://github.com/Gueddari-Wassim/Doctor-Recommendation-AI-model) | ![](https://img.shields.io/github/stars/Gueddari-Wassim/Doctor-Recommendation-AI-model?style=flat-square) | ⭐ C | A NLP medical specialty classification model that predicts the most relevant doctor specialty based on user-provided symptom descriptions. Built with PyTorch and served via FastAPI. |
| [Awesome-Self-Evolving-AI-for-Agentic-Healthcare](https://github.com/ZhihaoPENG-CityU/Awesome-Self-Evolving-AI-for-Agentic-Healthcare) | ![](https://img.shields.io/github/stars/ZhihaoPENG-CityU/Awesome-Self-Evolving-AI-for-Agentic-Healthcare?style=flat-square) | ⭐ C | *(no description)* |
| [cyber-doctor（赛博华佗）](https://github.com/Warma10032/cyber-doctor) | ![](https://img.shields.io/github/stars/Warma10032/cyber-doctor?style=flat-square) | ⭐⭐ B | Multi-modal medical agent with knowledge graph. Local deployment, Chinese native. Disease diagnosis, medical record analysis. |
| [MedgeClaw](https://github.com/xjtulyc/MedgeClaw) | ![](https://img.shields.io/github/stars/xjtulyc/MedgeClaw?style=flat-square) | ⭐⭐ B+ | XJTU — Biomedical AI research orchestrator. Integrates 140+ K-Dense scientific skills via Claude Code + OpenClaw. Supports WhatsApp/Slack/Feishu/Discord interfaces. |
| [HealthFlow](https://github.com/yhzhu99/HealthFlow) | ![](https://img.shields.io/github/stars/yhzhu99/HealthFlow?style=flat-square) | ⭐⭐ B- | Self-evolving healthcare-research agent framework with meta-planning, hypothesis generation, retrieval, and evaluation loops for autonomous literature-guided medical research workflows. |
| [medgraph-ai](https://github.com/asanmateu/medgraph-ai) | — | ⭐⭐ B | Healthcare RAG with Neo4j knowledge graphs. LangChain + FastAPI. |
| [SOLVE-Med](https://github.com/PRAISELab-PicusLab/SOLVE-Med) | — | ⭐ C | Privacy-oriented multi-agent SLM for medical Q&A. Cloud-free, offline capable. |
| [Isaree-Platform](https://github.com/Isaree-ai/Isaree-Platform) | — | ⭐ C | Open-source medical-compliant AI assistant and orchestration engine. |
| [Multi_Agent_Medical_System](https://github.com/joyceannie/Multi_Agent_Medical_System) | — | ⭐ C | ICD-10 code extraction, SOAP note generation, medical image analysis. LangGraph + MedGemma. |
| [Prescriptly-AI](https://github.com/warshit/Prescriptly-AI) | — | ⭐ C | Autonomous agent for prescription interpretation. |
| [Doctor_Agent](https://github.com/Ho3seinTork/Doctor_Agent) | — | ⭐ C 🔴 | AI medical assistant: symptom analysis, health data management. *(Stale)* |
| [crewai-health-advisor](https://github.com/AjayKuchhadiya/crewai-health-advisor) | — | ⭐ C 🔴 | CrewAI for medical report summarization. *(Stale)* |
| [MediCARE](https://github.com/giuseppericcio/MediCARE) | — | ⭐ C 🔴 | Collaborative agents over heterogeneous medical graphs. *(Stale)* |
| [HERA](https://github.com/Nerdboss-stm/hera-healthcare-ai) | ![](https://img.shields.io/github/stars/Nerdboss-stm/hera-healthcare-ai?style=flat-square) | ⭐⭐ B- | Production-style healthcare AI platform combining triage/diagnostic/treatment agents, biomedical NER, RAG, FHIR R4, observability, and a 9-stage patient pipeline. Dockerized with 104 tests and a live demo. |

---

| [References](https://github.com/Aryia-Behroziuan/References) | ![](https://img.shields.io/github/stars/Aryia-Behroziuan/References?style=flat-square) | ⭐ C | Poole, Mackworth & Goebel 1998, p. 1.  Russell & Norvig 2003, p. 55.  Definition of AI as the study of intelligent agents: Poole, Mackworth & Goebel (1998), which provides the version that is used ... |
| [preclinical](https://github.com/Mentat-Lab/preclinical) | ![](https://img.shields.io/github/stars/Mentat-Lab/preclinical?style=flat-square) | ⭐ C | Preclinical is an open-source healthcare AI safety testing platform. It simulates realistic adversarial patient interactions against your agent, stores transcripts, and grades outcomes against safe... |
| [open-medical-scribe](https://github.com/BirgerMoell/open-medical-scribe) | ![](https://img.shields.io/github/stars/BirgerMoell/open-medical-scribe?style=flat-square) | ⭐ C | Open-source medical scribe with pluggable providers for transcription and note generation. Supports OpenAI, Anthropic, Gemini, Deepgram, Berget AI, Ollama, whisper.cpp, and more. |
| [Pretty_Good_AI](https://github.com/Sat-ish77/Pretty_Good_AI) | ![](https://img.shields.io/github/stars/Sat-ish77/Pretty_Good_AI?style=flat-square) | ⭐ C | Automated voice bot that stress-tests AI medical receptionists via Twilio phone calls , simulating 13 patient scenarios to uncover HIPAA violations, emergency handling failures, and hallucination b... |
| [healthcare-agents](https://github.com/ajhcs/healthcare-agents) | ![](https://img.shields.io/github/stars/ajhcs/healthcare-agents?style=flat-square) | ⭐ C | 51 specialized AI agents for US healthcare administration. MHA-level expertise in revenue cycle, compliance, quality, clinical ops, payer relations, health IT, and more. Modeled after agency-agents. |
| [bmlibrarian](https://github.com/hherb/bmlibrarian) | ![](https://img.shields.io/github/stars/hherb/bmlibrarian?style=flat-square) | ⭐ C | Multi-agentic biomedical literature research system with counterfactual analsyis and extensive citation system |
| [Some-Many-Books](https://github.com/Dujltqzv/Some-Many-Books) | ![](https://img.shields.io/github/stars/Dujltqzv/Some-Many-Books?style=flat-square) | ⭐ C | 个人收藏书籍列表　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　... |
| [1](https://github.com/pxvr-official/1) | ![](https://img.shields.io/github/stars/pxvr-official/1?style=flat-square) | ⭐ C | 無許諾配信 企業理念剽窃 動物の森収益化 大神ミオ権利者削除 戌神権利侵害発言 常闇トワ炎上 夜空メルストーカー被害 建築王サポーター放置 赤十字マーク 魔乃アロエ卒業 一つの中國支持声明 大空昴3Dライブ 無限延期清掃員職業差別 日清コラボ楽曲 musedash非公開 rog案件取り消し 壁画ライブ 丁真 Ding Zhen 郑爽 Zheng Shuang 防护林 与朵小天使w 伊月猫凛 ... |
| [Clinical-LLM-Monitor](https://github.com/giakhanhhii/Clinical-LLM-Monitor) | ![](https://img.shields.io/github/stars/giakhanhhii/Clinical-LLM-Monitor?style=flat-square) | ⭐ C | *(no description)* |
| [AIHospital](https://github.com/spjianke-source/AIHospital) | ![](https://img.shields.io/github/stars/spjianke-source/AIHospital?style=flat-square) | ⭐ C | An LLM-powered multi-agent hospital simulation platform for clinical reasoning, role-based norm compliance, and interactive healthcare training. |
| [phi-redactor](https://github.com/DilawarShafiq/phi-redactor) | ![](https://img.shields.io/github/stars/DilawarShafiq/phi-redactor?style=flat-square) | ⭐ C | HIPAA-native PHI redaction proxy for AI/LLM interactions. Detects and masks all 18 Safe Harbor identifiers with clinically coherent synthetic replacements. |
| [Prior-Authorization-Multi-Agent-Solution-Accelerator](https://github.com/microsoft/Prior-Authorization-Multi-Agent-Solution-Accelerator) | ![](https://img.shields.io/github/stars/microsoft/Prior-Authorization-Multi-Agent-Solution-Accelerator?style=flat-square) | ⭐ C | Payer-side AI-assisted prior authorization review using Microsoft Agent Framework with four Foundry Hosted Agents (Compliance, Clinical, Coverage, Synthesis). Gate-based decision rubric, MCP health... |
| [Post-Discharge-Medical-AI-Assistant-POC](https://github.com/nehaabhalerao/Post-Discharge-Medical-AI-Assistant-POC) | ![](https://img.shields.io/github/stars/nehaabhalerao/Post-Discharge-Medical-AI-Assistant-POC?style=flat-square) | ⭐ C | You'll demonstrate core GenAI skills including RAG implementation, multi-agent orchestration, and medical data processing in a simplified but functional system. |
| [claude-medical-code-extraction](https://github.com/michalekb11/claude-medical-code-extraction) | ![](https://img.shields.io/github/stars/michalekb11/claude-medical-code-extraction?style=flat-square) | ⭐ C | Use Claude 2.0 to extract lists of medical billing codes from unstructured PDFs |
| [Nitinol](https://github.com/YQZ11111/Nitinol) | ![](https://img.shields.io/github/stars/YQZ11111/Nitinol?style=flat-square) | ⭐ C | 一个现代化的智能医疗助理平台，旨在通过 AI 技术让就医更简单，让健康触手可及. a modern smart medical assistant platform that aims to make healthcare simpler and health within reach through AI technology. |
| [hit-webinar.github.io](https://github.com/hit-webinar/hit-webinar.github.io) | ![](https://img.shields.io/github/stars/hit-webinar/hit-webinar.github.io?style=flat-square) | ⭐ C | 关注医疗智能科技相关的中文网络研讨会 |
| [Medical-Multi-Agent-Co-Pilot](https://github.com/wzm110/Medical-Multi-Agent-Co-Pilot) | ![](https://img.shields.io/github/stars/wzm110/Medical-Multi-Agent-Co-Pilot?style=flat-square) | ⭐ C | 本项目旨在解决医疗场景中“挂错号”、基层诊疗能力不足及AI模型“黑箱”问题，设计并实现一个模拟“多学科会诊”模式的可解释智能系统。项目以 LangGraph 作为核心工作流编排框架，结合Ollama本地化部署开源大模型，通过Docker进行容器化部署， 构建了一个包含症状采集、分诊调度、专科诊断与决策融合的四智能体协作原型，最终通过严谨的评估验证了该系统在提升分诊准确性与就医效率方面的有效性。 |
| [rytzuXVNNP](https://github.com/3886370410/rytzuXVNNP) | ![](https://img.shields.io/github/stars/3886370410/rytzuXVNNP?style=flat-square) | ⭐ C | 本项目是一款智能骨折诊断系统，采用YOLO与大模型技术，可实现高效准确的骨折图像识别。系统具备以下功能模块：骨折图像预处理、深度学习模型训练、实时骨折检测与定位、诊断结果展示与统计。系统具有快速识别、高准确率、易用性强等特点，适用于医疗机构和临床诊断。 |
| [tumor-ai-analysis-system](https://github.com/fish0976/tumor-ai-analysis-system) | ![](https://img.shields.io/github/stars/fish0976/tumor-ai-analysis-system?style=flat-square) | ⭐ C | 基于 SpringBoot + 通义千问多模态大模型的肿瘤影像 AI 分析系统，实现影像上传、AI 诊断、PDF 报告生成、数据管理全流程，适配医疗场景做工程化优化。 |
| [Agent-based-Intelligent-Triage--LangGraph](https://github.com/MsZml/Agent-based-Intelligent-Triage--LangGraph) | ![](https://img.shields.io/github/stars/MsZml/Agent-based-Intelligent-Triage--LangGraph?style=flat-square) | ⭐ C | 本项目基于 LangGraph 实现了医疗智能分诊的完整工作流，核心是状态图驱动的 Agent + 工具调用模式，支持意图分析、工具并行调用、结果评分、查询重写等关键环节； 技术栈上兼容多类大模型，通过 PostgreSQL+pgvector 实现持久化存储，同时提供 API 和 WebUI 两种交互方式 |
## Clinical Software & EHR
| [HealthWallet.me](https://github.com/LifeValue/HealthWallet.me) | ![](https://img.shields.io/github/stars/LifeValue/HealthWallet.me?style=flat-square) | ⭐⭐ B | Offline-first mobile health record manager with on-device AI, local document parsing, and FHIR R4 connectivity to 52K+ US healthcare providers. |
| [Open Wearables](https://github.com/the-momentum/open-wearables) | ![](https://img.shields.io/github/stars/the-momentum/open-wearables?style=flat-square) | ⭐⭐ B | Self-hosted wearable-data platform with a unified API, developer portal, and AI-ready natural-language automations across Apple Health, Garmin, Oura, WHOOP, Fitbit, and more. |
| [KinCare](https://github.com/NanshineLoong/KinCare) | ![](https://img.shields.io/github/stars/NanshineLoong/KinCare?style=flat-square) | ⭐ C+ | Self-hosted family health space with AI chat/voice assistance, unified household health profiles, daily insights, role-based permissions, and Docker-based deployment. |
| [clinical-doc-intelligence](https://github.com/erickyegon/clinical-doc-intelligence) | ![](https://img.shields.io/github/stars/erickyegon/clinical-doc-intelligence?style=flat-square) | ⭐ C | AI-powered FDA drug label intelligence platform — production RAG with 5-stage retrieval, multi-agent orchestration, clinical guardrails, and 54 automated tests |
| [fhir4java-agents](https://github.com/sg-victorchai/fhir4java-agents) | ![](https://img.shields.io/github/stars/sg-victorchai/fhir4java-agents?style=flat-square) | ⭐ C | A lightweight Java FHIR API server for configuration-driven HL7 FHIR based services with AI capabilities, support both native and MCP plugins for extensible healthcare APIs and workflows |
| [ClinicSim-AI](https://github.com/peienwu1216/ClinicSim-AI) | ![](https://img.shields.io/github/stars/peienwu1216/ClinicSim-AI?style=flat-square) | ⭐ C | AI-powered clinical skills training platform for medical students |
| [MR4CPS](https://github.com/peihuacher/MR4CPS) | ![](https://img.shields.io/github/stars/peihuacher/MR4CPS?style=flat-square) | ⭐ C | MR4CPS is a Portable AI-powered Mixed Reality system for Clinical Procedural Skills training. Here we document how we integrate LLM into mr4cps. |
| [medical-voice-agent](https://github.com/ibrahimhamwi99/medical-voice-agent) | ![](https://img.shields.io/github/stars/ibrahimhamwi99/medical-voice-agent?style=flat-square) | ⭐ C | 🤖 Streamline appointment management with an AI voice agent that handles calls, schedules, and integrates seamlessly with EHR systems for medical practices. |
| [MedSync-AI](https://github.com/tirth-patel06/MedSync-AI) | ![](https://img.shields.io/github/stars/tirth-patel06/MedSync-AI?style=flat-square) | ⭐ C+ | Medication-adherence assistant with a React/Express stack, reminders, drug interaction checks, report analysis, and AI health agents. Includes architecture, security, and EHR/wearable integration docs. |

> Open-source clinical systems, EMR editors, and hospital information systems.

| Project | Stars | Description |
|---------|-------|-------------|
| [SoDiaoEditor](https://github.com/tlzzu/SoDiaoEditor) | ![](https://img.shields.io/github/stars/tlzzu/SoDiaoEditor?style=flat-square) | Generic structured document editor used as EMR editor in Chinese hospitals. Template support, structured data entry. |
| [carlos](https://github.com/carlos-emr/carlos) | ![](https://img.shields.io/github/stars/carlos-emr/carlos?style=flat-square) | Open-source EMR for Canadian healthcare with HL7/FHIR interoperability, Java/Spring services, Docker-based deployment, and a clear contribution/development workflow. |
| [HIS (ZainZhao)](https://github.com/ZainZhao/HIS) | ![](https://img.shields.io/github/stars/ZainZhao/HIS?style=flat-square) | Hospital Information System. Outpatient/pharmacy/finance/patient workstations. Spring Boot. |
| [HIS (TANGKUO)](https://github.com/TANGKUO/HIS) | ![](https://img.shields.io/github/stars/TANGKUO/HIS?style=flat-square) | Hospital Information System. Clinical, drug, finance, patient management. |
| [Cloud Medical System](https://github.com/Rain-Ricky/cloud) | ![](https://img.shields.io/github/stars/Rain-Ricky/cloud?style=flat-square) | Online appointment, telemedicine, report lookup, billing. Spring Boot + frontend/backend separation. |

---

| [met-bot](https://github.com/onesky2015/met-bot) | ![](https://img.shields.io/github/stars/onesky2015/met-bot?style=flat-square) | ⭐ C | A multi-model AI bot tracking pediatric SLE research updates. 关注儿童红斑狼疮医疗情报的 AI 机器人 |
## NLP & Text Mining

> Medical NLP models and clinical text processing.

| Project | Stars | Description |
|---------|-------|-------------|
| [Chinese-clinical-NER](https://github.com/MenglinLu/Chinese-clinical-NER) | ![](https://img.shields.io/github/stars/MenglinLu/Chinese-clinical-NER?style=flat-square) | CCKS2019 Chinese clinical NER: diseases, anatomy, imaging, lab tests, surgery, drugs (6 entity types). |

---

## Biomedical Research & Drug Discovery

> AI platforms for biomolecular modeling, virtual screening, and pharma R&D workflows.

| Project | Stars | Grade | Description |
|---------|-------|-------|-------------|
| [BioNeMo Framework](https://github.com/NVIDIA/bionemo-framework) | ![](https://img.shields.io/github/stars/NVIDIA/bionemo-framework?style=flat-square) | ⭐⭐⭐ A- | NVIDIA's digital-biology framework for training and adapting biomolecular transformer models at scale. Ships with GPU-optimized recipes, benchmarked biological foundation models, extensive docs, and active CI. |
| [scvi-tools](https://github.com/scverse/scvi-tools) | ![](https://img.shields.io/github/stars/scverse/scvi-tools?style=flat-square) | ⭐⭐⭐ A- | Mature probabilistic modeling toolkit for single-cell and spatial omics, with extensive docs, tutorials, benchmarks, and active community maintenance on top of PyTorch and AnnData. |
| [cBioPortal](https://github.com/cBioPortal/cbioportal) | ![](https://img.shields.io/github/stars/cBioPortal/cbioportal?style=flat-square) | ⭐⭐⭐ A- | Widely used cancer genomics portal for exploring, visualizing, and downloading large-scale oncology datasets. Strong docs, deployment guides, and an active production codebase. |
| [AIAgents4Pharma](https://github.com/VirtualPatientEngine/AIAgents4Pharma) | ![](https://img.shields.io/github/stars/VirtualPatientEngine/AIAgents4Pharma?style=flat-square) | ⭐⭐ B | Pharma R&D agent suite with Docker/uv installs, docs, and modules for BioModels, knowledge graphs, literature mining, single-cell workflows, and multi-agent orchestration. |
| [asapdiscovery](https://github.com/asapdiscovery/asapdiscovery) | ![](https://img.shields.io/github/stars/asapdiscovery/asapdiscovery?style=flat-square) | ⭐⭐ B | Consortium-backed open antiviral drug-discovery toolkit with structure-based workflows, notebooks, documentation, and Python packaging for reproducible research. |
| [CASSIA](https://github.com/ElliotXie/CASSIA) | ![](https://img.shields.io/github/stars/ElliotXie/CASSIA?style=flat-square) | ⭐⭐ B | Multi-agent single-cell cell-type annotation framework with R and Python packages, a hosted web UI, benchmark pages, and detailed docs for marker-driven and LLM-assisted interpretation workflows. |
| [Genomic Agent Discovery](https://github.com/HelixGenomics/Genomic-Agent-Discovery) | ![](https://img.shields.io/github/stars/HelixGenomics/Genomic-Agent-Discovery?style=flat-square) | ⭐⭐ B- | Local genomics agent workspace for 23andMe, AncestryDNA, and VCF analysis with a dashboard, configurable public-database lookups, transparent prompts, tests, and privacy-first on-device processing. |
| [lobster](https://github.com/the-omics-os/lobster) | ![](https://img.shields.io/github/stars/the-omics-os/lobster?style=flat-square) | ⭐⭐ B- | Self-evolving agentic bioinformatics framework with installable package, benchmark harness, autonomous debugging loop, and reproducible genomics-oriented analysis workflows. |
| [scAgent](https://github.com/AI4S-YB/scAgent) | ![](https://img.shields.io/github/stars/AI4S-YB/scAgent?style=flat-square) | ⭐ C+ | Agentic single-cell analysis platform with a Go control plane, Python runtime, web UI, 32 executable skills, workspace persistence, and optional WeChat bridge. |

---

## Research & Paper Collections

| Resource | Stars | Description |
|----------|-------|-------------|
| [Awesome-LLM-Healthcare](https://github.com/mingze-yuan/Awesome-LLM-Healthcare) | ![](https://img.shields.io/github/stars/mingze-yuan/Awesome-LLM-Healthcare?style=flat-square) | Curated paper list: LLMs in medicine. |
| [Awesome-Medical-Healthcare-Dataset-For-LLM](https://github.com/onejune2018/Awesome-Medical-Healthcare-Dataset-For-LLM) | ![](https://img.shields.io/github/stars/onejune2018/Awesome-Medical-Healthcare-Dataset-For-LLM?style=flat-square) | Curated bilingual index of medical and healthcare LLM datasets, models, and papers, with direct links to Chinese and English resources. |
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
