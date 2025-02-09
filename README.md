# System Configuration Report

## Overview
This document provides details on the system's hardware and software configuration, including CPU, memory, storage, Python environment, and installed packages. This configuration is useful for replicating the research environment.

---

## 1. System Specifications

### **1.1 CPU Information**
- **Architecture:** x86_64
- **CPU Model:** Intel(R) Xeon(R) CPU @ 2.00GHz
- **Total Cores:** 96
- **Threads per Core:** 2
- **Sockets:** 2
- **L1 Cache:** 1.5 MiB (48 instances)
- **L2 Cache:** 48 MiB (48 instances)
- **L3 Cache:** 77 MiB (2 instances)
- **Virtualization:** KVM (Full Virtualization)

### **1.2 Memory**
- **Total Memory:** 334 GiB
- **Available Memory:** 329 GiB
- **Swap Memory:** 0B

### **1.3 GPU Information**
- **No GPU detected**.

### **1.4 Disk Space**
| Filesystem  | Size  | Used | Available | Usage % |
|-------------|------|------|-----------|---------|
| Root (/)   | 226G  | 17G  | 210G      | 8%      |
| `/var/colab` | 168G | 344K | 168G     | 1%      |
| `/etc/hosts` | 233G | 29G  | 204G     | 13%     |

---

## 2. Python Environment

### **2.1 Python Version**
- **Python 3.11.11**

### **2.2 Installed Packages**
The system includes a variety of installed Python packages for **data analysis, machine learning, and deep learning**. Some notable packages include:

- **Data Processing:** `pandas`, `numpy`, `scipy`
- **Machine Learning:** `scikit-learn`, `tensorflow`, `torch`
- **Natural Language Processing:** `transformers`, `nltk`, `spacy`
- **Visualization:** `matplotlib`, `seaborn`, `plotly`

To see all installed packages, run:
```bash
pip list
