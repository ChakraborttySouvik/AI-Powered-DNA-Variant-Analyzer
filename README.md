# 🧬 AI-Powered DNA Variant Analyzer

Predict the pathogenicity of genetic mutations using advanced AI models and clinical genomic databases.

![Project Screenshot](./assets/dashboard.png)

## 🚀 Overview

AI-Powered DNA Variant Analyzer is a full-stack bioinformatics application that helps identify whether a DNA mutation is potentially disease-causing or benign.

The application integrates genomic AI models with publicly available clinical databases to provide fast and accurate mutation analysis through an intuitive web interface.

## ✨ Features

* 🧬 DNA mutation pathogenicity prediction
* ⚖️ AI prediction vs ClinVar comparison
* 📊 Confidence score generation
* 🔍 Gene and chromosome search
* 🌍 Genome assembly support
* 🧪 Clinical variant exploration
* ⚡ GPU-accelerated inference
* 📱 Responsive modern UI

## 🏗️ Architecture

```text
Frontend (Next.js)
       │
       ▼
FastAPI Backend
       │
       ▼
AI Genomic Model
       │
       ├── ClinVar API
       └── UCSC Genome API
```

## 🛠️ Tech Stack

### Backend

* Python 3.12
* FastAPI
* Modal
* Evo2
* ClinVar API
* UCSC Genome Browser API

### Frontend

* Next.js
* React
* TypeScript
* Tailwind CSS
* Shadcn UI

## 📂 Project Structure

```text
AI-Powered-DNA-Variant-Analyzer/
│
├── backend/
├── frontend/
├── assets/
├── README.md
└── requirements.txt
```

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/your-username/AI-Powered-DNA-Variant-Analyzer.git
cd AI-Powered-DNA-Variant-Analyzer
```

### Backend Setup

```bash
cd backend

uv venv --python 3.12
source .venv/bin/activate

uv pip install -r requirements.txt

modal setup
modal run main.py
```

### Frontend Setup

```bash
cd frontend

npm install
npm run dev
```

Application will run at:

```text
http://localhost:3000
```

## 🔬 How It Works

1. Enter a DNA mutation.
2. Submit the mutation for analysis.
3. AI model evaluates its potential impact.
4. Results are compared with ClinVar records.
5. Prediction, confidence score, and variant details are displayed.
<img width="1717" height="916" alt="kk" src="https://github.com/user-attachments/assets/6b5e33b9-fcb2-412e-89b4-99cf205e54f6" />

## 📈 Future Enhancements

* Batch variant analysis
* PDF report generation
* User authentication
* Variant history tracking
* Additional genomic databases
* Enhanced visualization tools

## 👨‍💻 Author

**Souvik Chakraborty**

B.Tech Computer Science Engineer

Data Analytics & Artificial Intelligence Enthusiast

### Connect

* GitHub: https://github.com/ChakraborttySouvik
* LinkedIn: https://www.linkedin.com/in/souvik-chakraborty-977b74217/
