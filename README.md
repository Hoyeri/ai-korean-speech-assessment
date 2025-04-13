# ai-korean-speech-assessment
이 repository는 GPT-4o mini, Whisper, librosa를 활용하여  
**한국어 학습자의 말하기 발화에 대해 자동 채점 실험을 수행한 코드**를 포함합니다.  

---

- Whisper로 전사된 텍스트 및 avg_logprob 추출 → **발음 정확도 정량화**
- librosa로 pause 빈도, 발화 속도 계산 → **유창성 정량화**
- 각 지표를 z-score 기반으로 점수화 → **1~5점 척도 구성**

- GPT 프롬프트를 통한 내용 및 언어 사용 채점 → **전문가 채점과의 비교 분석**
