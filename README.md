## Arjun Thilak R

AI researcher at **Eros Innovation**, Chennai. I build benchmarks and evaluation setups that measure what language-model agents actually do, as opposed to what they report. Most of my recent work is on metacognition, tool use under budget limits, and small on-device models.

[LinkedIn](https://linkedin.com/in/arjun-thilak) · [Kaggle](https://www.kaggle.com/rarjunthilak) · [Email](mailto:arjunthilak2005@gmail.com)

---

### Research

**[GAUGE: Grading Awareness of Uncertainty and Grounded Epistemics](https://github.com/arjunthilak05/gauge-metacognition)**
Grand Prize, *Measuring Progress Toward AGI*, Google DeepMind × Kaggle (2026). One of four grand prizes across all tracks.
A 3-turn metacognition benchmark: 270 items, 8 models, 4 families. Gemini 2.5 Pro scored 94% accuracy and never abstained once (L-Score 0.0). Claude Haiku 4.5 scored 78% and had the highest metacognitive score (0.870). Being right and knowing when you're likely to be wrong turn out to be different skills.

**[Missing Callers Under a Response Budget](https://github.com/arjunthilak05/missing-callers-gemma4)**, with Ramkumar M V (2026)
When a code-graph tool hands a local Gemma 4 31B agent a caller list with one caller left out, does the agent still find the missing one? We tested this over 30 pinned Python libraries and 11,250 episodes. An incomplete list beats no list by 15.6 points (95% CI 11.5–19.8), but most of that gain comes from the agent *finishing* its answer, not from *finding* the missing caller. [Paper](https://github.com/arjunthilak05/missing-callers-gemma4/blob/main/paper/Missing_Callers_paper.pdf) · [Dataset](https://www.kaggle.com/datasets/rarjunthilak/absent-edges-expa-v1)

**[AphasiaBridge](https://github.com/arjunthilak05/aphasiabridge)**
An audio LoRA on Gemma 4 E4B for aphasic speech, meant to run on-device so post-stroke patients can turn fragmented speech into clear messages. Held-out WER on APROCSA dropped from 75.3% to 55.3% in phase 1.

**[UWE-SkinLesion](https://github.com/arjunthilak05/UWE-SkinLesion)**
An uncertainty-weighted ensemble of 11 models (ViTs + CNNs, weighted by MC Dropout) for 7-class dermoscopy. 85.6% balanced accuracy on HAM10000 with lesion-grouped 5-fold CV.

### Publications

- **A Hybrid Approach to License Plate Recognition: YOLO-v9 and Quantum-Enhanced CNN Model.** IEEE GCITC 2024. [IEEE Xplore](https://ieeexplore.ieee.org/document/10862831)
- **Risk Prediction of Heroin Drug Consumption Using Machine Learning Algorithms.** Ramkumar M V, Arjun Thilak R. IEEE GCCIT 2024.

### Open source

**[antigravity-claude-mcp](https://github.com/arjunthilak05/antigravity-claude-mcp)** · [npm](https://www.npmjs.com/package/antigravity-claude-mcp)
An MCP server that lets Claude Code ask a different model family (Gemini 3 Pro, via Google Antigravity) for a second opinion on a plan or diff before you accept it. One command to install, zero dependencies.

### Other projects

| Project | What it is |
|---|---|
| [RapidEye-DisasterAI](https://github.com/arjunthilak05/RapidEye-DisasterAI) | DeepLabV3+ on xView2 satellite pairs; 4-class damage segmentation, then an urgency score that ranks where responders should go first |
| [Entropy-QGAN](https://github.com/arjunthilak05/Entropy-QGAN) | Quantum GAN with entanglement entropy as a generator regularizer against mode collapse (PennyLane + PyTorch) |
| [Multimodal-RAG](https://github.com/arjunthilak05/Multimodal-RAG) | CLIP + FAISS dense retrieval with BM25 hybrid re-ranking over text, images and tables; FastAPI + Next.js |
| [TinyLLM-Quantization](https://github.com/arjunthilak05/TinyLLM-Quantization) | PTQ vs. QAT (INT8/INT4) on Qwen2.5-0.5B on Apple Silicon, with size/latency comparisons |
| [CarParts-YOLOv11](https://github.com/arjunthilak05/CarParts-YOLOv11) | YOLOv11 on 19 car-part classes, 68.1 mAP@50 |

### Education

- **Sai University**, Computing and Data Science. CGPA 9.0 / 10
- **IIT Madras**, BS in Data Science and Applications. CGPA 8.23 / 10

### Recognition

- Grand Prize, Google DeepMind × Kaggle *Measuring Progress Toward AGI* hackathon (2026)
- Amazon DeepRacer, top 20 globally (2023–24)
- IIT Madras: Best Capstone Project in ML; course topper in Tools in Data Science and ML (2024)
- L&T Technology Services Scholarship (2024–)
- VIT Hackathon, top 20 of 1,500 teams (2024)

---

<sub>Python · PyTorch · Transformers / PEFT · PennyLane / Qiskit · FastAPI · TypeScript / Next.js · Docker</sub>
