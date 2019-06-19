![python_vesion](https://img.shields.io/badge/Python-3.7%2B-green.svg)
[![MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/sfyc23/EverydayWechat/blob/master/LICENSE)

AVM Instruction 上課用筆記本

## 課程時間表

- 13:40~15:10 程式語言PYTHON之操作介紹與說明
  - 資源：Python_Crash_Course/
- 15:20~16:50 程式語言PYTHON之操作應用
  - 資源：Demo_code/

## 課程大綱
#### 1. 程式語言PYTHON之操作介紹與說明
- 講義：Python_Crash_Course/01_Python_Crash_Course.ipynb
- 練習：Python_Crash_Course/02_Python_Crash_Course_Exercises.ipynb
- 解答：Python_Crash_Course/03_Python_Crash_Course_Exercises - Solutions.ipynb

#### 2. 程式語言PYTHON之操作應用
- 講義：Demo_code/01_Pandas_and_Scikit-Learn.ipynb
- 講義：Demo_code/02_AVM_Model_Build_Predict.ipynb

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
[MIT License](https://zh.wikipedia.org/wiki/MIT%E8%A8%B1%E5%8F%AF%E8%AD%89)
