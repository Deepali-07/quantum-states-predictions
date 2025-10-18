# Quantum State Energy Predictor 🧪💻

**Predict quantum energy states using machine learning, visualize trends, and interact with an interactive demo!**  

---

## 🔍 Project Overview
This project combines **physics** and **machine learning** to predict energy levels of a particle in a **one-dimensional quantum box**.  

Given physical parameters:  

- **Box length (`L`)**  
- **Particle mass (`m`)**  
- **Quantum number (`n`)**  

the model predicts the discrete **energy state (`E`)** of the system.  

We generate a **synthetic dataset** using the quantum mechanics formula:  

\[
E_n = \frac{n^2 h^2}{8 m L^2}
\]

where `h` is Planck's constant. The project also includes a **Gradio interactive demo** to input parameters and instantly visualize predictions.

---

## 🎯 Motivation
- Showcase **AI/ML applied to physics concepts**.  
- Demonstrate how ML can **approximate real-world physical systems**.  
- Build a **portfolio-ready project** combining **data generation, modeling, visualization, and interactive demo**.  

---

## ⚡ Features

### Core Features
- **Synthetic Dataset Generation** – Create realistic quantum energy samples with small noise.  
- **ML Models** – Compare Linear Regression, Random Forest, and Neural Networks.  
- **Model Evaluation** – Evaluate using MSE and R²; automatically select the best model.  
- **Prediction** – Predict quantum energy for any combination of `L`, `m`, and `n`.  

### Extensions
- **Interactive Gradio Demo** – Input parameters and get energy predictions + dynamic visualization.  
- **Energy Visualization** – Shows energy vs box length trend with input highlighted.  
- **Symbolic Regression (Optional)** – AI can rediscover the quantum formula automatically.  
- **Wavefunction CNN (Optional)** – Predict the shape of the wavefunction ψ(x) for a 1D box.  

---

## 🛠 Tech Stack
- **Python** – Core programming language  
- **NumPy, Pandas** – Data handling and processing  
- **Scikit-learn** – ML models (Linear Regression, Random Forest, Neural Network)  
- **Matplotlib / Plotly** – Visualization  
- **Gradio** – Interactive demo  
- **joblib** – Model and scaler serialization  

---

## 🏗 Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/quantum-states-prediction.git
cd quantum-states-prediction

### 2️⃣ Create Virtual Environment
python -m venv env
# Activate environment
# Windows:
env\Scripts\activate
# Mac/Linux:
source env/bin/activate

### 3️⃣ Install Dependencies
pip install -r requirements.txt

### 4️⃣ Run the notebook

Open quantum_states.ipynb in Jupyter or VSCode.

Run all cells to generate dataset, train models, and test predictions.

### 5️⃣ Launch the interactive Gradio demo
# In the notebook
demo.launch()

👩‍💻 Author
Deepali Madala
