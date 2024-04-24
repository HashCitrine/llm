# llm

## 1. Attention Is All You Need
- [https://proceedings.neurips.cc/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf](https://proceedings.neurips.cc/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf)
- 트랜스포머(인공신경망) 구조를 발표한 논문
- 이후 많은 인공지능 모델이 트랜스포머 구조를 기본적으로 채용하며 언어모델의 성능이 비약적으로 향상
- [Hugging Face](https://huggingface.co/)와 같은 트랜스포머 모델 인터페이스 서비스 제공 플랫폼이 생겨남

## 2. 트랜스포머(Transformer)
![Transformer](https://upload.wikimedia.org/wikipedia/commons/8/8f/The-Transformer-model-architecture.png)
- Multihead Attention
- Positional Encoding
- Feed Forward Network

## 3. 언어모델
- OpenAI
  - [GPT](https://openai.com/gpt-4)
- Google
  - [Gemini](https://gemini.google.com) 
  - [Gemma](https://ai.google.dev/gemma)
- Meta
  - [LLaMA](https://llama.meta.com)

## 4. ollama
- [https://ollama.com/](https://ollama.com/)
- 개인 로컬 환경에서 LLM Model을 사용할 수 있도록 지원하는 도구(Linux, Mac, Windows 지원)
- 이용 예시
``` shell
> ollama run llama3
>>> Send a message
```

## 5. Pre Traing & Fine tuning


## 6. 참조
- [GPT-4 출시 | ChatGPT 달라진 점, GPT-3.5와 GPT-4 차이점](https://www.codestates.com/blog/content/gpt4-%EC%B6%9C%EC%8B%9C)
- [구글의 제미니와 GPT-4: 전체 성능 비교](https://textcortex.com/ko/post/gemini-vs-gpt-4)
- [구글의 최첨단 오픈 모델 ‘젬마(Gemma)’를 공개합니다](https://blog.google/intl/ko-kr/products/explore-get-answers/-gemma-open-models-kr/)
- [삼성 갤럭시 S24 시리즈에 탑재된 구글 AI](https://blog.google/intl/ko-kr/products/android-play-hardware/google-ai-samsung-galaxy-s24/)
- [Meta Llama 3 릴리즈: GPT4급 Open-Source 모델의 탄생](https://moon-walker.medium.com/meta-llama-3-%EB%A6%B4%EB%A6%AC%EC%A6%88-gpt4%EA%B8%89-open-source-%EB%AA%A8%EB%8D%B8%EC%9D%98-%ED%83%84%EC%83%9D-68c8ade1a33a)
