# ML Playground

This repository is my personal space to learn and practice **Machine Learning (ML)** and **Deep Learning (DL)** step by step.  
I will be following a structured roadmap and saving all code, notebooks, and mini-projects here.

## 🚀 How to Use
- All coding will be done in **Google Colab** (no local setup required).
- Datasets and models will be stored in my Google Drive under `ml-playground/`.
- Notebooks are organized in the `notebooks/` folder.

To run any notebook:
1. Open it in Google Colab.
2. Mount Google Drive:
   ```
   from google.colab import drive
   drive.mount('/content/drive')
   ```
4. Change directory to this repo folder:
   ```
   import os
   os.chdir("/content/drive/MyDrive/ml-playground")
   ```
5. Run the cells normally.

## 📂 Folder Structure

```
ml-playground/
│
├── data       ── Raw & processed datasets
├── notebooks  ── Colab notebooks (step-by-step learning)
├── src        ── Reusable Python scripts/functions
├── models     ── Trained model files (checkpoints, weights)
├── reports    ── Analysis, results, documentation
└── README.md  ── Project overview
```



## 🛠️ Dependencies
Most libraries are already available in Colab:
- Python 3.10+
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- PyTorch
- TensorFlow
- Hugging Face
If anything is missing, install it inside Colab:
  !pip install <package_name>

