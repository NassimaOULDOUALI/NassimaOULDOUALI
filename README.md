![Header](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=120&section=header&text=Nassima%20OULD%20OUALI&fontSize=40&fontColor=ffffff&animation=fadeIn)

<div align="center">

# 👋 Hi, I'm Nassima OULD OUALI

### Research Engineer in Speech @ Hi! PARIS / École Polytechnique  
### Working on TTS, Prosody Control, Voice Conversion, and NLP  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-%230A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://fr.linkedin.com/in/nassima-ould-ouali-858644170)
[![Email](https://img.shields.io/badge/Email-Contact-%23D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nassima.ouldouali123@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-%23181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NassimaOULDOUALI)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Profile-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=s4YSZDEAAAAJ&hl=fr)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-Models-FF9D00?style=for-the-badge&logo=huggingface&logoColor=white)](https://huggingface.co/nassimaODL)

</div>

---

## About me

I am a **Research Engineer in Speech** working within the **Hi! PARIS / École Polytechnique ecosystem**, contributing to research and engineering efforts in **speech generation**, **prosody control**, **voice conversion**, and **NLP**.

My work combines **scientific rigor** and **practical implementation**, with experience spanning:
- **French TTS and prosody control**
- **SSML-based modeling**
- **WavLM-based speech resynthesis**
- **Zero-shot multilingual voice conversion**
- **Evaluation and reproducible research pipelines**
- **HPC-scale experimentation**

I have developed my work in a strong academic research environment, including collaboration and scientific interactions within the **École Polytechnique ecosystem**.

---

## Research focus

- 🔊 **Controllable French TTS** with explicit prosody planning
- 🧠 **SSML-based modeling** for pauses, rhythm, emphasis, and timing
- 🧪 **WavLM → Audio resynthesis** with adversarial training and layer ablations
- 🚀 **Zero-shot voice conversion** using learned speech representations
- 🌍 **Multilingual TTS adaptation** for European low-resource languages
- 📊 **Objective and perceptual evaluation** for reproducible speech research
- ⚙️ **Distributed training pipelines** with PyTorch, DDP, AMP, and Slurm

---

## Selected contributions

- 📄 **ICNLSP 2025** — *Improving French Synthetic Speech Quality via SSML Prosody Control* — published
- 📄 **JEP 2026** — *WavLM-Vocoder-French: Neural Waveform Resynthesis from Frozen WavLM Representations* — accepted
- 📄 **EUSIPCO 2026** — *Europeanizing Modular Zero-Shot TTS: A Component-Level Adaptation Framework for French and German* — under submission
- 🤗 Released **Hugging Face models** for French SSML pause prediction and break rendering
- 🎙️ Developed **WavLM-based speech resynthesis** with adversarial training, layer ablation studies, and open-source release
- 🛠️ Built reproducible research pipelines for:
  - distributed training (**DDP / AMP**)
  - checkpoint-based evaluation
  - ablation studies
  - paper-ready tables and figures

---

## Experience

### Research Engineer in Speech  
**Hi! PARIS / École Polytechnique**

I contribute to research and development in **speech generation** and **language technologies**, with a particular focus on:
- controllable TTS
- prosody-aware modeling
- voice conversion
- multilingual speech adaptation
- evaluation methodology
- reproducible experimentation at scale

My work has been carried out in a highly demanding research setting, including scientific interactions with senior researchers such as **Éric Moulines** and **Reda Dehak**.

---

## Selected projects

### 🎧 Prosody-Control French TTS (SSML)
**Controllable French speech synthesis with explicit SSML planning for pauses, timing, and emphasis.**

**What this project includes**
- prosody-oriented text preprocessing
- symbolic pause planning
- SSML generation
- break prediction
- evaluation utilities
- reproducible training and inference scripts

**Links**
- [Repository](https://github.com/NassimaOULDOUALI/Prosody-Control-French-TTS)
- [Demo](https://hi-paris.github.io/DemoTTS/)
- [HF Model — `ssml-text2breaks-fr-lora`](https://huggingface.co/nassimaODL/ssml-text2breaks-fr-lora)
- [HF Model — `ssml-break2ssml-fr-lora`](https://huggingface.co/nassimaODL/ssml-break2ssml-fr-lora)
- [Paper — ICNLSP 2025](https://aclanthology.org/2025.icnlsp-1.30/)

---

### 🧪 WavLM Vocoder for French
**Waveform resynthesis from frozen WavLM representations for speech generation and voice conversion research.**

**What this project includes**
- adversarial waveform reconstruction (HiFi-GAN + MPD/MSD discriminators)
- learned weighted layer fusion over WavLM-Base+ representations
- chunked inference with overlap-add
- checkpoint evaluation and layer ablation experiments
- experiment tracking for paper-ready analysis
- trained on 238h of cleaned French speech (SIWIS, M-AILABS, Common Voice)

**Links**
- [Repository](https://github.com/hi-paris/wavlm-vocoder-french)
- [Demo](https://hi-paris.github.io/wavlm2audio-demo/)
- [HF Models](https://huggingface.co/nassimaODL)
- Paper accepted at **JEP 2026** (Montpellier, June 8–12)

---

### 🌍 CosyVoice2-EU — Multilingual Zero-Shot TTS Adaptation
**Component-level adaptation of CosyVoice2 for European languages, with a focus on French and German.**

**What this project includes**
- modular adaptation of a large-scale zero-shot TTS system
- language-specific fine-tuning of text encoder, flow matching module, and vocoder
- evaluation across seen and unseen speakers for French and German
- open-source release with reproducible training configs

**Links**
- [Repository](https://github.com/hi-paris/CosyVoice2-EU)
- [Demo](https://hi-paris.github.io/CosyVoice2-EU/)
- Paper under submission at **EUSIPCO 2026**

---

## Publications and research artifacts

### Publications

| Venue | Title | Status |
|-------|-------|--------|
| **ICNLSP 2025** | *Improving French Synthetic Speech Quality via SSML Prosody Control* | Published — [ACL Anthology](https://aclanthology.org/2025.icnlsp-1.30/) |
| **JEP 2026** | *WavLM-Vocoder-French: Neural Waveform Resynthesis from Frozen WavLM Representations* | Accepted |
| **EUSIPCO 2026** | *Europeanizing Modular Zero-Shot TTS: A Component-Level Adaptation Framework for French and German* | Under submission |

### Models
- [nassimaODL/ssml-text2breaks-fr-lora](https://huggingface.co/nassimaODL/ssml-text2breaks-fr-lora)
- [nassimaODL/ssml-break2ssml-fr-lora](https://huggingface.co/nassimaODL/ssml-break2ssml-fr-lora)

### Demos
- [WavLM2Audio](https://hi-paris.github.io/wavlm2audio-demo/)
- [Prosody-Control TTS](https://hi-paris.github.io/DemoTTS/)
- [CosyVoice2-EU](https://hi-paris.github.io/CosyVoice2-EU/)

### Research assets
- training and evaluation pipelines
- reproducible experiment configurations
- analysis scripts for ablations
- paper-ready figures and tables

---

## Technical expertise

### Speech and audio
- Text-to-Speech (TTS)
- prosody modeling
- SSML control
- pause prediction
- voice conversion
- multilingual speech adaptation
- speech evaluation
- segmentation and alignment
- chunked inference and overlap-add reconstruction

### Machine learning
- PyTorch
- distributed training (**DDP**)
- mixed precision (**AMP**)
- GAN training
- speech representation learning
- flow matching / diffusion-based generation

### Research engineering
- Slurm / HPC workflows
- experiment reproducibility
- checkpoint management
- configuration-driven training
- evaluation pipelines
- LaTeX-ready reporting and analysis

---

## Education

| Degree | Institution |
|--------|-------------|
| Master's degree | Université Gustave Eiffel |
| Master's degree | UVSQ (Versailles Saint-Quentin-en-Yvelines) |
| Bachelor's degree | Paris Descartes University |

---

## Collaboration

I am open to **research collaborations** and **industry partnerships** in:

- controllable TTS
- prosody modeling
- French speech technology
- multilingual voice conversion
- evaluation and reproducibility for speech systems

I am especially interested in projects where **scientific rigor**, **data confidentiality**, and **engineering quality** matter.

---

## GitHub stats

<div align="center">

![Nassima's GitHub Stats](https://github-readme-stats.vercel.app/api?username=NassimaOULDOUALI&show_icons=true&theme=radical&hide_border=true&include_all_commits=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=NassimaOULDOUALI&layout=compact&theme=radical&hide_border=true)

</div>

---

## Support my work

If you find my repositories useful for research or development, consider giving them a **star** on GitHub. It helps increase visibility and supports continued maintenance and improvement.

![Footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=120&section=footer&animation=fadeIn)
