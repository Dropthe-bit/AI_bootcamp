# 📘 06_LLM: Transformer & GPT2 기반 번역 및 파인튜닝 실습

자연어처리 모델의 구조인 Seq2Seq, Transformer, GPT2에 대한 실습 예제가 담겨 있습니다.  
Attention 메커니즘, 포지셔널 인코딩, 멀티헤드 어텐션 구현부터 GPT2 기반 제로샷 번역, 파인튜닝까지 학습 과정 실습.

## 📄 실습 목록

### ➊ [Seq2Seq + Attention Mechanism, Transformer, GPT2 실습 통합](https://colab.research.google.com/github/Dropthe-bit/ai_portfolio/blob/main/06_LLM/6_transfomer.ipynb)
- 번역을 위한 GRU 기반 Seq2Seq 모델 구현
- Attention 메커니즘 적용하여 문맥 정보 강화
- Transformer의 포지셔널 인코딩, 멀티헤드 어텐션 등 핵심 모듈 직접 구현
- Hugging Face의 GPT2Tokenizer 실습 및 제로샷 번역
- 사전학습된 GPT2를 번역 태스크에 맞게 파인튜닝

<details>
<summary>📚 포함된 실습 항목 보기</summary>

- GPT2Tokenizer를 활용한 토크나이징  
- `<PAD>` 및 `<|endoftext|>` 토큰 처리  
- 커스텀 Dataset (`WMTDataset`) 및 `collate_fn` 구성  
- Seq2Seq 모델 클래스 및 Attention 모듈 구현  
- 포지셔널 인코딩, 멀티헤드 어텐션, Feedforward, LayerNorm 직접 구현  
- Transformer 인코더-디코더 구조 작성  
- Cosine decay warmup 학습률 스케줄러 구현  
- GPT2 기반 제로샷 번역 실습 
- GPT2 파인튜닝을 위한 커스텀 학습 루프
</details>
