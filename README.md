<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img src="assets/banner-light.svg" alt="Arjun Thilak R, AI researcher" width="100%">
</picture>

I'm an AI researcher at **Eros Innovation** in Chennai, where I train generative models for images, video and speech. Most of my time goes into flow-matching diffusion, neural audio codecs, and the GPU pipelines that feed them.

[LinkedIn](https://linkedin.com/in/arjun-thilak) · [Kaggle](https://www.kaggle.com/rarjunthilak) · [Email](mailto:arjunthilak2005@gmail.com)

### Now

- **Text-to-speech, from scratch.** An expressive English TTS system: a GAN-trained neural audio codec (WavLM-distilled semantic FSQ, 15-layer acoustic RVQ, BigVGAN decoder) feeds a Qwen3-1.7B codec language model. The model is aligned with DPO/GRPO against speaker-similarity, intelligibility and naturalness rewards.
- **Text-to-image.** Core engineer on India's first culturally specialised T2I model, about 2B parameters, trained with rectified flow matching on 9.6M+ Indian cultural images. It uses a 5-stage progressive schedule from 512px to 4K.
- **Text-to-video data.** Turned 4,000+ full-length films into a 360M-frame training set for a T2V foundation model.
- **Data at scale.** A 9-stage image-curation pipeline: 7 models running as 6 microservices across 8×H100, with vLLM, YOLO, InsightFace, dual CLIP scoring and Ray scheduling. It has processed 30M+ images.

### Research

- **GAUGE: Measuring Monitoring–Control Coupling as a Metacognitive Failure Mode in LLMs.** ICST 2026 (Springer). Grand Prize, Google DeepMind × Kaggle *Measuring Progress Toward AGI*. [code](https://github.com/arjunthilak05/gauge-metacognition)
- **One-Cuff Subject Calibration for Facial rPPG Blood Pressure on MCD-rPPG.** IEEE EMBS BHI 2026.
- **Two-Stage Personalization of Audio Language Models for Aphasic Speech.** Under review. Fine-tunes Whisper-Large-v3 and Gemma 4 on AphasiaBank, cutting per-speaker WER from 0.625 to 0.521. [code](https://github.com/arjunthilak05/aphasiabridge)
- **Missing Callers Under a Response Budget: Finishing Versus Finding in a Local Gemma 4 Agent.** With Ramkumar M V. [paper](https://github.com/arjunthilak05/missing-callers-gemma4/blob/main/paper/Missing_Callers_paper.pdf) · [code](https://github.com/arjunthilak05/missing-callers-gemma4)
- **A Hybrid Approach to License Plate Recognition: YOLO-v9 and Quantum-Enhanced CNN Model.** IEEE GCITC 2024. [paper](https://ieeexplore.ieee.org/document/10862831)

### Open source

- **[antigravity-claude-mcp](https://github.com/arjunthilak05/antigravity-claude-mcp)**: lets Claude Code ask Gemini for a second opinion on a plan or diff. Available on [npm](https://www.npmjs.com/package/antigravity-claude-mcp).
- **[UWE-SkinLesion](https://github.com/arjunthilak05/UWE-SkinLesion)**: an 11-model ViT + CNN ensemble weighted by uncertainty. 85.6% balanced accuracy on HAM10000.
- **[TinyLLM-Quantization](https://github.com/arjunthilak05/TinyLLM-Quantization)**: PTQ vs. QAT at INT8/INT4 for small LLMs on Apple Silicon.

<details>
<summary>More</summary>
<br>

- [RapidEye-DisasterAI](https://github.com/arjunthilak05/RapidEye-DisasterAI): satellite damage segmentation with response-urgency ranking
- [Multimodal-RAG](https://github.com/arjunthilak05/Multimodal-RAG): CLIP + FAISS + BM25 hybrid retrieval over text, images and tables
- [Entropy-QGAN](https://github.com/arjunthilak05/Entropy-QGAN): entanglement-entropy regularisation for quantum GANs
- [CarParts-YOLOv11](https://github.com/arjunthilak05/CarParts-YOLOv11): 19-class car-part detection

</details>

### Background

BS in Computing & Data Science from **Sai University** (CGPA 9.0) and a Diploma in Data Science from **IIT Madras**, both 2022–26. In 2026 I was selected for the CS research cohort at Chennai Mathematical Institute. Before Eros I worked at HAL and IIT Madras Pravartak.

<sub>PyTorch · Diffusers · Transformers · vLLM · Ray · Triton · CUDA</sub>
