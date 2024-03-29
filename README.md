
# About the project
 
‘서울시 열린데이터 광장’에서 제공하는 여러 공공 데이터 가운데 [서울시 개인적인 고민거리 통계](https://data.seoul.go.kr/dataList/datasetView.do?infId=10416&srvType=S&serviceKind=2&currentPageNo=1&searchValue=&searchKey=null) (서울특별시 스마트도시정책관 빅데이터담당관, 2014년)를 활용하여, 구글 차트와 워드클라우드로 데이터를 시각화하는 프로젝트이다. 


# Purpose of the project

이 프로젝트를 통해 이루고자 하는 학습목표는 다음과 같다.
 
- 데이터 분석에서 시사점을 다각도로 이끌어 내는 것이 가능한 주제 / 연구방식을 지닌 데이터 선정하기<br>
- 구글 차트를 그리기에 적합한 형식으로 데이터 변환<br>
- 구글 차트로 구현될 수 있도록 자바 언어로 프로그래밍<br>
- 데이터를 워드클라우드로 시각화하기<br>

# Implications of the project

제공받은 데이터를 가공하여 개인적 고민의 종류를 '연령 / 성별 / 소득 / 혼인상태 / 학력 / 지역(지역구)'이라는 범주로 나누어 살펴본다. 이를 통해, 여러 범주 중 개인의 고민과 가장 큰 상관관계를 보이는 것은 '연령'일 것이라는 가설을 상정하고 확인해 볼 수 있다. 즉, 성별, 소득. 혼인상태, 학력, 지역에 따른 변화에도 차이를 거의 보이지 않는 개인의 고민거리가, 연령에 따라서는 확연한 차이를 보이고 있다. 특히, 혼인상태에 따른 개인별 고민거리의 차이도 혼인상태의 직접적인 영향이라기보다 연령이라는 제3의 변수(교란요인)에 의해 매개되고 있을 가능성까지 감안해 볼 때, 개인적 고민거리를 결정하는데 있어 '연령'이 아주 중요한 요소로 작용한다는 것을 알 수 있다. 또 한가지 흥미로운 점은, 개인의 고민거리가 학력의 차에 따라 큰 차이를 보이지는 않는 한편, 유독 중졸 이하에서만 '건강문제'가 독보적인 고민거리로 부상된다는 사실이다. 이것은 소득이 100만원 이하인 경우에도 건강문제가 최고의 고민거리로 나타나는 결과와 궤를 같이하는 양상으로서, 중졸이하에서는 학력이 절대적 빈곤과 밀접한 관련이 있기 때문일 것이라고 유추해 볼 수 있겠다.
  

# Development Environment

Window 10<br>
Eclipse Java EE IDE for Web Developers Version: Photon Release (4.8.0)<br>
Visual Studio Code(1.38.0)<br>

# Built with

```
* RDBMS : Oracle
* Back End Development Languages : Java / Servlet & JSP / SQL
* Front End Development Language : Java Script / HTML / CSS
* Libraries : Lombok, Google Chart 
* Tools : Maven / Eclipse 
* Additional technical set : Ajax
```

# How to run it
1. Eclipse에서 jsp 파일에 JSON 데이터를 넣은 후 웹서버를 가동한다
2. VSC에서 "step03_miniProject.html" 파일을 라이브 서버로 가동한다
3. 분석을 시작한다

# Authors
* **강민웅**:  [강민웅의 깃헙](https://github.com/happymwkang)
* **김수경**:  [김수경의 깃헙](https://github.com/sooish)
* **김웅태**:  [김웅태의 깃헙](https://github.com/angle2v)
* **김종성**:  [김종성의 깃헙](https://github.com/SEJSCloud)


# Images

<div>
<img src="https://user-images.githubusercontent.com/51253930/65009903-3ebe2700-d949-11e9-89d2-1ba909ac3dca.png" width="90%"></img>
<img src="https://user-images.githubusercontent.com/51253930/65009900-3d8cfa00-d949-11e9-9ac0-2b5dd723e5de.png" width="90%"></img> 
</div>
