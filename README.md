## Select Language: [English](https://github.com/LoveYouTenderly/LoveYouTenderly/blob/main/README.md#english), [한국어](https://github.com/LoveYouTenderly/LoveYouTenderly/blob/main/README.md#%ED%95%9C%EA%B5%AD%EC%96%B4)

## __English__
Contact: loveutenderly@gmail.com

# 😎 Introduction
I am a self-taught programming enthusiast. I have no CS degree nor a Bootcamp programming experience. Yet, I managed to solve problems using programming both as a hobby and work.

# 🐱‍🏍 Skills

### Back-end
  - Python | Pytorch, TensorFlow, Keras, Selenium, Doc2Vec, BERT, stylegan2, Stable Diffusion
  - R
  - Java
  - Swift
  - Kotlin
  - C

### Database
  - MySql

### Etc
  - Ubuntu
  - Colab
  - VScode

# 🏤 Education
### University
  - Bachelor: Ulsan National Institute of Science and Technology (No. 174 in the world, No. 6 among Korean universities) - Technology Management/Information System/Entrepreneurship, Marketing
  - Masters: Ulsan National Institute of Science and Technology - Management of Technology
  - Graduation Thesis for Masters - [Application of Long-short Term Memory (LSTM) Model for Forecasting NOx Emission in Pohang Area](https://drive.google.com/file/d/1tEm8tMAlw372iQ1S5NwwcdtkCuhNYNip/view?usp=sharing)
    
I took some courses in Coursera and Harvard edX

### Coursera
  - [Google Data Analytics Certificate](https://www.credly.com/badges/253783f7-f43a-4d4d-be18-97656f9cde1e)
  - [Data Analysis Using Python](https://coursera.org/share/ada3399a722a4d58ada1c30096c078ce)
  - [Inheritance and Data Structures in Java](https://coursera.org/share/bb3b62746751fbf6023fe3b4fb6ee72f)
  - [Introduction to Java and Object-Oriented Programming](https://coursera.org/share/532d22be61f63df885cefb6d0ffad6f0)
  - [Computational Thinking for Problem Solving](https://coursera.org/share/4e95fc2e0151545836ce8834e131d93d)
  
### Harvard edX
  - [Data Science: Machine Learning](https://courses.edx.org/certificates/54ff4138f50d4960829babca4a373f07)

# 🚀 Personal Experience & Projects
### 1. OWISquadTranslation Project
- I have participated in working on a translation project for a game called [Squad](https://store.steampowered.com/app/393380/Squad/).
#### Key Problems: Unity issue - 8000 lines of massive translation were done by individuals where unity throughout translation would be at risk.
#### Achievements
- Made an improvement to the search directory.
  - Find the same and similar text using Doc2Vec
  - Made repetitive translation work only done once for identical sentences.
  - Make a search directory by file location to show translators indicate where each sentence is used in-game.
#### Used repository 
- Selenium, Doc2Vec

### 2. Creating Stylegan2 Dataset Repository 
- I have made independent datasets for [Stylegan2](https://github.com/NVlabs/stylegan2) using two Nvidia 3060 Graphic Cards under Ubuntu OS for about two weeks each.
  - [Cat __1024x1024__](https://drive.google.com/file/d/1gKYFu0grhUC7O-8V6q2WOXTcTvQzy-MC/view?usp=share_link)
  - ![fakes000260](https://user-images.githubusercontent.com/72162982/202870367-cb878188-98c8-438a-88be-6fb098ad1585.jpg)
  - [Wood texture 1024x1024](https://drive.google.com/file/d/140newRNqvadE_K2i4lR2vJvc3TtTYJIU/view?usp=share_link)
  - ![fakes000464](https://user-images.githubusercontent.com/72162982/202870377-cac6018c-3432-46d4-8e1a-020f81f77784.png)
  - [Marble texture 1024x1024](https://drive.google.com/file/d/1RQ8A8UEYJdAcrdL8eZiE1VaTCMAazRqS/view?usp=share_link)
  - ![fakes000508](https://user-images.githubusercontent.com/72162982/202870380-ddb93cb5-a2c7-44aa-b662-b4a6ccbe9e1a.png)
  - [Flower 1024x1024](https://drive.google.com/file/d/1YeKQJ_kzJA0U9hA-HEoQ7RLtQu__5i-q/view?usp=share_link)
  - ![fakes000000 (1)](https://user-images.githubusercontent.com/72162982/204686171-94b82b41-401a-4a89-87ec-0fd79431eb57.png)
#### Used repository 
- Stylegan2, Pytorch

### 3. Analyze webpage
- I have analyzed [3D Modeling webpage](https://kainrypus.booth.pm/items?page=1) via request.
#### Key Problems: Analyze customer preference based on product market values
#### Achievements
- Found the market value of each product depends on image popularity matters from the second image and after. (Image anaysis)
- Found the market value of each product has no relation with text description (NLP)
- Monthly sales increased by 220% within 6 months since the analysis
#### Used repository 
- Selenium, Tenserflow, googletrans

### 4. [Project ongoing] Tracking for Aim Analysis for performance enhancement in FPS or ESP Hacking
[![Watch the video](https://img.youtube.com/vi/Dv0_ciMkJsY/maxresdefault.jpg)](https://youtu.be/Dv0_ciMkJsY)
#### Used repository 
- YOLO, cv2

# 📈 Work Experience

#### Aerix Data Analysts Developer Feb 1st 2023 ~ April 30th 2023 (Company account used https://github.com/AerixTenderly)
- Doing data analysis of TMS data as part of the [Clean Factory Governmental Project](https://www.korea.kr/news/pressReleaseView.do?newsId=156435736)
  Identified Outliers
  Found the worker's tendency to check on Monday and disregard the rest.
  Found SOx is more carefully audited compared to NOx
  Found overall correlation between dust, SOx, and NOx. [(Dust ⊃ NOx) & (NOx ∩ SOx)] // [(NOx ∩ SOx) ∉ Dust] as [SOx ∉ Dust]
  Made forecast model using LSTM and [Prophet](https://facebook.github.io/prophet/)
  Identified the reason for the hardship of making the NOx forecast model
- Grafana visualization using InfluxDB and Python via NUC 
- Successfully built and executed anomaly detection analysis for the first time in the company via Fourier Transform and IoT MQTT device data. The company struggled to solve this issue for years.

#### WisdomHouse(kor-_집현전_ ) COO & Programmer Jan 1st 2022 ~ Oct 11th 2022 (_company closed business_)
_only described work experience using programming(Python)_
- Made a backend system to collect company financial status and transform it into the form of dataframe from [DART](https://dart.fss.or.kr/) (not released)
- Used [stable diffusion](https://huggingface.co/CompVis/stable-diffusion-v1-4?text=A+high+tech+solarpunk+utopia+in+the+Amazon+rainforest) while creating company webpage (not released)
- Develop a system to analyze presenters' emotions using [LeXmo](https://github.com/dinbav/LeXmo)
- Analysize company tendencies via Twitter/Instagram/Facebook/NaverNews using both NLP and image recognition.




## __한국어__

# __Tenderly | 머신러닝과 인공지능 세상에 눈을 뜬 문과생 개발자__
Contact: loveutenderly@gmail.com

# 자기소개
취미로 프로그래밍하며, 스스로 성장해온 아마추어 개발자입니다.

# Skills

### Back-end
  - Python | Pytorch, TensorFlow, Keras, Selenium, Doc2Vec, BERT, stylegan2, Stable Diffusion
  - R
  - Java
  - Swift
  - Kotlin
  - C

### Database
  - MySql

### Etc
  - Ubuntu
  - Colab
  - VScode

# 학력
### 대학
  - 학부: 울산과학기술원 - 기술경영학과/마케팅
  - 석사: 울산과학기술원 - 기술경영학
  - 석사졸업논문 : [Application of Long-short Term Memory (LSTM) Model for Forecasting NOx Emission in Pohang Area](https://drive.google.com/file/d/1tEm8tMAlw372iQ1S5NwwcdtkCuhNYNip/view?usp=sharing)

온라인 과정
### Coursera
  - [Google Data Analytics Certificate](https://www.credly.com/badges/253783f7-f43a-4d4d-be18-97656f9cde1e)
  - [Data Analysis Using Python](https://coursera.org/share/ada3399a722a4d58ada1c30096c078ce)
  - [Inheritance and Data Structures in Java](https://coursera.org/share/bb3b62746751fbf6023fe3b4fb6ee72f)
  - [Introduction to Java and Object-Oriented Programming](https://coursera.org/share/532d22be61f63df885cefb6d0ffad6f0)
  - [Computational Thinking for Problem Solving](https://coursera.org/share/4e95fc2e0151545836ce8834e131d93d)
  
### Harvard edX
  - [Data Science: Machine Learning](https://courses.edx.org/certificates/54ff4138f50d4960829babca4a373f07)

# 개인 및 단체 프로젝트
### 1. OWISquadTranslation Project (단체)
- [스쿼드](https://store.steampowered.com/app/393380/Squad/)라는 스팀게임 번역에 참여하였으며, 데이터셋 재구축 및 Doc2Vec등을 활용하여 단순 번역뿐만이 아니라, 번역환경 전반에 편리한 번역을 할 수 있게끔 구축하였습니다.
#### 해결과제: 통일성 문제 - 8000여 줄 이상의 번역을 5명이 각자 번역작업을 하여 (용어/말투 등의) 번역 작업의 통일성이 일정하지 않음
#### 해결방안
- 검색 디렉터리 개선 및 보완.
  - Doc2Vec을 활용하여 유사 문장을 검색해, 타인의 번역 및 유사한 문장을 참조할 수 있는 시스템 개발.
  - 중복된 문장을 한 번만 번역하도록 구축.
  - 각 번역된 문장이 활용되는 파일 위치를 정리하여, 각 번역이 게임 내에 활용이 어디서 되는지 알 수 있게끔 구축.
#### 사용된 package 
- Selenium, Doc2Vec

### 2. Stylegan2 데이터셋 구축 
- [Stylegan2](https://github.com/NVlabs/stylegan2)를 활용뿐만이 아니라 독립된 데이터셋을 각 셋당 약 2주간의 머신러닝을 통해 학습시킴.
  개인 컴퓨터에서 Ubuntu OS에서 NVIDIA 3060 두 개를 활용. 한 달에 100만원 이상의 전기세가 나온 적이 있음.
  - [Cat __1024x1024__](https://drive.google.com/file/d/1gKYFu0grhUC7O-8V6q2WOXTcTvQzy-MC/view?usp=share_link)
  - ![fakes000260](https://user-images.githubusercontent.com/72162982/202870367-cb878188-98c8-438a-88be-6fb098ad1585.jpg)
  - [Wood texture 1024x1024](https://drive.google.com/file/d/140newRNqvadE_K2i4lR2vJvc3TtTYJIU/view?usp=share_link)
  - ![fakes000464](https://user-images.githubusercontent.com/72162982/202870377-cac6018c-3432-46d4-8e1a-020f81f77784.png)
  - [Marble texture 1024x1024](https://drive.google.com/file/d/1RQ8A8UEYJdAcrdL8eZiE1VaTCMAazRqS/view?usp=share_link)
  - ![fakes000508](https://user-images.githubusercontent.com/72162982/202870380-ddb93cb5-a2c7-44aa-b662-b4a6ccbe9e1a.png)
  - [Flower 1024x1024](https://drive.google.com/file/d/1YeKQJ_kzJA0U9hA-HEoQ7RLtQu__5i-q/view?usp=share_link)
  - ![fakes000000 (1)](https://user-images.githubusercontent.com/72162982/204686171-94b82b41-401a-4a89-87ec-0fd79431eb57.png)

#### 사용된 package 
- Stylegan2

### 3. 웹페이지 분석 (의뢰)
- [3D 모델링 웹페이지](https://kainrypus.booth.pm/items?page=1)를 의뢰받아 분석.
#### 해결과제: 제품별 시장가치에 따른 고객 성향 분석
#### 성취
- 제품별 시장가치가 배치된 2번째 이미지 이후부터 관계가 있음을 발견 (이미지 분석)
- 제품별 시장가치가 제품 설명서와 관계가 없음을 증명 (자연어처리)
- 분석후 월 매출 6개월만에 220% 상승
#### 사용된 package 
- Selenium, Tenserflow, googletrans

### 4. [미완 프로텍트] FPS 또는 ESP 해킹의 성능 향상을 위한 조준 분석 추적
[![Watch the video](https://img.youtube.com/vi/Dv0_ciMkJsY/maxresdefault.jpg)](https://youtu.be/Dv0_ciMkJsY)
#### 사용된 package 
- YOLO, cv2

# 업무 경험
#### 에어릭스 - 데이터분석 담당 개발자 - 2023 2월 ~ 2023 4월 (해당 기간동안 사용된 계정 https://github.com/AerixTenderly)
- [클린팩토리 프로젝트](https://www.korea.kr/news/pressReleaseView.do?newsId=156435736)의 일환으로 TMS 데이터 분석 수행
  이상값 분석 진행
  월요일에만 점검하고 나머지는 무시하는 작업자의 경향을 발견
  질소산화물(NOx)에 비해 황산화물(SOx)을 더 주의 깊게 감사하는 경향 발견
  먼지, 황산화물(SOx, 질소산화물(NOx) 간의 전반적인 상관관계 발견. (먼지 ⊃ NOx) & (NOx ∩ SOx)] // [(NOx ∩ SOx) ∉ 먼지] = [SOx ∉ 먼지]
  LSTM과 [Prophet](https://facebook.github.io/prophet/)을 사용하여 예측 모델 제작
  질소산화물(NOx) 예측 모델 제작이 어려운 이유 파악
- Grafana 시각화, influxdb와 NUC를 활용
- IoT MQTT 디바이스 데이터로부터 사내 최초로 FFT 분석 구축 및 실행에 성공

#### 집현전 인베스트먼트 - 운영팀장/개발자 - 2022년 1월 ~  2022 10월 (회사 폐업)
_업무 중 프로그래밍을 활용한 것만 작성_
- [DART](https://dart.fss.or.kr/)시스템에서 검색된 회사 재무제표를 데이터셋으로 자동 변환할 수 있는 백엔드 개발 (미출시)
- [Stable diffusion](https://huggingface.co/CompVis/stable-diffusion-v1-4?text=A+high+tech+solarpunk+utopia+in+the+Amazon+rainforest)을 활용하여 회사 홈페이지 제작에 활용 (미출시)
- [LeXmo](https://github.com/dinbav/LeXmo)를 활용하여 발표자들의 심리상태분석
- 트위터/인스타그램/페이스북/네이버뉴스 등의 텍스트(자연어처리) 및 이미지 분석을 통해, 회사의 성향분석

<!---
LoveYouTenderly/LoveYouTenderly is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
