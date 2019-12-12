## 環境建立
#### Python虛擬環境建立
```
conda create -n AVM_instruction python=3.7
conda activate AVM_instruction
```

#### 安裝課程所使用相關套件
```
conda install jupyter

conda install pandas

conda install xlrd

conda install seaborn

conda install scikit-learn

conda install statsmodels
```

#### 因為Statsmodels與Scipy 1.3.0版本目前有衝突，所以將版本調降為1.2.0
```
conda install scipy=1.2.0
```

#### 啟動jupyter notebook伺服器
```
# 切換至下載檔案目錄所在位置
jupyter notebook
```
## LICENSE
[01_training_clean_housing_data_for_1212.ipynb](https://drive.google.com/open?id=1QFUygJfnCQNvMI7V9AMe3V7P2K8yKwHT)

[corr_1212_r.ipynb](https://drive.google.com/open?id=1SUeQMZdpab_HVbzJ29JNpPt_5TRrKv2b)

[regression.ipynb](https://drive.google.com/open?id=1BaPZoXLaydg5eUY4QpCau1_fIWCfXIQA)

[raw_data_1212.csv](https://drive.google.com/open?id=1FXQvRhU-O_bhI_t5ZZovSMUrdulxJlTE)

[cleaned_taoyuan_data_1212_r.csv](https://drive.google.com/open?id=1gt8XpvPgVO8EredEG9JKbjhTa61B6g97)
