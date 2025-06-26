# 📘 03_Unsupervised_Learning: 비지도 학습 실습

비지도 학습 기법을 활용한 클러스터링 및 차원 축소 실습 예제가 포함되어 있습니다.  
K-means와 PCA 등의 알고리즘을 사용하여 데이터 구조를 이해하고 시각화하는 방법을 학습합니다.

## 📄 실습 목록

### ➊ [K-means 클러스터링 (Clustering)](https://colab.research.google.com/github/Dropthe-bit/ai_portfolio/blob/main/03_Unsupervised_Learning/3_1_machine_learning2_clustering.ipynb)
- K-means 알고리즘을 활용한 클러스터링 실습  
- 군집 수 결정 기법(Elbow Method, Silhouette Score) 적용  
- 시각화를 통한 클러스터 구조 분석 

<details>
<summary>📚 포함된 실습 항목 보기</summary>

- **계층적 군집화 (Hierarchical Clustering)**  
  - 덴드로그램 시각화  
  - 실루엣 계수 분석  
- **중심기반 군집화 (Centroid-based: K-means)**  
  - Elbow Method, Silhouette Score, ARI  
  - 최적 k값 탐색 및 시각화  
- **밀도기반 군집화 (Density-based: DBSCAN)**  
  - 이상치 탐지 포함  
  - ARI, Silhouette Score 활용  
- `KneeLocator`, `clusteval` 활용 자동 군집 수 탐색  
- `matplotlib`, `seaborn` 기반 시각화  

</details>

---

### ➋ [PCA 기반 차원 축소 (Dimension Reduction)](https://colab.research.google.com/github/Dropthe-bit/ai_portfolio/blob/main/03_Unsupervised_Learning/3_2_machine_learning2_dimension_reduction.ipynb)
- 주성분 분석(PCA)을 통한 차원 축소 및 시각화  
- 고차원 데이터를 시각적으로 해석 가능하게 표현

<details>
<summary>📚 포함된 실습 항목 보기</summary>

- PCA `scikit-learn` 적용  
- 설명된 분산비(Explained Variance Ratio) 확인  
- 차원 축소 전/후의 정보 손실 확인 (누적 분산 분석)  
- 군집 구조 시각화 (`scatter plot` 기반 시각화)  
- `matplotlib`, `seaborn` 활용  

</details>
