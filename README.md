# Hemoglobin-Recommendation-Model
환자 검진 데이터를 바탕으로 HB수치를 예측하고 조혈제 처방 용량을 추천하는 모델

## Null data Imputation Preprocessing
- 시계열 데이터에 null data를 처리하는 방법으로 해당 feature의 Mean데이터와 생성 모델인 Denoising AutoEncoder를 사용
- Denoising AutoEncoder : 9.0 Data Generation Model.ipynb, 99. Mean_Scaler_DataCreation.ipynb

## Prediction Model
- GRU : 3.0 (Mean) Prediction Model.ipynb
- Sequence Attention GRU : 9.0 (Mean) Attn Prediction Model.ipynb

## Recommendation Model
- MLP

## Research Architerture
![image](https://user-images.githubusercontent.com/37866322/101493116-f5705200-39a8-11eb-91bf-4c5712558cae.png)

## Feature Importance
![image](https://user-images.githubusercontent.com/37866322/102145038-ed814800-3ea9-11eb-8fd5-e8c2c2e5d1f6.png)

## Result
![image](https://user-images.githubusercontent.com/37866322/102145920-73ea5980-3eab-11eb-80da-787a459b8993.png)
![image](https://user-images.githubusercontent.com/37866322/102145950-84023900-3eab-11eb-8d48-2141a42d6f89.png)
![image](https://user-images.githubusercontent.com/37866322/102146019-a09e7100-3eab-11eb-8987-8f133642c0a4.png)
