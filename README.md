# Stock Pattern Finder
---


## 테스트
[1. 단일 종목 내 유사한 과거 주가 패턴 추출](https://github.com/sw-song/SPF/blob/main/test/01_single_stock_pattern_search.ipynb)
- 코스피(KS11)
- 최근 12일 그래프로 과거 12일치 그래프 비교
- 코사인 유사도 기준 가장 유사한 구간 추출(cosine:0.47)

<img src="https://github.com/sw-song/SPF/blob/main/readme_img/01_cosine_0.47.png" width="300" height="150">

- 과거 그래프에 5일 더 보여주기

<img src="https://github.com/sw-song/SPF/blob/main/readme_img/01_add5days.png" width="300" height="150">



## 폴더 구조
```
.SPF
.  /test
.  /test/01_single_stock_pattern_search.ipynb
```