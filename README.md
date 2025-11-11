# ChildSpeech
### 한국어 아동 음성 데이터를 활용하여 데이터 증강 후 Whisper-small 모델 성능 개선

<img width="949" height="270" alt="research_pipeline(urop)" src="https://github.com/user-attachments/assets/ee2481cb-6b36-44a1-b51a-252c023a7c9e" />
(pipeline은 위와 유사함. Timestretch 구간에서 여러 방법 적용하여 실험 진행)

<실험 순서>
- 테스트 데이터(지정)로 whisper 기본 성능 알아보기 (=zero-shot 성능 평가)
- fine-tuning (+자연 발화)
- 각각의 방법으로 데이터 증강
- 증강한 데이터로 학습시키고 성능 알아보기
- 성능 비교

<방법>
- speed (ㅇㅎ)
- pitch (ㅇㅎ)
- volume (ㅅㅁ)
- noise (ㅁㄱ)
- specArgu
- TTS (이건 추후에 할 예정)
- 각각 단일 방법 실험 후 결과가 좋은 방법들을 조합해서 재실험 진행 

<251105 Wed>
- 방법 나누기
- 데이터 다운받기
- 나이 구간 나누기 (4-7세, 8-12세)
