# 📘 02_Classification: 지도 학습 기반 분류 및 회귀 실습

분류(Classification) 및 회귀(Regression) 문제 해결을 위한 지도 학습 기법을 다양한 모델로 실습합니다.  
여러 알고리즘 간의 성능 비교와 모델 최적화 과정을 체험할 수 있습니다.

## 📄 실습 목록

### ➊ [ML 모델 비교 실습 (Model Comparison)](https://colab.research.google.com/github/Dropthe-bit/ai_portfolio/blob/main/02_Classification/2_1_machine_learning1_comparison.ipynb)
- 혼동행렬과 ROC-AUC를 활용한 분류 성능 평가 실습  
- 정규화 / 표준화 전처리 방식의 차이 비교  

<details>
<summary>📚 포함된 실습 항목 보기</summary>

- 혼동 행렬 생성 (`confusion_matrix`)  
- 성능 지표 계산: Accuracy, Precision, Recall, F1 Score  
- ROC Curve 및 AUC 시각화 (`roc_curve`, `auc`)  
- 변수 표준화 (`StandardScaler`) 및 정규화 (`MinMaxScaler`) 적용  
- 정규화/표준화 비교 시각화  

</details>

---

### ➋ [분류 모델 학습 및 평가 (Classifier)](https://colab.research.google.com/github/Dropthe-bit/ai_portfolio/blob/main/02_Classification/2_2_maching_learning1_classifier.ipynb)
- 분류 문제에서 여러 모델 비교 및 성능 분석
- Confusion Matrix, Accuracy, Recall, Precision 등 지표 확인

<details>
<summary>📚 포함된 실습 항목 보기</summary>

- 의사결정나무, 로지스틱 회귀 등 분류 모델  
- Confusion Matrix, Accuracy 등 평가 지표  
- 다중 클래스 분류 예제  
- 모델 예측 결과 비교 시각화  
</details>

---

### ➌ [회귀 모델 학습 및 비교 (Regressor)](https://colab.research.google.com/github/Dropthe-bit/ai_portfolio/blob/main/02_Classification/2_3_machine_learning1_regressor.ipynb)
- 회귀 문제에 다양한 모델 적용 및 비교
- 회귀 지표(MAE, MSE, R² 등) 기반 모델 평가

<details>
<summary>📚 포함된 실습 항목 보기</summary>

- 회귀 기반 ML 모델 (`LinearRegression`, `SVR`, `RandomForestRegressor`)  
- 성능 지표: MAE, MSE, RMSE, R²  
- 예측 결과 시각화  
- 모델 해석 및 비교 분석  
</details>
