<div align="center">

# Ali Rashidi (Farid)
### Computer Vision Engineer · Data Scientist · Satellite Payload Developer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/faridrash/)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:farid.rash@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?logo=github&logoColor=white)](https://github.com/FaridRash)
[![Profile Views](https://visitcount.itsvg.in/api?id=FaridRash&icon=0&color=0)](https://visitcount.itsvg.in)

</div>

---

## 🛠️ What I Build

I'm a Computer Vision and Deep Learning Engineer with hands-on experience designing, training, and deploying end-to-end CV pipelines across **medical imaging**, **Earth Observation**, and **astronomical data**. I build systems from the physics of a sensor all the way to a deployed, containerized inference service.

**Current focus areas:**

- 🧠 **Medical Imaging** — End-to-end pipeline for brain CT hemorrhage detection and segmentation (U-Net + LLM + RAG); also training YOLOv8-seg for multimodal brain tumor segmentation across CT and MRI
- 📡 **Radio Astronomy** — CNN-based morphological classification of extragalactic radio galaxies (FR0, FRI, FRII) on ~18,000 image datasets; deployed on Google Cloud Run as a REST inference service
- 🛰️ **Satellite Payload Engineering** — Physics-aware SNR and imaging performance modelling for the **IGNIS CubeSat** (thermal IR volcano monitoring), including radiometric signal chains, FoV/footprint analysis, and mission timing optimization
- ⚡ **GPU Programming** — Low-level CUDA/C++ development on a Quadro P2000, building custom compute kernels and exploring GPU-accelerated pipelines on Linux (WSL2/Ubuntu)

---

## 🚀 Active Projects

### 🛰️ IGNIS CubeSat — Payload Department *(Supervisor)*
Leading the electro-optical payload design for a volcano-monitoring CubeSat. Built Python simulation pipelines (NumPy, SciPy, Matplotlib) to evaluate FoV, spatial resolution, and radiometric SNR under real orbital conditions. Applied anomaly detection to mission outputs, ultimately recommending a ~5-month launch postponement to improve early-mission imaging quality.

### 🧠 AI-Assisted Intracranial Hemorrhage Segmentation
Modular medical-AI pipeline combining Computer Vision, ML, LLM, and RAG for 3D CT scan analysis. Full preprocessing stack: Hounsfield Unit preservation, multi-windowing, brain extraction, 3D-to-2D slicing. U-Net trained with Dice + BCEWithLogitsLoss and balanced patch sampling to handle severe class imbalance.

### 🧬 Brain Tumor Segmentation with YOLOv8
Transfer-learning-based YOLOv8-seg model for pixel-level tumor mask generation across CT and MRI. Systematic hyperparameter tuning and augmentation for cross-modality robustness; evaluated with box/mask mAP, precision/recall, and confusion matrix analysis.

### 📡 Radio Galaxy Morphological Classification
CNN classifier for FR0/FRI/FRII radio galaxy morphologies from 50×50 greyscale images (~80–85% accuracy after class balancing and augmentation). Packaged as a Dockerized REST service and deployed on Google Cloud Run.

### ⚡ CUDA / GPU Programming
Custom CUDA kernel development in C++ targeting an NVIDIA Quadro P2000, running on Linux via WSL2 (Ubuntu). Working with CUDA 12.4 in a containerized environment (`nvcr.io/nvidia/cuda:12.4.1-devel-ubuntu22.04`) to bypass host OS compatibility constraints — a practical deep-dive into GPU memory models, kernel optimization, and low-level compute pipelines.

### 📈 Forex RL Trading Agent
DQN-based reinforcement learning agent trading EUR/USD with PyTorch. Custom state representation, stop-loss/target logic (target = 2× SL), epsilon-greedy action selection, and maximum holding period constraints.

---

## 💻 Tech Stack

**Languages**

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![Bash Script](https://img.shields.io/badge/bash_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)

**ML / DL**

![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)
![mlflow](https://img.shields.io/badge/mlflow-%23d9ead3.svg?style=for-the-badge&logo=numpy&logoColor=blue)

**GPU & HPC**

![nVIDIA CUDA](https://img.shields.io/badge/cuda-000000.svg?style=for-the-badge&logo=nVIDIA&logoColor=green)
![C++](https://img.shields.io/badge/CUDA%20C++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

**Data & Compute**

![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)

**Infrastructure & Tools**

![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white)
![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-%23FE4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=FaridRash&theme=dark&hide_border=false&include_all_commits=false&count_private=false)

![Streak Stats](https://nirzak-streak-stats.vercel.app/?user=FaridRash&theme=dark&hide_border=false)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=FaridRash&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

</div>

---

## 🤝 Open to Collaborate On

- Segmentation and detection in medical imaging (CT, MRI)
- Deep learning for astronomical image classification
- Earth observation payload design and performance modelling
- Thermal IR sensor simulation and radiometric analysis
- GPU programming, CUDA kernel development, and high-performance computing
- Reinforcement learning for financial or control systems

---

*"Build first. Understand deeply. Then build better."*
