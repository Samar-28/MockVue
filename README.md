# 🎙️ MockVue – AI Interview Buddy  

MockVue is an advanced AI-driven interview platform designed to revolutionize the way candidates prepare for job interviews. By combining intelligent automation, machine learning, and interactive simulations, MockVue bridges the gap between traditional preparation methods and real-world interview expectations through personalized, immersive, and realistic interview experiences.

---

## 🚀 Key Features

- **🔍 Intelligent Resume Classification**  
Maps user resumes to relevant job roles using machine learning (BiLSTM, NN Dense), ensuring tailored interview simulations.

- **📝 AI-Powered Resume Review**  
Evaluates resumes for structure, clarity, keyword optimization, and alignment with the desired role or domain.

- **🎤 Real-Time Mock Interviews (HR & Technical)**  
AI-conducted interactive interviews dynamically tailored to the user’s resume and selected role.

- **🗣️ Voice-Enabled Conversations**  
Seamless speech-to-text and text-to-speech integration for natural, real-world interview simulations.

- **💡 Algorithmic & Problem-Solving Assessment**  
Pseudo-code challenges to evaluate problem-solving and articulation of technical concepts.

- **📊 Multi-Modal Performance Analysis**  
Analyzes user responses through:
  - **Video Analysis** (Posture, Emotion via DeepFace & OpenCV)  
  - **Audio Confidence Scoring**  
  - **Facial Expression Tracking**

- **📈 Comprehensive Feedback Reports**  
Detailed evaluation across technical depth, communication clarity, fluency, and confidence.

---

## 🛠️ Tech Stack

### **Frontend**  
- React.js  
- Web Speech API (Speech-to-Text)  
- AWS Polly (Text-to-Speech)  
- React Overlays  

### **Backend**  
- Node.js with Express.js  
- REST APIs  
- WebSockets (Real-Time Interaction)  
- CI/CD Integration  

### **AI & Machine Learning**  
- BiLSTM, NN Dense (Resume Classification)  
- DeepFace & OpenCV (Video Analysis)  
- Generative AI (Interview Questions & Feedback)  

### **Other Tools**  
- Frame Extraction for Video Analysis  
- Audio Confidence Scoring  

---

## 👥 Team & Contributions

| Team Member       | Contributions                                                             |
|-------------------|---------------------------------------------------------------------------|
| **Samarpreet Singh**  | Google Auth (Sessions), Resume Parsing, GenAI, Model Integration, Front-End, CI/CD |
| **Krishna Deol**      | AWS Polly (TTS), Audio Confidence Scoring, UI Components (React)            |
| **Sunpreet Singh**    | WebSockets, Resume Review, Web Speech API (STT), Frame Extraction, Interview Module, React Overlays, REST APIs |
| **Viplove Tyagi**     | BiLSTM, NN Dense (Resume Classification), Video Analysis (DeepFace, OpenCV)   |

---

## ⚖️ Licenses & Attributions

This project utilizes models and datasets that carry specific licensing requirements:

* **AI/ML Models:** The core models for Resume Classification were developed and provided by [vipplovve/ResuAnalyz](https://github.com/vipplovve/ResuAnalyz) under the MIT License.
* **Mixed Dataset Licensing & Restrictions:** The machine learning models integrated from `ResuAnalyz` were trained using datasets with varying licenses:
  * **IT Career Proficiency Dataset:** Licensed under CC BY 4.0 (Commercial use permitted with attribution).
  * **Resume Dataset:** Licensed under **CC BY-NC 4.0 (Non-Commercial use ONLY)**.
* **Commercialization Notice:** Because the resume classification features rely on the CC BY-NC 4.0 dataset, those specific features **CANNOT be used for commercial purposes or monetized**. Any future commercialization of the MockVue platform will require isolating, replacing, or completely retraining the models tied to the non-commercial data.
