# 🧠 Deep Learning Archive

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=flat-square&logo=python&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-22.04-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-12.9-76B900?style=flat-square&logo=nvidia&logoColor=white)

이 레포지토리는 **Deep Learning Frameworks (PyTorch & TensorFlow)** 의 실습 코드를 정리한 아카이브입니다.
* **PyTorch:** [혁펜하임](https://youtube.com/playlist?list=PL_iJu012NOxdhFmM2aw6bwpZTMFdsPxws&si=5OaIx4Q_GKEy7V-F) 인스톨! 파이토치를 참고해서 구현
* **TensorFlow:** 공식 가이드 및 튜토리얼 기반 실습
<br>

## 🖥️ Environment: Server 🔱

| Hardware | Specs |
| :--- | :--- |
| **CPU** | AMD EPYC 7713 (64-Core Processor) |
| **RAM** | 503 GB |
| **GPU** | RTX 3090 (Current Driver: 575.64) |
| **OS** | Ubuntu 22.04.5 LTS |

> **Conda Environments:**
> * **PyTorch:** `conda activate torch_study` (Python 3.11 + Torch 2.x)
> * **TensorFlow:** `conda activate tutorial` (Python 3.11 + TF 2.x)

<br>

## 📂 Directory Structure

```bash
deep-learning-study/
├── PyTorch/              # [Main] 혁펜하임 강의 실습 & 논문 구현
│   ├── 01_Syntax_Basic/  # 텐서 조작, 인덱싱, Autograd (기초)
│   ├── 02_Linear_Model/  # 선형/이진 회귀, 하이퍼파라미터
│   ├── 03_NN_Training/   # DataLoader, 커스텀 모듈, Dropout
│   ├── 04_CNN_Vision/    # CNN 이론, Augmentation, VGG
│   └── 05_Advanced_Tip/  # ModuleList, Parameters 제어
│
├── TensorFlow/           # [Sub] TF 공식 가이드 & 튜토리얼
│   ├── 01_Guide/         # 텐서, Keras Core, tf.data
│   └── 02_Tutorials/     # Vision, NLP, Generative Models
│
└── README.md
```

<br>

## 📝 Pytorch Study Log


| Chapter | Topic | Status | Note |
| :---: | :--- | :--- | :---: |
| 01. Syntax | 텐서 연산, 차원 조작(View/Reshape), Autograd | ✅ |  |
| 02. Linear | 선형 회귀, 이진 분류, Optimizer 수동 구현 | 🏃 |  |
| 03. Training | Dataset/DataLoader, Custom Module, Dropout | 🔒 |  |
| 04. CNN | Conv2d, Pooling, Augmentation, VGG Transfer | 🔒 |  |
| 05. Adv | nn.ModuleList, Parameter Control | 🔒 |  |


<br>

---
_Powered by PyTorch & TensorFlow on Server_