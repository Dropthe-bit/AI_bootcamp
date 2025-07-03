# 🎬 Content-Based Filtering: TMDB 영화 추천 시스템

`TMDB 5000 Dataset`을 활용하여 컨텐츠 기반 추천 시스템을 구현한 실습 노트북입니다. 

## 📄 실습 노트북

### ➊ [콘텐츠 기반 추천 시스템 구현](https://colab.research.google.com/github/Dropthe-bit/ai_portfolio/blob/main/project_recommender_system/Content_Based_TMDB.ipynb)
- 영화 제목, 개요, 출연진, 감독 정보 전처리
- `TF-IDF` 벡터화 및 `Cosine Similarity` 기반 유사도 계산
- 유사 영화 추천 함수 구현

<details>
<summary>📚 포함된 실습 항목 보기</summary>

- TMDB 5000 Dataset 로딩 (`movies`, `credits`)  
- 영화 정보 병합 및 결측치 처리   
- `TfidfVectorizer`로 텍스트 벡터화  
- `cosine_similarity`로 영화 간 유사도 계산  
- 사용자가 입력한 영화 기준으로 유사 영화 Top-N 추천 함수 구현   
- 추천결과 시각화
</details>

---

# 📚 Book Recommendation System

이 프로젝트는 Kaggle의 `Book Recommendation Dataset`을 기반으로 다양한 **추천 알고리즘**을 실습한 노트북입니다.  
메모리 기반 협업 필터링, 행렬 분해, 딥러닝 기반 모델, 콘텐츠 기반 추천 등 **다양한 방식의 추천 시스템**을 실습과 함께 학습할 수 있습니다.

## 📄 실습 노트북

### ➊ [book_recommend_system.ipynb](https://colab.research.google.com/github/Dropthe-bit/ai_portfolio/blob/main/project_recommender_system/book_recommend_system.ipynb)
- Kaggle 데이터 기반 책 추천 시스템 구축
- EDA, 전처리, 다양한 추천 알고리즘의 구현 포함
- 협업 필터링, SVD/NMF, NCF, 콘텐츠 기반, 인기 기반 추천까지 다룸
- ** Kaggle Notebook 환경에서 실행 가능**

<details>
<summary>📚 포함 알고리즘 요약</summary>

- Memory-based Collaborative Filtering  
- Model-based Matrix Factorization (SVD, NMF, SVDpp)  
- Neural Collaborative Filtering (NCF)  
- Content-based Filtering  
- Popularity-based Recommendation  
- Final 모델 통합 클래스 구성  

</details>
