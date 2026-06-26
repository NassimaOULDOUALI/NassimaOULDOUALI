![Header](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=160&section=header&text=Nassima%20OULD%20OUALI&fontSize=44&fontColor=ffffff&animation=fadeIn&desc=Research%20Engineer%20in%20Speech%20%7C%20TTS%20%C2%B7%20Voice%20Conversion%20%C2%B7%20NLP&descAlignY=62&descSize=18)

<div align="center">

# 👋 Hi, I'm Nassima OULD OUALI

### Research Engineer in Speech @ Hi! PARIS / École Polytechnique
**TTS · Prosody Control · Voice Conversion · NLP**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-%230A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://fr.linkedin.com/in/nassima-ould-ouali-858644170)
[![Email](https://img.shields.io/badge/Email-Contact-%23D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nassima.ouldouali123@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-%23181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NassimaOULDOUALI)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Profile-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=s4YSZDEAAAAJ&hl=fr)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-Models-FF9D00?style=for-the-badge&logo=huggingface&logoColor=white)](https://huggingface.co/nassimaODL)

</div>

---

## About me

I am a **Research Engineer in Speech** within the **Hi! PARIS / École Polytechnique** ecosystem, working at the intersection of **speech generation**, **prosody control**, **voice conversion**, and **NLP**.

My work combines scientific rigor with production-grade engineering — from controllable French TTS and WavLM-based resynthesis to zero-shot multilingual voice conversion and large-scale, reproducible experimentation on HPC (Jean Zay / A100). I collaborate closely with senior researchers including **Éric Moulines** and **Reda Dehak**.

---

## 🔬 Research focus

- 🔊 **Controllable French TTS** with explicit prosody planning
- 🧠 **SSML-based modeling** for pauses, rhythm, emphasis, and timing
- 🧪 **WavLM → audio resynthesis** with adversarial training and layer ablations
- 🚀 **Zero-shot voice conversion** in learned speech-representation spaces
- 🌍 **Multilingual TTS adaptation** for European low-resource languages
- 📊 **Objective & perceptual evaluation** for reproducible speech research

---

## 🛠️ Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Transformers-FFD21E?style=flat&logo=huggingface&logoColor=black)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat&logo=nvidia&logoColor=white)
![Slurm](https://img.shields.io/badge/Slurm%20%2F%20HPC-2C3E50?style=flat&logo=linux&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat&logo=latex&logoColor=white)

**Specialties:** DDP / AMP distributed training · GAN & flow-matching / diffusion generation · LoRA / PEFT fine-tuning · speech representation learning · RAG & LLM orchestration · reproducible evaluation pipelines

---

## 🚀 Featured projects

### 🎧 Prosody-Control French TTS (SSML)
Controllable French speech synthesis with explicit SSML planning for pauses, timing, and emphasis — symbolic pause planning, break prediction, SSML generation, and reproducible training/inference.

[Repository](https://github.com/NassimaOULDOUALI/Prosody-Control-French-TTS) · [Demo](https://hi-paris.github.io/DemoTTS/) · [Paper — ICNLSP 2025](https://aclanthology.org/2025.icnlsp-1.30/) · HF: [text2breaks](https://huggingface.co/nassimaODL/ssml-text2breaks-fr-lora) · [break2ssml](https://huggingface.co/nassimaODL/ssml-break2ssml-fr-lora)

### 🧪 WavLM Vocoder for French
Waveform resynthesis from frozen WavLM representations: adversarial reconstruction (HiFi-GAN + MPD/MSD), learned weighted layer fusion over WavLM-Base+, chunked overlap-add inference, and layer-ablation studies. Trained on 238h of cleaned French speech (SIWIS, M-AILABS, Common Voice).

[Repository](https://github.com/hi-paris/wavlm-vocoder-french) · [Demo](https://hi-paris.github.io/wavlm2audio-demo/) · [HF Models](https://huggingface.co/nassimaODL) · [Paper — **JEP 2026**](https://www.isca-archive.org/tmp/jep_2026/ouldouali26_jep.pdf)

### 🌍 CosyVoice2-EU — Multilingual Zero-Shot TTS
Component-level adaptation of CosyVoice2 for European languages (French & German): language-specific fine-tuning of the text encoder, flow-matching module, and vocoder, evaluated across seen/unseen speakers.

[Repository](https://github.com/hi-paris/CosyVoice2-EU) · [Demo](https://hi-paris.github.io/CosyVoice2-EU/) · Paper under submission — **EUSIPCO 2026**

### 🧭 Compass — Agentic RAG Assistant (HEC Paris)
Production-deployed retrieval-augmented assistant for **HEC Paris**, combining document retrieval with an agentic LLM pipeline, served as a full web application on Azure. Focus on robust orchestration, controlled tool-calling, and cost-efficient inference.

[Live app](https://compass.francecentral.cloudapp.azure.com/) *(HEC login required)*
<br>**Stack:** RAG · LLM orchestration · vector retrieval · Flask/web app · Azure deployment

### 👁️ AIKON — Paleographic Analysis Module (École des Ponts / ENPC)
Developing a new computer-vision module for the **aikon-demo** platform that makes fine-grained, interpretable **paleographic (historical-script) analysis** accessible to historians without ML expertise. End-to-end pipeline (milestone 1): a new dataset object pairing **text-line images with their transcriptions**, a **training/inference API** that fine-tunes networks for morphological script-metrological analysis (following Vlachou-Efstathiou et al., ICDAR 2026), and an **interactive front-end** to explore results — character prototypes, morphological differences, distances, and diachronic evolution. Built for non-expert testing, open-source release, and documentation; later extensible to typographers. Developed with **Mathieu Aubry's group at École des Ponts (ENPC)**.

[Platform](https://aikon-demo.huma-num.fr/) · [Repository](https://github.com/Aikon-platform/aikon-demo) · **Stack:** Computer Vision · Python · PyTorch · web platform (front-end + API)

---

## 📚 Publications

| Venue | Title | Status |
|-------|-------|--------|
| **ICNLSP 2025** | *Improving French Synthetic Speech Quality via SSML Prosody Control* | Published — [ACL Anthology](https://aclanthology.org/2025.icnlsp-1.30/) |
| **JEP 2026** | *WavLM-Vocoder-French: Neural Waveform Resynthesis from Frozen WavLM Representations* | Published — [ISCA Archive](https://www.isca-archive.org/tmp/jep_2026/ouldouali26_jep.pdf) |
| **EUSIPCO 2026** | *Europeanizing Modular Zero-Shot TTS: A Component-Level Adaptation Framework for French and German* | Accepted |

**Released models:** [ssml-text2breaks-fr-lora](https://huggingface.co/nassimaODL/ssml-text2breaks-fr-lora) · [ssml-break2ssml-fr-lora](https://huggingface.co/nassimaODL/ssml-break2ssml-fr-lora)
**Demos:** [WavLM2Audio](https://hi-paris.github.io/wavlm2audio-demo/) · [Prosody-Control TTS](https://hi-paris.github.io/DemoTTS/) · [CosyVoice2-EU](https://hi-paris.github.io/CosyVoice2-EU/)

---

## 🎓 Education

| Degree | Institution |
|--------|-------------|
| Master's degree | Université Gustave Eiffel |
| Master's degree | UVSQ (Versailles Saint-Quentin-en-Yvelines) |
| Bachelor's degree | Université Paris Descartes |

---

## 🤝 Collaboration

Open to **research collaborations** and **industry partnerships** in controllable TTS, prosody modeling, French speech technology, multilingual voice conversion, and reproducible evaluation for speech systems — especially where scientific rigor, data confidentiality, and engineering quality matter.

If you find a repository useful, a ⭐ helps visibility and supports continued maintenance.

![Footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=120&section=footer&animation=fadeIn)
