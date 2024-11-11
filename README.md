# DA36_mini2_Dionysus
# 🍷Wine Recommendation System🍷

## 🍇 와인 추천의 필요성 🍇
  - 개인화된 추천 (Personalized Recommendation)
  - 새로운 와인 발견 (Discover New Wines)
  - 시간절약 (Time-Saving)

## 🍇 참고 사이트 🍇
[![image](https://github.com/user-attachments/assets/713b7b57-ba37-4e89-a7bb-f2ab2b2f5856)
](https://www.vivino.com/US/en/)

사진을 클릭하세요.

## 🍇 Team Crew 🍇
<div style="display: flex; align-items: center;">

  <img src="https://github.com/user-attachments/assets/843c1342-a6a6-415d-8fbe-6f5611f6e88c" style="width: 100px; margin-right: 20px;">
  <div>
    <strong>Haebin Kim</strong> <맛잘알, 와잘알 와인 추천 구현><br>
    [특징] 와인에 미쳐 사는 사람. 맛있는 음식과 함께라면 와인 주량 3병. 아이디어 제공자
  </div>

</div>

<div style="display: flex; align-items: center;">

  <img src="https://github.com/user-attachments/assets/adbecace-d98a-418a-9581-f570303ddbe9" style="width: 100px; margin-right: 20px;">
  <div>
    <strong>Yejin Lee</strong> <와린이 와인 추천 구현><br>
    [특징] 와인에 대해 아는 것이라고는 스파클링, 레드, 화이트 와인이 있다는 정도의 문외한이었어요. 하지만 이제 나도 와잘알?
  </div>

</div>

<div style="display: flex; align-items: center;">

  <img src="https://github.com/user-attachments/assets/324420a3-a674-4ee7-ac08-4285dbea6408" style="width: 100px; margin-right: 20px;">
  <div>
    <strong>Jeongseok Shim</strong> 팀원<br>
    [특징]  와인 입문자
  </div>

</div>

## 🍇 DATA Introduction 🍇
- [**와잘알/맛잘알 Data**](https://www.vivino.com/explore)
    - API 호출하여 JSON 파일 추출
    - **Columns**   총 22 columns x 3675 rows
        - *wine_ratings_count : 와인 평점 수*
        - *wine_ratings_average : 와인 평점*
        - *foods : 와인에 어울리는 음식*
        - vintage_price : 가격
        - vintage_wine_name : 와인 이름 (이름 + 년도)
        - vintage_wine_type : 와인 타입 (id mapping to type)
        - varietal_name : 포도 품종
        - variety : 와인 품종
        - winery : 와이너리 (양조장)
    - **Row Count**
        - 중복값 제거 후 df.shape = (2024, 22)

- [**와린이 Data**](https://www.kaggle.com/datasets/zynicide/wine-reviews?select=winemag-data_first150k.csv)
    - **Columns**
        - *description : 리뷰*
        - *title : 와인 이름*
        - country : 나라 이름
        - points : 와인 평점
        - price : 와인 가격
        - variety : 와인 품종
        - winery : 와이너리 (양조장)
    - **Row Count**
        - 중복된 행 제거 후 29,971 ⇨ 119,928
    - **Description words**
        - 68 words
        - 단어 벡터화 제외 5% 이하, 90% 이상 

## 🍇 Development Tools 🍇

![image](https://github.com/user-attachments/assets/0618206c-0b8f-46ca-b469-1670d4eee134)
![image](https://github.com/user-attachments/assets/b562dcd6-77ad-4869-ba33-fb8ff2f1ba32)
![image](https://github.com/user-attachments/assets/d8b91890-e764-458d-b4dc-1f413def55d1)
![image](https://github.com/user-attachments/assets/b26c66d7-251b-4e40-8c39-32cd627e45fd)



  








