# 🏥 Medical NLP Pipeline - Full Stack End-to-End Demo

An advanced **Medical Natural Language Processing (NLP) Pipeline** capable of analyzing clinical conversations, extracting key medical information, generating SOAP notes, assessing sentiment, and evaluating data quality.  

✅ Fully functional demo for educational and academic purposes.  
✅ Backend & Frontend deployed.  
✅ Streamlined for live demo & assignments.

---

## 🚀 Key Features

- **Named Entity Recognition (NER)**  
  Extracts symptoms, diagnoses, treatments, temporal expressions, and more.

- **Medical Summarization**  
  Automatically summarizes clinical conversations into structured data.

- **Sentiment Analysis**  
  Detects patient emotions (anxious, hopeful, reassured, concerned, etc.).

- **SOAP Note Generation**  
  Converts the conversation into structured clinical SOAP documentation.

- **Quality Metrics**  
  Calculates entity coverage, summary completeness, SOAP completeness, and confidence scores.

---

## 📦 Tech Stack

| Layer       | Technology        |
| ----------- | ----------------- |
| Backend API | FastAPI (Python)  |
| Frontend UI | Streamlit         |
| NLP Models  | spaCy, Transformers (HuggingFace) |
| Deep Learning | PyTorch        |
| Deployment  | Docker + AWS EC2 (Backend) |
| Web Hosting | Streamlit Cloud (Frontend) |

---

## 🗂️ Project Structure

| File | Description |
| ---- | ----------- |
| `medical_nlp_pipeline.py` | NLP pipeline (NER, Summarization, Sentiment, SOAP) |
| `medical_nlp_api.py` | Backend API server (FastAPI) |
| `medical_nlp_streamlit.py` | Streamlit UI frontend |
| `requirements.txt` | Python dependencies |

---

## ⚙️ Deployment

### Backend (FastAPI)

- Deployed using Docker on AWS EC2 instance (t2.micro - Free Tier).
- Public IP accessible for frontend communication.

### Frontend (Streamlit)

- Fully deployed on Streamlit Cloud.
- Accessible globally via public URL.

---

## 🔧 Local Development

### 1️⃣ Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/medical-nlp-pipeline.git
cd medical-nlp-pipeline
````

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run Backend API (FastAPI)

```bash
python medical_nlp_api.py
```

API will be available at:

```
http://localhost:8000/docs
```

### 5️⃣ Run Frontend (Streamlit)

Update the backend URL in `medical_nlp_streamlit.py`:

Run Streamlit:

```bash
streamlit run medical_nlp_streamlit.py
```

Frontend UI will be available at:

```
http://localhost:8501
```

---

## 🌐 Live Demo (Deployment URLs)

| Component                  | URL                                                                                          |
| -------------------------- | -------------------------------------------------------------------------------------------- |
| Frontend (Streamlit Cloud) | [Frontend](https://medicalnlpapp.streamlit.app/) |
| Backend (FastAPI)          | [Backend](http://35.173.247.177:8000/)                   |

---

## 📊 Sample Use Case

* Upload or paste medical conversation text
* Pipeline analyzes & extracts medical entities
* Generates clinical summaries and SOAP notes
* Presents patient sentiment timeline
* Displays quality metrics for clinical review




