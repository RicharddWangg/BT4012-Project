# BT4012 Fraud Detection Project

This repository contains the complete implementation for our BT4012 Fraud Analytics project.  
It includes an end-to-end fraud detection pipeline covering:

- Data preprocessing  
- Feature engineering  
- Feature Selection
- Model training and hyperparameter tuning
- Ensemble modeling (stacking and blending)  
- Performance evaluation  

All plots, models (except the Random Forest model >100MB), and ensemble artifacts are provided in this repository.


## 📥 Dataset Download

The dataset is too large to host directly on GitHub.  
Please download it here:

🔗 **Dataset Download:**  
https://www.kaggle.com/datasets/kartik2112/fraud-detection

After downloading, place the dataset inside:
/data/train.csv
/data/test.csv


## ⚠️ Important: Update File Paths in Notebook

If the notebook contains Google Colab paths such as ```"/content/drive/MyDrive/BT4012/train.csv"```, please change them to ```"./data/train.csv"``` or whichever local path you choose.

Search for any paths containing ```/content/drive/MyDrive/``` and update them accordingly with **your own local path**.


## 🚀 Running the Project
1. Install dependencies <br>
```pip install -r requirements.txt```

2. Download the dataset <br>
Place ```fraudTrain.csv``` and ```fraudTest.csv``` into ```./data/```

3. Open the notebook <br>
```notebooks/BT4012_Project_Notebook.ipynb```

And run all cells top-to-bottom.