# 📘 04_Ensemble_Imbalanced: 앙상블 & 불균형 데이터 실습

앙상블 기반 모델링 기법과 불균형/이상치 데이터를 다루는 다양한 머신러닝 기법을 실습합니다.  
교차 검증, 부스팅 계열 모델, 불균형 샘플링, 이상 탐지, AutoML까지 단계별로 학습합니다.

## 📄 실습 목록

### ➊ [교차 검증 (Cross Validation)](https://colab.research.google.com/github/your_repo/4_1_machine_learning3_cross_validation.ipynb)
- 다양한 교차 검증 기법 (`KFold`, `Nested k-fod CV`) 실습  
- 모델별 정확도 분석 및 평균 성능 확인  

---

### ➋ [부스팅 모델 실습 (Boosting Models)](https://colab.research.google.com/github/your_repo/4_2_machine_learning3_boosting.ipynb)
- `Gradient Boosting`, `XGBoost`, `LightGBM`, `CatBoost` 모델 성능 비교  
- `GridSearchCV` 기반 하이퍼파라미터 튜닝  

<details>
<summary>📚 포함된 실습 항목 보기</summary>

- `AdaBoostClassifier` 실습  
- `GradientBoostingClassifier` 실습  
- `XGBClassifier` 실습 
- `LGBMClassifier` 실습  
- 모델별 최적의 파라미터 찾기
</details>

---

### ➌ [ML 프로젝트 통합 실습](https://colab.research.google.com/github/your_repo/4_3_machine_learning3_project_sol.ipynb)
- 전처리부터 모델 튜닝까지 통합된 ML 실습  
- `GridSearchCV`를 활용한 하이퍼파라미터 튜닝  
- 종합 성능 평가 (`classification_report`, `confusion_matrix`)  

<details>
<summary>📚 포함된 실습 항목 보기</summary>

- SECOM 반도체 불량 예측 데이터셋 로드 및 분할  
- 불균형 데이터 시각화 및 클래스 분포 확인  
- `RandomForestClassifier` 기반 모델 학습  
- `GridSearchCV`로 하이퍼파라미터 튜닝 수행  
- `classification_report`, `confusion_matrix`로 최종 평가  
</details>

---

### ➍ [불균형 데이터 처리 (Imbalanced Data)](https://colab.research.google.com/github/your_repo/4_4_machine_learning4_imbalance.ipynb)
- `SMOTE`, `RandomOverSampler`, `RandomUnderSampler` 등 샘플링 기법 실습  
- 불균형 상황에서의 모델 평가 지표 분석

<details>
<summary>📚 포함된 실습 항목 보기</summary>

- `imbalanced-learn` 사용법 (`SMOTE`, `RandomOverSampler`, `RandomUnderSampler`)  
- 샘플링 전/후 성능 비교 (`confusion_matrix`, `classification_report`)  
</details>

---


### ➎ [이상치 탐지 (Anomaly Detection)](https://colab.research.google.com/github/your_repo/4_5_machine_learning4_anomaly.ipynb)
- `IsolationForest` 모델 실습
- 이상 탐지 결과 시각화 및 threshold 실험  
- 비지도 학습 기반 이상 탐지 적용  

<details>
<summary>📚 포함된 실습 항목 보기</summary>

- 이상치 threshold 수동 조정 vs contamination 자동 설정  
- `decision_function` 기반 점수 시각화   
</details>

---

### ➏ [AutoML 실습 (PyCaret & H2O)](https://colab.research.google.com/github/your_repo/4_6_machine_learning4_automl.ipynb)
- `PyCaret`, `H2O AutoML` 기반 머신러닝 실습  
- 핵심 함수 사용 예제 실습 (`compare_models`, `tune_model`)  
- 모델 저장 및 재활용 (`save_model`, `load_model`)  

<details>
<summary>📚 포함된 실습 항목 보기</summary>

- PyCaret을 이용한 분류 자동화  
- H2O 기반 AutoML 실험 및 리더보드 출력  
- 학습된 모델 저장 및 불러오기  
</details>
