### Hi, I'm Arjun

I'm an AI researcher at **Eros Innovation** in Chennai. I study how language-model agents behave as opposed to how they say they behave: whether they know when they're wrong, whether they act on what they know, and what they do with incomplete tools. I also work on small on-device models and camera-based health sensing.

Find me on [LinkedIn](https://linkedin.com/in/arjun-thilak) or [Kaggle](https://www.kaggle.com/rarjunthilak), or [email me](mailto:arjunthilak2005@gmail.com).

### Papers

| | |
|---|---|
| **BHI 2026** | **One-Cuff Subject Calibration for Facial rPPG Blood Pressure on MCD-rPPG: Diastolic Gains and a Systolic Ceiling.** IEEE EMBS International Conference on Biomedical and Health Informatics. |
| **ICST 2026** | **GAUGE: Measuring Monitoring–Control Coupling as a Metacognitive Failure Mode in Large Language Models.** Springer proceedings. [code](https://github.com/arjunthilak05/gauge-metacognition) |
| **2026** | **Missing Callers Under a Response Budget: Finishing Versus Finding in a Local Gemma 4 Agent.** With Ramkumar M V. [paper](https://github.com/arjunthilak05/missing-callers-gemma4/blob/main/paper/Missing_Callers_paper.pdf) · [code](https://github.com/arjunthilak05/missing-callers-gemma4) · [dataset](https://www.kaggle.com/datasets/rarjunthilak/absent-edges-expa-v1) |
| **IEEE 2025** | **A Hybrid Approach to License Plate Recognition: YOLO-v9 and Quantum-Enhanced CNN Model.** [IEEE Xplore](https://ieeexplore.ieee.org/document/10862831) |

### Selected work

<a href="https://github.com/arjunthilak05/gauge-metacognition"><img src="https://raw.githubusercontent.com/arjunthilak05/gauge-metacognition/main/figures/cover_final.png" width="420" align="right" alt="GAUGE: Gemini 2.5 Pro scores L = 0.0 and never abstains; Qwen3-235B scores L = 0.813"></a>

**[GAUGE](https://github.com/arjunthilak05/gauge-metacognition).** Grand Prize, Google DeepMind × Kaggle *Measuring Progress Toward AGI* (one of four across all tracks).
I gave 8 models 270 items, each in three turns: predict the difficulty, answer with a confidence, then decide whether to submit or abstain. Gemini 2.5 Pro got 94% right but never abstained, which gives it a coupling score of zero. The most accurate model was the least self-aware.

**[Missing Callers](https://github.com/arjunthilak05/missing-callers-gemma4).** What does a coding agent do when its code-graph tool quietly drops a caller from the list? Over 11,250 controlled episodes on 30 Python libraries, an incomplete list still helped by +15.6 points. Most of that gain came from the agent *finishing* its answer, not from *finding* the missing caller.

<br clear="right">

**[AphasiaBridge](https://github.com/arjunthilak05/aphasiabridge).** Audio LoRA on Gemma 4 E4B for post-stroke aphasic speech, running on the phone. In phase 1, held-out WER dropped from 75.3% to 55.3%.

**[UWE-SkinLesion](https://github.com/arjunthilak05/UWE-SkinLesion).** An 11-model ViT + CNN ensemble, weighted by MC Dropout uncertainty. 85.6% balanced accuracy on HAM10000 under lesion-grouped CV.

**[antigravity-claude-mcp](https://github.com/arjunthilak05/antigravity-claude-mcp)** ([npm](https://www.npmjs.com/package/antigravity-claude-mcp)). Lets Claude Code ask Gemini for a second opinion on a plan or diff before you accept it. One command to install, zero dependencies.

<details>
<summary><b>More projects</b></summary>
<br>

- [RapidEye-DisasterAI](https://github.com/arjunthilak05/RapidEye-DisasterAI): satellite damage segmentation (DeepLabV3+, xView2), plus an urgency score that ranks where responders should go first
- [Entropy-QGAN](https://github.com/arjunthilak05/Entropy-QGAN): entanglement entropy as a generator regularizer against mode collapse in quantum GANs
- [Multimodal-RAG](https://github.com/arjunthilak05/Multimodal-RAG): CLIP + FAISS + BM25 hybrid retrieval over text, images and tables
- [TinyLLM-Quantization](https://github.com/arjunthilak05/TinyLLM-Quantization): PTQ vs. QAT at INT8/INT4 on Qwen2.5-0.5B, on Apple Silicon
- [CarParts-YOLOv11](https://github.com/arjunthilak05/CarParts-YOLOv11): 19-class car-part detection, 68.1 mAP@50

</details>

### Background

I studied Computing & Data Science at **Sai University** (CGPA 9.0) and did the BS in Data Science at **IIT Madras** (CGPA 8.23) in parallel. Earlier wins: top 20 globally in Amazon DeepRacer, Best Capstone Project in ML at IIT Madras, and the L&T Technology Services Scholarship.

<sub>I mostly write Python (PyTorch, Transformers, PEFT) and TypeScript.</sub>
