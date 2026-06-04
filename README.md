##🧬  AI-Powered-DNA-Variant-Analyzer

An intelligent web application that predicts whether a genetic mutation is likely to be disease-causing or harmless using advanced genomic AI models and publicly available clinical databases.

## 📌 Project Overview

Genetic mutations can significantly impact human health. Identifying whether a mutation is pathogenic or benign is an important task in genomic research and precision medicine.

This project combines artificial intelligence with genomic databases to provide quick and user-friendly mutation analysis through a modern web interface.

## ✨ Features

* Predict pathogenic or benign DNA variants
* Analyze mutations using AI-based genomic models
* Compare predictions with ClinVar classifications
* Search variants by gene or chromosome
* View confidence scores for predictions
* Support for multiple genome assemblies
* Interactive and responsive user interface
* GPU-accelerated inference for faster results

## 🏗️ System Architecture

Frontend (Next.js)
↓
FastAPI Backend
↓
Genomic AI Model
↓
ClinVar & Genome APIs

## 🛠️ Technology Stack

### Backend

* Python 3.12
* FastAPI
* Modal
* Evo2 Genomic Model
* ClinVar API
* UCSC Genome Browser API

### Frontend

* Next.js
* React
* TypeScript
* Tailwind CSS
* Shadcn UI

## 🚀 Installation

### Clone Repository

```bash
git clone <your-repository-url>
cd variant-pathogenicity-analyzer
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

Application will be available at:

```bash
http://localhost:3000
```

## 📊 Workflow

1. Enter a DNA mutation.
2. Submit for analysis.
3. AI model evaluates mutation impact.
4. Results are compared with clinical databases.
5. Prediction and confidence score are displayed.

## 🎯 Future Improvements

* Support for batch mutation analysis
* Variant visualization dashboards
* Additional genomic databases
* Downloadable analysis reports
* User authentication and history tracking

## 👨‍💻 Author

Souvik Chakraborty

B.Tech Computer Science Graduate

Data Analytics & AI Enthusiast
