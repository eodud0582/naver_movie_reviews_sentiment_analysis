# Naver Movie Reviews Sentiment Analyzer Modeling
## 네이버 영화 평점 분석 및 긍부정 예측 모델링

![image](https://user-images.githubusercontent.com/38115693/154954040-0ce6f83e-f465-40bf-a300-45e90a10efe8.png)

## 프로젝트 배경 및 목적
- 영화에 대해 많은 평점이 존재하여, 영화에 대한 정확한 평을 알기 어려운 경우가 있음
- 네이버 영화 평점 분석을 통해 영화에 대한 전체적인 평을 확인 할 수 있을 것이라 생각됨
  - https://movie.naver.com/movie/point/af/list.nhn
- **Logistic Regression을 활용한 긍정/부정 예측 모델링**

## 데이터
- 네이버 영화 평점 데이터
  - https://github.com/e9t/nsmc

## 프로젝트 결과
- CountVectorizer를 사용한 경우와 비교하여, **TF-IDF**를 사용했을 때가 더 높은 성능을 보였습니다.
- **Accuracy: 0.8412 / AUC: 0.9214**
