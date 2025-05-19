# 🧠 Calcium Imaging Analysis — NSC 2025 Homework 1

**An end-to-end pipeline for analyzing calcium fluorescence video data to detect neuronal activity and functional regions.**

---

## 🚀 Project Overview

This project implements a full calcium imaging data workflow:

- 📹 **Motion Correction** of raw TIF image sequences
- 🧮 **Statistical Summary Image Generation**
- 🔍 **Interactive ROI Selection & Masking**
- 📈 **Time-Trace Extraction from Fluorescence Frames**
- 🧠 **Matrix Factorization** (PCA, NMF, ICA) for neuron detection

Designed for **clarity, reproducibility**, and **scalability** in neuroscience data analysis.

---

## 🔗 Full Analysis & Code: CI_Analysis.ipynb

## Dataset Download: 

TEST_MOVIE_00001-small.tif : [LINK](https://www.dropbox.com/scl/fi/2m1rww64907h0wvlihqj2/TEST_MOVIE_00001-small-motion.tif?rlkey=pv83iulbkhwtztpuwfo3nk6a6&st=69nu7fvt&dl=0)
TEST_MOVIE_00001-small-motion.tif : [LINK](https://www.dropbox.com/scl/fi/gphia4ppq99k78zwhufgl/TEST_MOVIE_00001-small.tif?rlkey=pb8k5h5mdszhvy3ald1nl9qzv&st=cj7qbw55&dl=0)
---

## 💡 Key Features
- Python-based pipeline using NumPy, SciPy, and scikit-learn
- Interactive ROI selection using OpenCV
- Real-time ROI visualization and trace plotting
- Comparison of PCA, NMF, and ICA for neuron extraction

---

## 🛠 Tech Stack

- Python 3.9+
- `tifffile` for multi-frame image stacks
- `OpenCV` for ROI selection
- `scikit-learn` for decomposition methods
- `matplotlib` for visualization

---

## 🧪 Summary of Tasks

| Step                        | Goal                                  |
|-----------------------------|----------------------------------------|
| 📦 Load TIF stack           | Import raw video data                 |
| 🌀 Motion correction         | Align misaligned frames               |
| 🧮 Compute summary images    | Mean, median, variance, etc.          |
| 🖱 ROI selection             | Manual seed selection & mask creation |
| 📊 Extract traces           | Time-series of activity per ROI       |
| 🧠 Decompose with PCA/NMF/ICA| Unsupervised ROI detection            |

---

## 📎 Notes

- Tested on data from `TEST_MOVIE_00001-small.tif` and `-motion.tif`
- Data not included in repo due to size — expected in same folder as script
- Modular scripts for each processing step

---
