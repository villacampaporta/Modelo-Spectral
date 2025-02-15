# 📡 Modelo-Spectral: Synthetic Data Generation for Dielectric Characterization  

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)  
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  

## 📌 Project Overview  

This repository contains the implementation used for the research project:  

**"Synthetic Data Generation for Machine Learning Models Oriented to the Dielectric Characterization of Liquids Using a Dielectric Resonator"**  

- **Author:** Javier Villacampa Porta  
- **Supervisors:** Miguel Monteagudo Honrubia & Francisco Javier Herraiz Martínez  
- **Institution:** ICAI – Universidad Pontificia Comillas  

### 📖 Abstract  

This study evaluates and compares **TVAE** and **CTGAN** models for **synthetic data generation** to enhance machine learning models for liquid characterization. Results demonstrate that **TVAE outperforms CTGAN** in terms of efficiency, data quality, and predictive accuracy, making it a superior choice for dielectric characterization tasks.  

**Keywords:** Deep Learning, Dielectric Resonator Sensor, Synthetic Data Generation (SDG), Variational Autoencoder (VAE), Generative Adversarial Networks (GAN)  

---

## 🚀 Features  

✅ **Synthetic Data Generation:** Leverages **TVAE & CTGAN** to generate high-quality synthetic data for dielectric characterization  
✅ **Machine Learning Pipeline:** Implements **SVM, SVR, PCA, and data preprocessing** for predictive modeling  
✅ **Performance Benchmarking:** Evaluates models using **f1-score, RMSE, and accuracy**  
✅ **Visualization Tools:** Interactive **seaborn, matplotlib, and Plotly** visualizations  
✅ **Data Profiling & Optimization:** Monitors **memory usage and performance**  

---

## 📂 Repository Structure  

```bash
📦 Modelo-Spectral
│-- 📁 data/                  # Raw & processed datasets
│-- 📁 notebooks/             # Jupyter Notebooks for analysis
│-- 📁 models/                # Trained models & synthetic data
│-- 📁 reports/               # Research findings & documentation
│-- 📁 src/                   # Main codebase
│   ├── data_processing.py    # Data import & preprocessing
│   ├── synthetic_generation.py  # TVAE & CTGAN model implementation
│   ├── ml_models.py          # SVM & PCA-based ML models
│   ├── visualization.py      # Data visualization functions
│   ├── evaluation.py         # Model performance evaluation
│-- README.md                 # Project documentation
│-- requirements.txt          # Dependencies
│-- LICENSE                   # License information
```

## 🛠 Setup & Installation
1️⃣ Clone the repository
```bash
git clone https://github.com/villacampaporta/Modelo-Spectral.git
cd Modelo-Spectral
```
2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```
3️⃣ Run the analysis
```bash
python src/data_processing.py
python src/synthetic_generation.py
python src/ml_models.py
python src/evaluation.py
```

## 🔬 Methodology

1️⃣ Data Preprocessing: Loads and processes dielectric characterization data

2️⃣ Synthetic Data Generation: Implements TVAE & CTGAN for generating high-quality synthetic datasets

3️⃣ Machine Learning Models: Trains and evaluates SVM, SVR, and PCA-based models

4️⃣ Performance Evaluation: Compares synthetic vs. real data effectiveness using standard metrics

5️⃣ Visualization & Reporting: Generates insights through seaborn, Plotly, and Matplotlib


## 📊 Results

🔹 TVAE outperformed CTGAN in data similarity and predictive model performance

🔹 Generated synthetic data improved classification accuracy in dielectric characterization tasks

🔹 Memory-efficient & scalable solution for real-world applications


## 📌 Key Technologies

Programming: Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly)

Machine Learning: Scikit-learn (SVM, SVR, PCA), Synthetic Data Vault (SDV)

Deep Learning: TVAE, CTGAN

Performance Monitoring: Memory profiling, computational efficiency


## 🎯 Future Work

🔹 Extend model evaluation to other dielectric resonator-based datasets

🔹 Integrate reinforcement learning for adaptive synthetic data generation

🔹 Optimize data synthesis using hybrid VAE-GAN architectures


## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.


## 🤝 Acknowledgments

Special thanks to ICAI – Universidad Pontificia Comillas for supporting this research.


## 📬 Contact

📧 Email: javier.villacampa.porta@gmail.com

🔗 LinkedIn: linkedin.com/in/javiervillacampa

🌍 GitHub: github.com/villacampaporta


🔥 If you find this project useful, give it a ⭐ and contribute!
