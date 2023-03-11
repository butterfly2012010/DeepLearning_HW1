# **Deep Learning HW1**
## **Perceptron**
Step 1. 利用OpenCV讀入彩色BGR圖片，對其利用color histogram抽取特徵，將每一張圖片的特徵攤平。

Step 2. 將攤平後的特徵利用sklearn中的Perceptron訓練。

Step 3. 訓練完成後，使用top-1 accuracy與top-5 accuracy評估模型表現。

## **XGBoost**
Step 1. 利用OpenCV讀入彩色BGR圖片，對其利用color histogram抽取特徵，將每一張圖片的特徵攤平。

Step 2. 將攤平後的特徵利用xgb中的分類模型訓練。

Step 3. 訓練完成後，使用top-1 accuracy與top-5 accuracy評估模型表現。

## **CNN**
Step 1. 利用OpenCV讀入彩色BGR圖片，並縮小圖片。

Step 2. 設置訓練資料之batch_size=32送進CNN進行訓練。

Step 3. 訓練完成後，使用top-1 accuracy與top-5 accuracy評估模型表現。