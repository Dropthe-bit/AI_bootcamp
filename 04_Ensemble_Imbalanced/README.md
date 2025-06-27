# 📘 04_Ensemble_Imbalanced: 앙상블 & 불균형 데이터 실습

앙상블 기반 모델링 기법과 불균형/이상치 데이터를 다루는 다양한 머신러닝 기법을 실습합니다.  
교차 검증, 부스팅 계열 모델, 불균형 샘플링, 이상 탐지, AutoML까지 단계별로 학습합니다.

## 📄 실습 목록

### ➊ [교차 검증 (Cross Validation)](https://colab.research.google.com/github/your_repo/4_1_machine_learning3_cross_validation.ipynb)
- 다양한 교차 검증 기법 (`KFold`, `StratifiedKFold`, `GroupKFold`) 비교  
- 모델별 분산/정확도 분석 및 평균 성능 확인  
- 교차검증 기반 모델 평가 자동화 실습  

<details>
<summary>📚 포함된 실습 항목 보기</summary>

- `train_test_split`, `cross_val_score`, `cross_validate` 사용법  
- 모델 성능 비교 시 `mean`, `std` 활용  
- `Pipeline`과 교차검증 결합  
- 분류/회귀 문제 모두 대응  
</details>

---

### ➋ [부스팅 모델 실습 (Boosting Models)](https://colab.research.google.com/github/your_repo/4_2_machine_learning3_boosting.ipynb)
- `Gradient Boosting`, `XGBoost`, `LightGBM`, `CatBoost` 모델 성능 비교  
- SHAP 값 시각화로 변수 중요도 분석  
- `optuna` 및 `GridSearchCV` 기반 하이퍼파라미터 튜닝  

<details>
<summary>📚 포함된 실습 항목 보기</summary>

- `early_stopping_rounds` 실습  
- SHAP을 통한 해석 가능한 머신러닝  
- `optuna` 튜너와의 통합 실험  
- 모델별 학습 속도 및 성능 비교 시각화  
</details>

---

### ➌ [ML 프로젝트 통합 실습](https://colab.research.google.com/github/your_repo/4_3_machine_learning3_project_sol.ipynb)
- 전처리부터 모델 튜닝까지 통합된 ML 파이프라인 실습  
- `ColumnTransformer`, `Pipeline`, `GridSearchCV` 활용  
- 종합 성능 평가 (`classification_report`, `confusion_matrix`)  

<details>
<summary>📚 포함된 실습 항목 보기</summary>

- 범주형/수치형 변수 분리 처리  
- 전처리 + 모델 파이프라인 통합  
- 하이퍼파라미터 튜닝 최종 평가  
</details>

---

### ➍ [불균형 데이터 처리 (Imbalanced Data)](https://colab.research.google.com/github/your_repo/4_4_machine_learning4_imbalance.ipynb)
- `SMOTE`, `RandomOverSampler`, `UnderSampler` 등 샘플링 기법 실습  
- 불균형 상황에서의 모델 평가 지표 분석 (F1, AUC 등)  
- 모델 내부의 class_weight 활용 전략  

<details>
<summary>📚 포함된 실습 항목 보기</summary>

- `imbalanced-learn` 사용법  
- 샘플링 전/후 성능 비교  
- confusion matrix 중심 불균형 평가  
</details>

---

### ➎ [이상치 탐지 (Anomaly Detection)](https://colab.research.google.com/github/your_repo/4_5_machine_learning4_anomaly.ipynb)
- `Isolation Forest`, `One-Class SVM`, `Elliptic Envelope` 모델 비교  
- 이상 탐지 결과 시각화 및 비율 조정 실험  
- 비지도 학습 기반 이상 탐지 적용  

<details>
<summary>📚 포함된 실습 항목 보기</summary>

- 이상치 threshold 조정 시 정확도/재현율 변화  
- 이상 탐지 vs 지도 학습 비교  
- `decision_function` 시각화  
</details>

---

### ➏ [AutoML 실습 (PyCaret & H2O)](https://colab.research.google.com/github/your_repo/4_6_machine_learning4_automl.ipynb)
- `PyCaret`, `H2O AutoML` 기반 자동 머신러닝 실습  
- `compare_models`, `tune_model`, `get_leaderboard()` 등 핵심 함수 실습  
- 모델 저장 및 재활용 (`save_model`, `load_model`)  

<details>
<summary>📚 포함된 실습 항목 보기</summary>

- PyCaret으로 빠른 모델링 자동화  
- H2O로 고성능 AutoML 대시보드 연동  
- 성능 평가 및 모델 불러오기 실습  
</details>
