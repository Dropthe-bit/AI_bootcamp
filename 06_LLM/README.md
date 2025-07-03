# 📘 06_LLM: Transformer & GPT2 기반 번역 및 파인튜닝 실습

자연어처리 모델의 구조인 Seq2Seq, Transformer, GPT2에 대한 실습 예제가 담겨 있습니다.  
Attention 메커니즘, 포지셔널 인코딩, 멀티헤드 어텐션 구현부터 GPT2 기반 제로샷 번역, 파인튜닝까지 학습 과정 실습.

## 📄 실습 목록

### ➊ [Seq2Seq + Attention Mechanism, Transformer, GPT2 실습 통합](https://colab.research.google.com/github/Dropthe-bit/ai_portfolio/blob/main/06_LLM/6_1_transfomer.ipynb)
- 번역을 위한 GRU 기반 Seq2Seq 모델 구현
- Attention 메커니즘 적용하여 문맥 정보 강화
- Transformer의 포지셔널 인코딩, 멀티헤드 어텐션 등 핵심 모듈 직접 구현
- Hugging Face의 GPT2Tokenizer 실습 및 제로샷 번역
- 사전학습된 GPT2를 번역 태스크에 맞게 파인튜닝

<details>
<summary>📚 포함된 실습 항목 보기</summary>

- GPT2Tokenizer를 활용한 토크나이징   
- 커스텀 Dataset (`WMTDataset`) 및 `collate_fn` 구성  
- Seq2Seq 모델 클래스 및 Attention 모듈 구현  
- 포지셔널 인코딩, 멀티헤드 어텐션, Feedforward, LayerNorm 직접 구현  
- Transformer 인코더-디코더 구조 작성  
- Cosine decay warmup 학습률 스케줄러 구현  
- GPT2 기반 제로샷 번역 실습 
- GPT2 파인튜닝을 위한 커스텀 학습 루프
</details>

### ➋ [Zero-shot Prompting, CoT, RAG, PEFT 통합 실습](https://colab.research.google.com/github/Dropthe-bit/ai_portfolio/blob/main/06_LLM/6_2_llm.ipynb)
- 사전학습된 언어모델에 Prompt만으로 문제 해결 (Zero-shot)
- 추론 과정을 중간 단계로 유도하는 Chain-of-Thought(COT) 기법 실습
- FAISS 기반 문서 검색을 통한 Retrieval-Augmented Generation (RAG)
- RAG에 PEFT 기법을 결합한 파라미터 효율적 미세조정 실습

<details>
<summary>📚 포함된 실습 항목 보기</summary>

- Hugging Face 모델과 토크나이저 로딩 및 프롬프트 생성  
- `generate()`를 이용한 Zero-shot 추론  
- Chain-of-Thought Prompt 구성 및 출력 결과 비교  
- FAISS를 통한 벡터기반 문서 검색 및 RAG 구현  
- 사용자 질문에 대한 검색 → 컨텍스트 → 생성 흐름 구성  
- LoRA 미세조정 적용    
</details>
