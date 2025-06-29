# 📘 05_DL_Basics: 딥러닝 기초 실습

딥러닝 기초 모델을 다양한 형태로 구현하며, DNN, CNN, LSTM, AutoEncoder의 기본 구조와 학습 과정을 실습합니다.  
이미지 분류, 시계열 예측, 이상 탐지 등의 태스크에 각 모델을 적용하며 구조적 차이를 이해합니다.

## 📄 실습 목록

### ➊ [DNN 기반 분류 모델 실습 (Deep Neural Network)](https://colab.research.google.com/github/Dropthe-bit/ai_portfolio/blob/main/05_DL_Basics/5_1_deep_learning1_dnn.ipynb)
- PyTorch로 구현한 **심층 신경망(DNN)** 기반 이진 분류 실습  
- `Sequential`, `Dropout`, `BatchNorm1d` 등을 활용한 유연한 모델 구조 설계  
- `train_loader` 기반 학습 루프 작성 및 정확도, F1-score 평가 진행  

<details>
<summary>📚 포함된 실습 항목 보기</summary>

- 사용자 정의 `DNN` 및 `DNN_dropout_batchNorm` 클래스 구현  
- 하이퍼파라미터 랜덤 서치를 통한 최적 모델 탐색  
- 드롭아웃 및 배치 정규화 유무에 따른 모델 성능 비교  
- `Permutation Importance` 기반 특성 중요도 분석  
- K-Fold 교차검증을 통한 모델 일반화 성능 평가  
- 학습 손실 그래프 시각화  

</details>

---

### ➋ [CNN 기반 이미지 분류 모델 실습 (Convolutional Neural Network)](https://colab.research.google.com/github/Dropthe-bit/ai_portfolio/blob/main/05_DL_Basics/5_2_deep_learning2_cnn.ipynb)
- PyTorch로 구현한 **합성곱 신경망(CNN)** 기반 다중 클래스 이미지 분류 실습  
- CIFAR-10 데이터셋을 활용한 학습 및 예측 수행  
- `Conv2d`, `MaxPool2d`, `ReLU`, `Dropout`, `BatchNorm2d` 등을 활용한 CNN 구조 설계 및 개선  

<details>
<summary>📚 포함된 실습 항목 보기</summary>

- 사용자 정의 `BasicCNN` 및 `ImprovedCNN` 클래스 구현  
- 드롭아웃, 배치 정규화 등 추가 기법 적용을 통한 모델 성능 향상  
- 학습/검증 정확도 및 손실 추이 시각화  
- `test_loader`를 활용한 모델 예측 결과 시각화 (이미지와 예측 라벨 출력)  
- 클래스별 정확도 측정 및 주요 오분류 샘플 시각화  

</details>

---

### ➌ [LSTM 기반 시계열 분류 모델 실습 (Long Short-Term Memory)](https://colab.research.google.com/github/Dropthe-bit/ai_portfolio/blob/main/05_DL_Basics/5_3_deep_learning2_lstm.ipynb)
- PyTorch로 구현한 **LSTM(Long Short-Term Memory)** 기반 시계열 분류 실습  
- `sin`과 `cos` 파형에 대한 시계열 데이터를 기반으로 이진 분류 수행  
- `nn.LSTM` 모듈을 활용한 순환 신경망 모델 구현 및 학습  

<details>
<summary>📚 포함된 실습 항목 보기</summary>

- LSTM 기반 `LSTMClassifier` 사용자 정의 클래스 구현  
- `DataLoader`를 활용한 시계열 형태의 학습/검증 데이터 구성  
- 시퀀스 입력 길이에 따른 입력 텐서 전처리 및 배치 구성  
- 학습 루프 작성 및 에폭별 정확도 및 손실 출력  
- 테스트 데이터에 대한 예측 결과 시각화 (원본 시계열 + 예측 라벨 표시)  

</details>

---

### ➍ [오토인코더 기반 비지도 학습 실습 (AutoEncoder)](https://colab.research.google.com/github/Dropthe-bit/ai_portfolio/blob/main/05_DL_Basics/5_4_deep_learning2_ae.ipynb)
- PyTorch로 구현한 **오토인코더(AutoEncoder)** 기반의 비지도 학습 실습  
- MNIST 데이터셋을 사용하여 입력 이미지를 압축하고 복원하는 신경망 구조 학습  
- 인코더-디코더 구조를 활용한 특징 표현 학습 및 시각화  

<details>
<summary>📚 포함된 실습 항목 보기</summary>

- 오토인코더 모델 클래스(`AutoEncoder`) 구현  
- 인코딩 차원(`z_dim`) 변경에 따른 성능 차이 실험  
- 입력 이미지와 복원 이미지 비교 시각화  
- 테스트 샘플의 인코딩된 잠재공간(z) 시각화 (2D scatter plot)  
- 학습 손실(MSELoss) 추이 그래프 시각화  
</details>
