# FIFA_inven_analysis
- 피파 인벤 홈페이지 (출처 : http://fifaonline4.inven.co.kr/)
- 인벤 유저들의 선수 평가(comment) 데이터를 통한 분석

## 분석 목적
- user들의 선수들에 대한 평가가 어떤지 확인
- 주로 어떤선수들을 사용하는지(언급하는지) 확인
- 포지션별로 어떤 선수들을 많이 사용하는지(언급하는지) 확인
- 선수들에 대한 평가 중 어떤 말들이 많이 사용되는지 확인(wordcloud)


## Crawling 단계
- 선수들에 대한 user들의 comment data 수집
- 선수명 & 포지션 정보 수집
- ~ 2020/12/23 까지 기록된 데이터

## Analysis 단계
1. 데이터 불러오기 및 형태 확인
2. Descriptive Analysis
3. EDA를 통한 insight 도출
4. 데이터 시각화


## 결과
### wordcloud
#### - 추출된 선수(extracted_df) wordcloud of total_position

![image](https://user-images.githubusercontent.com/68583172/103545128-7b1de980-4ee4-11eb-802b-079d44025308.png)

#### - wordcloud of FW_position

![image](https://user-images.githubusercontent.com/68583172/103619039-5bce9d00-4f74-11eb-95dc-c65a520bee2f.png)

#### - wordcloud of MF_position

![image](https://user-images.githubusercontent.com/68583172/103621119-12804c80-4f78-11eb-9de5-400d6aba663f.png)


#### - wordcloud of DF_position

![image](https://user-images.githubusercontent.com/68583172/103622513-304eb100-4f7a-11eb-966f-c1c1597cb50e.png)

