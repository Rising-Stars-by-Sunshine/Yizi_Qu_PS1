# Stata Data Analysis Guide

## Overview
This repository contains **Stata `.dta` data files** and scripts for analyzing **parental absence and child development**. Follow these instructions to configure and run the analysis in both **local** and **cloud environments**.

---

## 1. System Requirements

### 1.1 Local Machine Setup

#### **Supported Operating Systems**
- **Windows 10/11** (64-bit)
- **macOS 10.14 or later**
- **Linux** (Ubuntu 18.04+, RHEL, CentOS)

#### **Required Software**
- **Stata 15 or later** (SE or MP recommended for large datasets)
- **R (optional)** for statistical analysis
- **Python (optional)** for automation via `pystata`

#### **Dependencies**
To ensure Stata commands run correctly, install:
```stata
ssc install estout, replace
ssc install outreg2, replace
ssc install asdoc, replace
