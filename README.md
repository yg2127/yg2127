### Hi, I'm 유건 (Yugeon) 👋

🎓 Undergraduate at **Sejong University, Department of Artificial Intelligence** (2023.03 – 2027.02 expected)

🔬 **Research Interests**
Computer Vision · Multimodal Learning · Vision-Language Models · Model Robustness · Driver Behavior Understanding under Occlusion

---

#### 📚 Recent Research Activity

- **Heart Lab, Sejong University — Undergraduate Research Intern** (2025.06 – 2025.10)
  ST-GCN-based driver behavior classification on the _100 Driver Dataset_ (action macro-F1 0.76).

- **Paper Review Slides** — Heart Lab seminar talks & independent paper reviews:
  GCN · CLIP · BYOL · ResNet · SVM · TabPFN
  → see [`paper-review-slides`](https://github.com/yg2127/paper-review-slides) for slides

---

#### 🧪 Selected Projects

- **Capstone Design — Occlusion-Robust Driver Monitoring** (2026.03 – 2026.06) · 🏆 **Excellence Award**, Sejong University Creative Design Competition (2026)
  → [`full_model`](https://github.com/yg2127/full_model)
  Multitask DMS classifier (action · gaze · hands · talk) made robust to occlusion
  (sunglasses · masks · patches). Core idea: an **occlusion-gated face input (occgateRAW)** that
  restores occluded facial landmarks via **ORFormer + StackedHGNet** and aligns them back to the
  mediapipe facemesh coordinate frame (Umeyama), with per-region occlusion judged by an occlusion CNN.
  Reduces gaze performance degradation to **PDI 9.0%** (vs. 16–27% for landmark/image baselines) under occlusion.
  Builds on the ST-GCN backbone from my Heart Lab internship.

- **PDF Paper Translator (Layout-preserving EN→KR Translation)** — 2025
  → [`pdf-paper-translator`](https://github.com/yg2127/pdf-paper-translator)
  YOLOv11 fine-tuned on DocLayNet for figure/table/equation/caption detection,
  PyMuPDF text extraction with custom point↔pixel coordinate transformation,
  and Helsinki-NLP en-ko model for translation while preserving original PDF layout.

---

#### 🛠 Tech

`Python` · `PyTorch` · `OpenCV` · `transformers` · `ultralytics (YOLOv11)` · `Git` · `Linux`

---

#### 🔗 Links

- 📝 Tech Blog — [yg2127.github.io](https://yg2127.github.io)
- 📧 Email — gyu32386@gmail.com
