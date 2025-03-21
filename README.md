
## Introduction
This repository contains files of a trained large language model (LLM) as part of a pilot experiment. Implemented in Python using PyTorch and Hugging Face libraries.

---

## System Requirements
### Operating Systems
- Tested on **Ubuntu 22.04 LTS** and **Windows 10/11** (x86_64)

### Software Dependencies
| Package       | Version  | Installation Command          |
|---------------|----------|--------------------------------|
| Python        | 3.9+     | `sudo apt install python3.9`   |
| PyTorch       | 2.0+     | `pip install torch`            |
| Transformers  | 4.30+    | `pip install transformers`     |
| CUDA Toolkit  | 11.8+    | [CUDA Download](https://developer.nvidia.com/cuda-11-8-0-download-archive) |

### Hardware
| Component     | Minimum              | Recommended           |
|---------------|----------------------|-----------------------|
| GPU           | NVIDIA 12GB VRAM     | Multi-GPU (A100/A10)  |
| RAM           | 16GB                 | 64GB+                 |
| Storage       | 100GB HDD            | 1TB NVMe SSD          |

---

## Installation
```bash
# Clone repository
git clone https://github.com/yourusername/llm-preliminary-experiment.git
cd llm-preliminary-experiment

# Install dependencies
pip install -r requirements.txt

# Verify installation
python -c "import torch; print(f'PyTorch {torch.__version__}, CUDA {torch.version.cuda}')"

## AUC-ROC Curve
![AUC-ROC Curve](./docs/images/auc_curve.png)  
- AUC: 0.98
