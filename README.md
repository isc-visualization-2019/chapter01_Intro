정보문화학 비주얼라이제이션 2019-1
===

교과목번호
---
- 2114.411

교과목명
---
  - 비주얼라이제이션

담당교수
---
 - 성명 : 배여운
 - 이메일 : bae.yeowoon@joongang.co.kr
 - 면담방법(시간/장소)
   * 매 수업 후 강의실 (수업 전에 이메일 요청)
   * 주중은 상암동 JTBC빌딩 (수업 전에 이메일 요청)

수업진행
---
 - 깃허브 : 해당 페이지에 강의 자료 등이 공유됩니다.
 [https://github.com/isc-visualization-2019](https://github.com/isc-visualization-2019)
 - 슬랙 : 슬랙 메신져를 활용하여 수강생간의 소통이 이루어질 예정입니다.

수업목표
---
 - 비주얼라이제이션을 위한 시각화 리터러시(Visual Literacy)를 학습한다. 
 - Grammar of Graphics를 바탕으로 올바르고 왜곡없는 차트 제작
 - ggplot2를 활용한 explanatory charts를 구성해본다.
 - 정부와 언론에서 왜곡한 그래프를 알아보고 올바르게 표현해본다. 

교재 및 참고문헌
---
 - 별도의 주교재 없이 강의자료를 바탕으로 진행합니다. 아래의 참고문헌을 활용합니다.
 - ggplot2 Elegant Graphics for Data Analysis, Hadley Wickham, 2016 (Second Edition)
 - The Grammar of Graphics (Statistics and Computing), Leland Wilkinson, 2005
 - R Graphics Cookbook, Winston Chang, 2018 (Second Edition)
 - The Truthful Art: Data, Charts, and Maps for Communication, Alberto Cairo, 2016
 - Data Visualisation: A Handbook for Data Driven Design, Andy Kirk, 2016
 - The Wall Street Journal Guide to Information Graphics, Dona M. Wong, 2013
 - [Flowing Data, Nathan Yau](https://flowingdata.com/)
 - [R for Journalists](https://learn.r-journalism.com/en/), Andrew Ba Tran (Washington Post)

평가방법
---

| 구분 | **출석** | **개인과제** | **팀과제** | **기말프로젝트** | **기타참여** |
|:--|:--|:--|:--|:--|:--|
| 비율 | 10% | 20% | 20% | 45% | 5% |

출석 (10%)
---
 - 수업일수의 1/3을 초과하여 결석하면 성적은 "F" 또는 "U"가 됨(담당교수가 불가피한 결석으로 인정하는 경우는 예외로 할 수 있음)
 - 피치못할 사정이 있는 경우 미리 연락 부탁드립니다.

개인과제(20%)
---
 - 매주 한 개의 course가 [DataCamp](https://www.datacamp.com) Classroom에 등록됩니다. 제출 기한이 있습니다. 
 - 매 과제 완료 후에 Certification(PDF) 구글드라이브에 업로드

팀과제(20%)
---
 - 그래프(차트) 분류 시각화 (ex.[Financial Times Chart Doctor](https://github.com/ft-interactive/chart-doctor/tree/master/visual-vocabulary))
 - 결과물은 print, interactive 상관 없음 (print 결과물 제출시 인쇄비 지원)
 - 팀과제 수행 기간은 중간고사 직후 시작해서 5월 중순까지 마감할 것
 - xmind로 기획서 제출

기말 과제전(45%)
---
 - 자유주제로 비주얼라이제이션 작품 만들기 (데이터시각화)
 - 비주얼라이제이션 구현은 자유 : print(Infographics), d3.js, R Graph, Processing 등
 - 데이터 수집은 정보공개청구, 공공데이터, 크롤링을 바탕으로 진행

기타 참여(5%)
---
 - 담당 교수가 제작 예정인 2019년 1학기 강의북 제작 참여시 (수업 아카이빙)
	 - '한 학기 우리는 어떻게 공부했나?' 코드 및 자료 공유 예정
 - GitBook으로 퍼블리싱 및 바이라인 함께 공동 명시
 - [Mistakes, we’ve drawn a few](https://medium.economist.com/mistakes-weve-drawn-a-few-8cdd8a42d368?fbclid=IwAR2LXxJ_SCs6VH453d2IBoWzjueFbLR8CHKVULc2UahL7kB1tak8uI1KP90)

강의계획(주차별)
---

### 1주차 : 오리엔테이션
  - 강의소개
  - Join in Datacamp Classroom
  - R/Rstudio 설치 및 [팀세팅](https://docs.google.com/spreadsheets/d/e/2PACX-1vSpvm-G78bO3WfSpnoHH2y-FerPB1X7v736PD9xviPvl_CuLUrSSkfXghB-068MrsAx7M59yZW29Yqo/pubhtml?gid=23874303&single=true)
  
### 2주차 : [비주얼라이제이션을 위한 데이터 알아보기](https://github.com/isc-visualization-2019/chapter02_190316) 
  - 데이터 타입(numeric, character, factor, date 등)과 구조
  - vector, matrix, dataframe, list 알아보기
  - Data import/export
  - [xmind](https://www.xmind.net/)
  - 과제전 팀미팅
  - (과제 01) : [Working with the RStudio IDE(Part1)](https://www.datacamp.com/courses/working-with-the-rstudio-ide-part-1) 
  - (과제 02) : [Introduction to R](https://www.datacamp.com/courses/free-introduction-to-r)
  - [강의슬라이드](https://docs.google.com/presentation/d/1PBSNUrivGktWj5QepzAOaCL_Ldu6akU53Ip8lLajpug/edit?usp=sharing)

### 3주차 : [Essential Function](https://github.com/isc-visualization-2019/chapter03_190323) 
  - 비주얼라이제이션을 위한 가로형 데이터와 세로형 데이터 개념(gather & spread)
  - FOR, IF 반복문
  - Data Wrangling in Tidyverse
  - 과제전 팀미팅
  - (과제 03) : [Intermediate R](https://www.datacamp.com/courses/intermediate-r)

### 4주차 : [Tidyverse for Data visualization](https://github.com/isc-visualization-2019/chapter04_190330)
  - ~~정부와 언론 속 정크차트란 무엇인가?~~ (5주차로 연기)
  - `select`, `filter`, `mutate`, `arrange`, `group_by` 등을 활용하여 비주얼라이제이션을 위한 데이터프레임 다루기
  - 과제전 팀미팅
  - How Charts Lie 실습
  - (과제 04) : [Data Manipulation in R with dplyr](https://www.datacamp.com/courses/dplyr-data-manipulation-r-tutorial)

### 5주차 : [Data Visualization-Base](https://github.com/isc-visualization-2019/chapter05_190406)
  - 정부와 언론 속 정크차트란 무엇인가?
  - `plot`으로 base graphics 만들어보기
  - Visual Encoding이란? 차원과 시각적 요소의 관계
  - 과제전 팀미팅
  - How Charts Lie 실습
  - (과제 06) : [Data Visualization in R](https://www.datacamp.com/courses/data-visualization-in-r)

### 6주차 : [중간고사](https://github.com/isc-visualization-2019/chapter06_190413)
  - 중간고사는 별도의 퀴즈로 대체합니다

### 7주차 : [Aesthetics](https://github.com/isc-visualization-2019/chapter07_190420)
  - Grammar of Graphics | Aesthetics
  - Aesthetics를 활용한 시각화 실습
  - 과제전 팀미팅
  - How Charts Lie 실습
  - (과제 07) : [Data Visualization with ggplot2(Part1)](https://www.datacamp.com/courses/data-visualization-with-ggplot2-1)

참고사항
---
 - 본 수업은 프로그래밍 강좌 수업이 아닌 올바른 비주얼라이제이션을 위한 데이터시각화 이론과 제작을 배웁니다. 
 - 1-2회 외부특강이 예정되어 있습니다.
 - 과제전 프로젝트가 있습니다. 