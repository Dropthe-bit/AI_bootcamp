# 🥬 농산물 가격 예측 대시보드

Streamlit을 활용한 시계열 기반 **농산물 가격 예측 시각화 웹 앱**입니다.  
특정 품목의 과거 가격 변동 및 예측 결과를 시각화하여 확인할 수 있으며, 평균 가격의 추세선(rolling mean)도 함께 제공합니다.
<br><br><br>

## 📁 프로젝트 구조
```
├── app.py                     # Streamlit 대시보드 메인 코드
├── data/
│   ├── streamlit_data.csv     # 시각화용 전처리된 시계열 데이터
│   ├── metric_summary.csv     # 품목별 예측 정확도 요약 데이터
│   ├── train.csv              # 학습용 원본 시계열 데이터
│   └── test_2020-11-05.csv    # 테스트용 평가 데이터
├── demand_forecasting.ipynb   # 예측 모델 및 시계열 분석 실험 노트북
├── requirements.txt           # 실행에 필요한 Python 패키지 목록
└── README.md
```
<br><br><br>
## 🛠️ 주요 기능

- ✅ 품목 선택 후 가격 시계열 시각화  
- 📈 Rolling Mean을 통한 가격 추세 파악  
- 📊 예측 정확도(metric summary) 확인  
- 📅 날짜 범위 지정 필터 제공
- 🧪 다양한 시계열 예측 모델 실험 및 비교:
  - **Prophet**: 추세, 주기성, 휴일 등을 자동 반영하는 시계열 분석 모델
  - **XGBoost / LightGBM**: 시계열 특징을 반영한 트리 기반 부스팅 모델
  - **RandomForestRegressor / LinearRegression**: 머신러닝 회귀 모델 비교용
- 📏 모델 성능 비교 지표:
  - MAE (Mean Absolute Error)
  - RMSE (Root Mean Squared Error)
- 🧄 지원 품목:
  - cabbage (배추)
  - radish (무)
  - garlic (마늘)
  - onion (양파)
  - daikon (대파)
  - cilantro (건고추)
  - artichoke (깻잎)

<br><br><br>
## 📊 데이터 설명

| 파일명                  | 설명                                                                 |
|------------------------|----------------------------------------------------------------------|
| `train.csv`            | 시계열 예측 모델 학습용 원본 데이터                                  |
| `test_2020-11-05.csv`  | 테스트 및 성능 평가용 데이터                                         |
| `streamlit_data.csv`   | Streamlit에서 사용하는 전처리된 시계열 데이터                        |
| `metric_summary.csv`   | 각 품목별 예측 모델 성능 요약 (예: MAE, RMSE 등)                    |

<br><br><br>

## 📌 인사이트 (Insights)

이 Streamlit 대시보드를 통해 다음과 같은 **실질적인 인사이트와 의사결정 도움**을 받을 수 있습니다:

- 📦 농산물 가격 급등/급락 예측을 통한 **재고 및 물류 계획 최적화**
- 📉 평균 가격 추세선을 활용한 **안정적인 구매/판매 시점 판단**
- 📊 품목별 예측 정확도 비교를 통한 **모델 신뢰도 분석**
- ⏳ 날짜 필터 기능으로 특정 시점 전후의 **시장 변동성 파악**
- 🤖 다양한 AI 예측 모델을 비교해보며 **데이터 기반 의사결정 역량 강화**
- 🧠 시계열 예측 결과를 통해 **향후 가격 흐름을 선제적으로 대응**


<br><br><br>
## 📷 앱 화면 예시

👉 실제 앱 사용해보기: [https://aibootcamp-app.streamlit.app/](https://aibootcamp-app.streamlit.app/)




