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
- <유저들의 FW position에 대한 평가>
- 침투와 체감을 중요시함
- 드리블, 몸싸움, 크로스에 대한 괌심이 높음
- 헤딩의 중요성을 보임
- 호나우두, 호날두, 메시, 네이마르에 대한 언급 비중이 높음

#### - wordcloud of MF_position

![image](https://user-images.githubusercontent.com/68583172/103621119-12804c80-4f78-11eb-9de5-400d6aba663f.png)

- <유저들의 MF position에 대한 평가>
- 굴리트, 비에이라 선수에 대한 언급 비중이 높음
- 패스와 체감을 매우 중요시 여김
- 중거리에 대한 중요성
- 더브라위너, 프티 선수도 눈에 띔
- 크로스의 중요성
- FW 대비 은카에 대한 관심도가 높음
- 수비적인 가담이 중요시됨


#### - wordcloud of DF_position

![image](https://user-images.githubusercontent.com/68583172/103622513-304eb100-4f7a-11eb-966f-c1c1597cb50e.png)

- <유저들의 DF position에 대한 평가>
- 수비수 답게 몸싸움이 매우 중요시 여겨짐
- '동작'이라는 말의 언급 비중이 높음으로 보아 역동장에 대한 관심이 높음
- 크로스를 잘 방어해야 하고, 체감을 중요시 여김
- 다른 포지션 대비 금카, 은카에 대한 비중이 굉장히 높음
- 풀백에 대한 관심도가 높음
- 라모스, 바란, 말디니 선수에 대한 언급이 높음

#### - wordcloud of GK_position

![image](https://user-images.githubusercontent.com/68583172/103623910-2168fe00-4f7c-11eb-8082-481d35b7846a.png)

- <유저들의 GK position에 대한 평가>
- 급여에 대한 관심이 가장 높음
- 중거리, 크로스를 잘 처리해야함
- 쿠르투아, 데헤아, 노이어에 대한 언급이 많음
- 라이브 시즌 카드에 대한 언급이 많음
- 금카에 대한 비중이 매우 높음


