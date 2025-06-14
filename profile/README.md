# 🧠 GenCheck – Multi-Modal AI-Generated Content Detection Platform

**GenCheck** is a multi-modal content verification platform that detects whether a given **text**, **image**, or **video** is **AI-generated** or **human-created**.

With the rise of tools like ChatGPT, DALL·E, Midjourney, and deepfake generators, GenCheck brings **transparency and trust** to digital content.

---

## 🎯 Project Goals

- ✅ Build an AI/ML-powered detection system for **text**, **images**, and **videos**
- ✅ Provide **confidence scores** and **explainable insights**
- ✅ Support multiple file types with a seamless **upload → analyze → result** pipeline
- ✅ Enable **modular extensibility** (e.g., audio detection, metadata forensics)
- ✅ Educate users on generative AI ethics and content manipulation

---

## 🧩 Key Functionalities

### 🔠 Text Analysis Module

- Detects AI-generated content (e.g., ChatGPT, GPT-3, GPT-4)
- Provides **confidence scores** with rationale (e.g., low burstiness, predictable structure)
- Supports `.txt`, `.pdf`, and `.docx` file uploads

### 🖼️ Image Analysis Module

- Detects images from DALL·E, Midjourney, Stable Diffusion, etc.
- Flags **forensic anomalies** (e.g., texture inconsistencies, symmetry artifacts)
- Parses **EXIF metadata** to check for missing camera signatures

### 🎞️ Video Analysis Module

- Identifies **deepfakes** and AI-manipulated videos
- Analyzes **face landmarks**, **blinking patterns**, **lip-sync accuracy**
- Offers **frame-by-frame anomaly detection**

### 📊 Unified Report Dashboard

- View detection results: ✅ Human / 🤖 AI-generated
- Displays **confidence percentages** and visual cues
- Maintains per-user or per-session **analysis history**

---

## 🔐 Optional Features

- 🔑 **User Authentication** (history retention, user-specific logs)
- 🔌 **API Access** for third-party platform integrations
- 📤 **Exportable Reports** in `.pdf` format

---

## 🧑‍💻 Target Users

- 🎓 Academic Institutions – Prevent AI-written plagiarism
- 📰 Media Companies – Validate source authenticity
- 🧑‍💼 Recruiters – Verify originality of applicant content
- 👤 Individuals – Ensure trust in consumed digital content

---

## 🛠️ Tech Stack (Planned / In Progress)

| Area                | Tools / Technologies                              |
|---------------------|----------------------------------------------------|
| **Frontend**        | React, TailwindCSS, Chart.js                       |
| **Backend**         | Python (FastAPI / Flask), Node.js (optional)       |
| **ML Models**       | HuggingFace Transformers, CNNs, Deepfake models    |
| **Storage**         | AWS S3, Firebase, MongoDB                          |
| **Auth**            | Firebase Auth, JWT                                 |
| **File Parsing**    | PyMuPDF, python-docx, ffmpeg                       |
| **Metadata Parsing**| PIL, exifread, OpenCV                              |

---
