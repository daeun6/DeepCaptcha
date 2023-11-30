# DeepCaptcha


### 1. 개발 배경

딥보이스 기술의 발전으로 증가한 딥보이스 기반 보이스피싱 피해를 낮추는 것이 목표이며 대화 내용 기반 보이스피싱 탐지 프로그램에 딥보이스 탐지 기술을 추가한 연구 및 애플리케이션을 개발한다.  


### 2. 전체 구성

2.1 딥보이스 탐지 : 실제 음성을 STFT로 변환 후, Bicoherence로 변환하여 구성한 데이터 셋을 Ganomaly 모델에 학습시켜 Anomal Score로 딥보이스 적용 여부 판별

2.2 내용 기반 탐지 : 피싱대화/일반대화 음성을 STT로 변환 후 벡터화하여 구성한 데이터 셋을 LSTM 모델에 학습 시켜 이진 분류를 통해 보이스피싱 대화 여부 판별

### brochure

![b4가 낫다  (1)](https://github.com/daeun6/DeepCaptcha/assets/81478444/961239cf-5431-4c1d-9a86-c45bf5b7a0ae)


![학부생  (4)](https://github.com/daeun6/DeepCaptcha/assets/81478444/1cf906ef-f7c7-413c-b789-919ae2380b1c)


### ✌️ 참여 인원

|[송다은](https://github.com/daeun6)|[이나영]()|[김지원]()|
| --- | --- | --- |
|<img width="100" src="https://github.com/GDSC-SWU/2023-AI-ML-study/assets/81478444/21400679-dcc3-4731-9638-d8f717e0bc84"/>|<img width="100" src=""/>|<img width="100" src=""/>|
