# **Graduate Admissions**

대학원의 입학 가능 확률을 아는 것은 전략적 대학원 지원을 위해 중요한 일이다. <br>
본 커널의 목적은 ‘GRE Score’, ‘TOEFL Score’, ‘CGPA’, ‘University Rating’, ‘SOP’, ‘LOR’, ‘Research’ 의 7 항목을 토대로 ‘Chance of Admit’을 모델링 하는 것이다.

사용언어 & 툴: python <br>
데이터 수집: kaggle dataset 'graduate-admissions'를 통해 수집

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
