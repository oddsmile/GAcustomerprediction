# GAcustomerprediction

### 개요
---
- 유저 분석에 널리 사용되는 GA4 데이터를 직접 다뤄봅니다
- 서비스 사용성 분석에 일반적으로 사용되는 지표를 직접 구해봅니다

### 배경
---
- 로그 데이터 Log data는 서비스를 이용하는 유저의 족적을 파악할 수 있는 데이터입니다.
- 굉장히 양이 많고, 전처리가 조금 어렵지만 서비스 분석을 하기 위해서는 필수적인 여정이기에 이를 체험보고자 합니다.

### 주제
---
- 사용자 로그 행동 데이터 활용 웹 서비스 분석

### 설명
---
- 파이썬을 이용해 주어진 데이터로부터 다음의 지표들을 구하고 시각화합니다.
    - DAU/WAU/MAU를 line chart로 시각화
    - 유저별 평균접속시간의 분포를 ECDF로 시각화
    - 방문 주차에 따른 코호트를 생성하고, 코호트 별로 weekly 리텐션을 구하고 이를 heatmap으로 시각화
    - 요일/시간대별 사용자 수를 구하고 이를 heatmap으로 시각화
    - (Challenging) Carrying Capacity
        - [참고 영상(토스)](https://www.youtube.com/watch?v=tcrr2QiXt9M&t=1s)
    - (Challenging) 국가별 DAU 평균을 Folium으로 시각화하기
    - (Challenging) 캠페인 효과 분석: 캠페인으로 들어온 사람은 다른 사람과 다른 특징을 가지고 있는지 분석해보기
데이터 : [Kaggle 데이터](https://www.kaggle.com/competitions/ga-customer-revenue-prediction/overview)

