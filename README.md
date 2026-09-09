### Hi, I'm 유건 (Yugeon) 👋

🎓 Undergraduate at **Sejong University, Department of Artificial Intelligence** (2023.03 – 2027.02 expected)

🔬 **Research Interests**
Computer Vision · Multimodal Learning · Vision-Language Models · Model Robustness · Driver Behavior Understanding under Occlusion

---

#### 📚 Recent Research Activity

- **[Smart Vision & Media Lab (SVM Lab)](https://sites.google.com/view/csi2267svm/), Sogang University — Undergraduate Research Intern (2026.09 – Present)**

- **Heart Lab, Sejong University — Undergraduate Research Intern** (2025.06 – 2025.10)
  ST-GCN-based driver behavior classification on the _100 Driver Dataset_ (action macro-F1 0.76).

- **Paper Review Slides** — Heart Lab seminar talks & independent paper reviews:
  GCN · CLIP · BYOL · ResNet · SVM · TabPFN
  → see [`paper-review-slides`](https://github.com/yg2127/paper-review-slides) for slides

---

#### 🧪 Selected Projects

- **Capstone Design — OcclusionGateNet: Occlusion- & NIR-Robust Driver Monitoring** (2026.03 – 2026.06) · 🏆 **Excellence Award**, Sejong University Creative Design Competition (2026) · **team lead**
  → [`OcclusionGateNet`](https://github.com/yg2127/OcclusionGateNet)
  Multitask DMS classifier (action · gaze · hands · talk) robust to occlusion (sunglasses · masks · hands)
  and night-time low-light, running on dual near-infrared (IR) cameras. Three pillars: **NIR domain adaptation**
  (YOLO-Pose fine-tuned on hand-labeled IR frames, mAP50-95 0.788), **occluded-landmark restoration**
  via **ORFormer + VQ-VAE + HGNet** (NME ≤ 5%), and **Occlusion-aware Dynamic Fusion** gating face/pose
  cues by per-region visibility from an occ CNN (Macro-F1 0.9714).
  Reaches **masked gaze F1 0.583** (+10.8–46.3% over external SOTA baselines) and cuts the degradation
  index **PDI 6.93% → 3.67%**. Demoed live on a night-time public road with two IR cameras (TTS risk warnings).
  Builds on the ST-GCN backbone from my Heart Lab internship.

- **PDF Paper Translator (Layout-preserving EN→KR Translation)** — 2025
  → [`pdf-paper-translator`](https://github.com/yg2127/pdf-paper-translator)
  YOLOv11 (DocLayNet) for figure/table/equation detection, PyMuPDF text extraction
  with custom point↔pixel coordinate transforms, and a QLoRA-fine-tuned
  TowerInstruct-13B (MarianMT fallback) for translation — preserving the original PDF layout.

---

#### 🛠 Tech

`Python` · `PyTorch` · `OpenCV` · `transformers` · `ultralytics (YOLOv11)` · `Git` · `Linux`

---

#### 🔗 Links

- 📝 GitBlog — [yg2127.github.io](https://yg2127.github.io)
- 📧 Email — gyu32386@gmail.com
