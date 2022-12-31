# Facemask_Detection,南華大學
人臉口罩偵測

#操作步驟
1.使用預先已經訓練的 model 來取得分類器
2.必須匯入以下的模組
import albumentation as A
import torch
import cv2
import numpy
3.載入 已經訓練好的 facemask_detection model
4.以 openCV 讀取要偵測的圖片 並轉為 RGB 格式
5.將圖片變數轉換成 facemask-detection 模組可以辨識的格式
6.將轉換後的圖片輸入資料(張量: tensor) 傳給 facemask-detection的 model來偵測

#參考資料:
https://hackmd.io/@L-W7DgKMR_G7ZX3wGcC3Zw/SyoY8ZdVs
https://pypi.org/project/facemask-detection/
