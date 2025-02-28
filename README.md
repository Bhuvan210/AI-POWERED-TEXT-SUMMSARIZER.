# AI-POWERED-TEXT-SUMMSARIZER.
 
An **AI-driven text summarization tool** available as a **website, mobile app, and API**, designed to generate **concise and context-aware** summaries of large texts.  

## 🌟 **Features**  
✅ **AI Summarization** – Generate summaries using **GPT-4, BERT, and other NLP models**.  
✅ **Multi-Format Support** – Summarize **plain text, PDFs, and web pages**.  
✅ **Voice Summarization** – Convert **speech to text** and summarize.  
✅ **Customizable Summaries** – Choose **summary length & style**.  
✅ **Cross-Platform** – Available as a **Web App, Mobile App (React Native), and API**.  

---

## 🛠️ **Tech Stack**  

### **🌐 Frontend (Next.js)**  
- **Framework:** Next.js (React-based)  
- **UI Library:** Tailwind CSS + shadcn/ui  
- **State Management:** React Hooks (useState, useEffect)  
- **Authentication:** Firebase/Auth0  
- **Deployment:** Vercel  

### **🚀 Backend (FastAPI)**  
- **Framework:** FastAPI (Python)  
- **Database:** PostgreSQL / Firebase Firestore  
- **AI Model Integration:** Hugging Face Transformers / OpenAI API  
- **Authentication:** JWT / Firebase Auth  
- **Deployment:** AWS / GCP  

### **📱 Mobile App (React Native)**  
- **Framework:** React Native  
- **UI Library:** NativeBase / Tailwind CSS  
- **State Management:** Redux / Zustand  
- **OCR & Speech-to-Text:** Google ML Kit / OpenAI Whisper  
- **Storage:** AsyncStorage + Firebase Firestore  
- **Deployment:** Expo / Native Build Tools  

---

## 🔧 **Installation & Setup**  

### **1️⃣ Backend (FastAPI)**  
```sh
git clone https://github.com/your-repo/ai-summarizer.git
cd ai-summarizer/backend
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
uvicorn main:app --reload
```

### **2️⃣ Frontend (Next.js)**  
```sh
cd ../frontend
npm install
npm run dev
```

### **3️⃣ Mobile App (React Native)**  
```sh
cd ../mobile
npm install
npx expo start
```

---

## 📌 **API Endpoints (FastAPI)**  

| Method | Endpoint           | Description                     |
|--------|--------------------|---------------------------------|
| `POST` | `/summarize`       | Summarize input text           |
| `POST` | `/summarize/pdf`   | Summarize content from a PDF   |
| `POST` | `/summarize/url`   | Summarize a web page           |
| `POST` | `/summarize/audio` | Convert speech to text & summarize |
| `GET`  | `/health`         | Check API status               |

---

## 🌍 **Deployment**  

### 🚀 **Frontend**  
```sh
npm run build && vercel deploy
```

### 🔧 **Backend**  
```sh
docker-compose up --build
```
**Hosting:** AWS EC2 / GCP  

### 📱 **Mobile App**  
```sh
eas build --profile production
```
**Distribution:** Google Play Store & Apple App Store  

---

## 🤝 **Contribution**  

Want to contribute? Follow these steps:  

1. **Fork** the repository.  
2. **Create a new branch** (`git checkout -b feature-branch`).  
3. **Commit your changes** (`git commit -m "Added new feature"`).  
4. **Push to your branch** (`git push origin feature-branch`).  
5. **Submit a Pull Request** for review.  

---

## 📜 **License**  
This project is licensed under the **MIT License**.  

---

## 📞 **Contact**  
For any queries, reach out at **chbhuvan235@gmail.com**
---
