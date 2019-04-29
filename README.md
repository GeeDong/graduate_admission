# **Graduate Admissions**

대학원의 입학 가능 확률을 아는 것은 전략적 대학원 지원을 위해 중요한 일이다. <br>

**목표**: ‘GRE Score’, ‘TOEFL Score’, ‘CGPA’, ‘University Rating’, ‘SOP’, ‘LOR’, ‘Research’ 의 7 항목을 토대로 ‘Chance of Admit’의 모델 개발 <br>
**과정**
1. 사용언어 & 툴: Python, scikit-learn
2. 데이터 수집: Kaggle 데이터셋 'graduate-admissions’
3. 데이터 전처리: 시각화를 통한 변수간 관계 파악, 이상치 제거, 특성공학을 통한 변수 추가/ 삭제/ 변환
4. 데이터 분석: 지도학습 알고리즘을 활용한 회귀 모델링 (Linear regression/ Elastic-net/ Linear SVR/ Random forest)

**성과** <br>
실제 값과 예측 값의 R2adj 기준 0.74 - 0.77 를 갖는 예측 모델 개발

**논의** <br>
대학원 합격/ 불합격의 기준을 세워(e.g. ‘Chance of Admit’이 0.8 이상이면 합격) 분류 분석을 수행 시, 합격/ 불합격으로 예측을 수행하기 때문에 회귀 분석보다 더 좋은 예측 성능을 보일 것이며, 전략적인 대학원 지원에 도움을 줄 수 있을 것으로 예상

---
**Contents**

1. 서론
2. 라이브러리 로드
3. 데이터 적재
4. 탐색적 데이터 분석 (EDA)
>- general information
>- IV 탐색
>- DV 탐색
5. 특성 공학 (Feature Engineering)
>- feature importance 계산
>- 예측변수 제거
>- 변수 추가
>- 가변수 생성
>- 데이터 준비
>- 변수 scaling
6. 지도학습 알고리즘을 활용한 회귀 모델링
>- linear regression
>- elastic net
>- linear SVM regression
>- Random forest regression
7. 결론
