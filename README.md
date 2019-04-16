# Graduate Admission

대학원의 입학 가능 확률을 아는 것은 전략적 대학원 지원을 위해 중요한 일이다. 
본 커널의 목적은 ‘GRE Score’, ‘TOEFL Score’, ‘CGPA’, ‘University Rating’, ‘SOP’, ‘LOR’, ‘Research’ 의 7 항목을 토대로 ‘Chance of Admit’을 모델링 하는 것이다.

사용언어 & 툴: python
데이터 수집: kaggle dataset 'graduate-admissions'를 통해 수집

0. INTRODUCTION
1. 라이브러리 로드
2. 데이터 적재
3. 탐색적 데이터 분석 (EDA)
3.1 general information
3.2 IV 탐색
3.3 DV 탐색
4. 특성 공학 (Feature Engineering)
4.1 feature engineering 전 모델링
4.2 feature importance 
4.3 예측변수 제거
4.4 변수 추가
4.5 가변수 생성
4.6 데이터 준비
4.7 변수 scaling
5. 지도학습 알고리즘을 활용한 회귀 모델링
5.1 linear regression
5.2 elastic net
5.3 linear SVM regression
5.4 Random forest regression
6. 결론

데이터 전처리: feature importance 계산/ 예측변수 제거 및 새로운 변수 추가/ 가변수 생성/ 변수 scaling
데이터 분석: linear regression, elastic net 등의 회귀 머신러닝 기법으로 'Chance of Admit' 모델링

