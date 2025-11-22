# tf-learning
🔱 Terraforming with TensorFlow: A study archive on the Server (AMD EPYC + CUDA 12.9).

# 🧠 tf-learning

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=flat-square&logo=python&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-22.04-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-12.9-76B900?style=flat-square&logo=nvidia&logoColor=white)

**TensorFlow 2.x Learning Roadmap** based on official documentation.
이 레포지토리는 [TensorFlow 공식 튜토리얼](https://www.tensorflow.org/tutorials?hl=ko)과 [가이드](https://www.tensorflow.org/guide?hl=ko)를 실습하고 정리한 아카이브입니다.

<br>

## 🖥️ Environment: Server 🔱

| Hardware | Specs |
| :--- | :--- |
| **CPU** | AMD EPYC 7713 (64-Core Processor) |
| **RAM** | 503 GB |
| **GPU** | RTX 3090 (Current Driver: 575.64) |
| **OS** | Ubuntu 22.04.5 LTS |

> **Note:** `conda` 가상환경(`tutorial`)에서 `pip install "tensorflow[and-cuda]"`로 환경을 구축했습니다.

<br>

## 📂 Directory Structure

```bash
tf-learning/
├── 01_Guide/            # [이론] TensorFlow 공식 가이드 실습
│   ├── 01_Basics/       # 텐서, 변수, 자동미분 (Deep Learning 기초)
│   ├── 02_Keras_Core/   # 층(Layer), 모델링, 학습 루프
│   ├── 03_Data_Pipeline/# tf.data (고성능 데이터 파이프라인)
│   ├── 04_Performance/  # GPU 가속 및 최적화
│   └── 05_Save_Load/    # 모델 저장 및 불러오기
│
├── 02_Tutorials/        # [실전] 분야별 튜토리얼 프로젝트
│   ├── 00_Quickstart/   # 빠른 시작 (Hello World)
│   ├── 01_ML_Basics/    # ML 기초 (회귀, 기본 분류)
│   ├── 02_Vision/       # 컴퓨터 비전 (CNN, ResNet)
│   ├── 03_NLP/          # 자연어 처리 (Transformer, BERT)
│   ├── 04_Generative/   # 생성형 모델 (GAN, VAE)
│   └── 05_Structured/   # 정형 데이터 (CSV, Pandas)
│
└── README.md
```

<br>

## 📝 Study Log

| Date | Chapter | Topic | Status |
| :---: | :--- | :--- | :---: |
| 2025.11.22 | Env Setup | Conda 환경 구축 및 GitHub 연동 | ✅ |
| 2025.11.23 | Basic | 텐서(Tensor)와 연산 | 🏃 |
| ... | ... | ... | 🔒 |

<br>

---
_Powered by TensorFlow 2.16+_