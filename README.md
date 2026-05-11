BioStructNet 🧬

An advanced AI-powered protein secondary structure prediction platform built using Deep Learning, FastAPI, and modern web technologies. ProteinFoldAI predicts protein secondary structures from amino acid sequences using hybrid neural network architectures and provides interactive visualization, confidence analysis, and real-time predictions.

🚀 Overview

ProteinFoldAI is a modernized and production-ready reimplementation of traditional protein secondary structure prediction systems. The platform combines Convolutional Neural Networks (CNNs), BiLSTM sequence modeling, and explainable AI techniques to analyze protein sequences and classify residues into structural categories such as:

H → Alpha Helix
E → Beta Sheet
C → Coil

The project transforms classical academic research pipelines into a scalable web-based AI platform with visualization dashboards, API support, and deployment-ready architecture.

✨ Features
AI & Bioinformatics
Protein secondary structure prediction
3-state and 8-state prediction modes
CNN + BiLSTM hybrid architecture
Sequence preprocessing pipeline
Padding and masking support
Confidence score prediction
Explainable AI visualization
Web Platform
Interactive prediction dashboard
FASTA file upload support
Real-time inference API
Responsive modern UI
Dark mode support
Prediction history system
Visualization
Residue-level prediction highlighting
Confidence heatmaps
Sequence probability graphs
Interactive protein analysis dashboard
Engineering
FastAPI backend
Next.js frontend
Modular architecture
Docker support
REST API endpoints
Deployment-ready structure
🧠 AI Architecture

The prediction engine uses a hybrid deep learning pipeline:

Input Sequence
      ↓
Embedding Layer
      ↓
CNN Feature Extraction
      ↓
BiLSTM Sequence Learning
      ↓
Attention Layer
      ↓
Dense Classification Head
      ↓
Secondary Structure Prediction

The model learns local amino acid patterns using CNN layers and long-range sequence dependencies using BiLSTM layers.

🏗️ Project Structure
ProteinFoldAI/
│
├── backend/
│   ├── api/
│   ├── models/
│   ├── preprocessing/
│   ├── training/
│   └── utils/
│
├── frontend/
│   ├── components/
│   ├── pages/
│   ├── services/
│   └── styles/
│
├── datasets/
│
├── notebooks/
│
├── docker/
│
├── docs/
│
├── tests/
│
└── README.md
⚙️ Tech Stack
AI & Backend
Python
TensorFlow / Keras
FastAPI
NumPy
Pandas
Scikit-learn
Frontend
Next.js
React
TailwindCSS
Chart.js / Plotly
Deployment
Docker
Vercel
Render
📊 Dataset

The model is trained using benchmark protein datasets including:

CullPDB
CB513

Protein sequences are transformed into numerical feature representations for deep learning training and evaluation.

🔥 API Endpoints
Predict Protein Structure
POST /predict
Request
{
  "sequence": "MKWVTFISLLFLFSSAYSRGVFRR"
}
Response
{
  "prediction": "HHHHHCCCCEEECCCHHHHCCC",
  "confidence": [0.98, 0.95, 0.93]
}
💻 Installation
Clone Repository
git clone https://github.com/yourusername/ProteinFoldAI.git
cd ProteinFoldAI
Backend Setup
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
Frontend Setup
cd frontend
npm install
npm run dev
🐳 Docker Deployment
docker-compose up --build
📈 Future Improvements
Transformer-based protein models
Protein mutation impact analysis
Tertiary structure estimation
Protein similarity search
AI-powered research assistant
Cloud GPU inference
Mobile application support
🎯 Use Cases
Computational Biology
Drug Discovery
Bioinformatics Research
Healthcare AI
Academic Deep Learning Research
📸 Screenshots

Coming Soon...

🤝 Contribution

Contributions, feature suggestions, and pull requests are welcome.

📄 License

This project is licensed under the MIT License.

🙌 Acknowledgements

Inspired by previous academic research and open-source work in protein secondary structure prediction using deep learning architectures.

⭐ Support

If you found this project useful, consider giving it a star on GitHub.
