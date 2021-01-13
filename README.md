# Python_National_Petition
```
청와대 국민청원 게시판 크롤링, 데이터 가공, 데이터 시각화를 통해 
현재(2020.01.11기준) 청원게시판의 Top Keyword를 쉽게 알 수 있다.
```

# 데이터 시각화 결과
# Screenshot
![real_data_cloud](https://user-images.githubusercontent.com/50208120/104368859-fffda880-555f-11eb-8b7c-4a7057707bf2.PNG)


# Introduction
```
1. 2020년 1월 11일 기준 청와대 국민청원 게시판 추천순이 높은 게시글 크롤링. 
2. 데이터 가공, 엑셀에 저장
3. KoNLPy 패키지로 자연어처리
4. wordcloud 로 데이터 시각화
5. 데이터 전처리 후 가장 많이 등록된 청원 키워드 20개 추출
6. 빈도수가 가장 높은 키워드가 가장 큰 텍스트로 보여지는 것을 확인 (위 ScreenShot 확인)

```

# Visualizing Environment
```
- Python 3.9.1
- Jupyter Notebook

```

# Library
```
- selenium
- BeautifulSoup
- Konlpy
- openpyxl
- matplotlib
- WordCloud
- numpy

```