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
