# Sentence-Bias-Classification-using-Linguistic-Features-Based-on-Pre-trained-Language-Models
문장편향분류는 언어적 편향성을 탐지하는 모델로, 사전학습 언어모델과 언어적 특징을 활용한 fine-tuning방식을 제안하고 있다. 
또한 가짜뉴스가 언어적으로 편향된 표현이 많음을 확인함과 동시에 모델의 유효성을 검증하였다.

-------------

## Files descriptions

1. embedding.ipynb
  *사전학습 언어모델에 사용될 텍스트 임베딩을 생성하고 저장하는 코드.
  텍스트 임베딩은 data/preprocessed_data에 저장됨.*

2. model.py
  사전학습 언어모델을 언어적 특징 함께 활용하여 fine-tuning하는 코드.

3. training.ipynb
  저장된 embedding을 model.py의 모델을 통해 훈련시키는 코드.
  Fine-tuning된 모델은 data/models에 저장됨.

4. fakenews_embedding.ipynb
  Fake news 데이터의 텍스트 임베딩을 생성하고 저장하는 코드.
  텍스트 임베딩은 data/preprocessed_data에 저장됨.

5. fakenews_application.ipynb
  저장된 fake news 텍스트 임베딩을 시영히야 Fine-tuning된 모델을 fake news에 적용하는 코드.

6. requirements.txt
   본 실험에 사용된 파이썬 및 라이브러리 버전에 대한 정보

----------

## Model architecture


![image](https://github.com/J-HRhee/Sentence-Bias-Classification-using-Linguistic-Features-Based-on-Pre-trained-Language-Models/assets/48899068/4e1a167a-40de-47b9-8744-f4820f581c7f)


