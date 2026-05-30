### Hi, I'm 유건 (Yugeon) 👋

🎓 Undergraduate at **Sejong University, Department of Artificial Intelligence** (2023.03 – 2027.02 expected)

🔬 **Research Interests**
Multimodal Learning · 3D Vision · Driver Behavior Understanding under Domain Shift

---

#### 🚧 Currently Working On

- **Capstone Design — Occlusion-Robust Driver Monitoring** (2026.03 – present)
  → [`model4_dms`](https://github.com/yg2127/model4_dms)
  Multitask DMS classifier (action · gaze · hands · talk) made robust to occlusion
  (sunglasses · masks · patches). Core idea: an **occlusion-gated face input (occgateRAW)** that
  restores occluded facial landmarks via **ORFormer + StackedHGNet** and aligns them back to the
  mediapipe facemesh coordinate frame (Umeyama), with per-region occlusion judged by an occlusion CNN.
  Significantly reduces gaze performance degradation (PDI) under occlusion.
  Builds on the ST-GCN backbone from my Heart Lab internship.

---

#### 📚 Recent Research Activity

- **Heart Lab, Sejong University — Undergraduate Research Intern** (2025.06 – 2025.10)
  ST-GCN-based driver abnormal behavior classification on the _100 Driver Dataset_.

- **Lab Seminar Presentations** — paper reviews & presentations during the internship:
  GCN · CLIP · BYOL · ResNet · SVM
  → see [`lab-seminar-2025`](https://github.com/yg2127/lab-seminar-2025) for slides

---

#### 🧪 Selected Projects

- **PDF Paper Translator (Layout-preserving EN→KR Translation)** — 2025
  → [`pdf-paper-translator`](https://github.com/yg2127/pdf-paper-translator)
  YOLOv11 fine-tuned on DocLayNet for figure/table/equation/caption detection,
  PyMuPDF text extraction with custom point↔pixel coordinate transformation,
  and Helsinki-NLP en-ko model for translation while preserving original PDF layout.

---

#### 🛠 Tech

`Python` · `PyTorch` · `OpenCV` · `Git` · `Linux`

---

#### 🔗 Links

- 📝 Tech Blog — [yg2127.github.io](https://yg2127.github.io)
- 📧 Email — gyu32386@gmail.com
