### 개발일정
5주차 : 관련 Danfo.js , javascript 언어 다루기 습득
<hr>
6주차~8주차 : 얻어낸 데이터와 관련된 필요한 컨텐츠 코드 작성(javascript코드 위주)
(ex : CompareCity, 지도를 통한 원하는 날짜 지정시 해당 도시 드래그때 확진자 발생, 기간내 전반적인 그래프 추출, 
해당 날짜 별 막대그래프 혹은 원차트 추출  및 해당 결과물 다운로드 받을 수 있게 구현)
<hr>
9주차 : 6주차에서 8주차까지 작성한 코드 모듈화 및 가독성 높이기
<hr>
10주차 : 코로나 웹사이트 시작 브라우저 UI 환경 코드작성
<hr>
11주차 : Bootstrap을 통한 레이아웃 css 설계
<hr>
12주차 : 관련 xml데이터 csv변환 내용 서버에 전송(데이터 수 증가)
<hr>
13주차 ~ 14주차 : 이전기간에 수행 못한 부분 수정 및 처리 



### 핵심 기술 내용 분석

1. xml 형태의 공공데이터 (open.api => [코로나 시도별 현황](https://data.go.kr/iim/api/selectAPIAcountView.do) )
2. Danfo.js (Danfo.js is heavily inspired by the Pandas library and provides a similar interface and API. This means users familiar with the Pandas API can easily use Danfo.js. )
=> 간단히 python의 pandas에서 감명받은 것을 통해 만들어낸 js 라이브러리
3. [xml to csv 사이트](https://json-csv.com/xml) : Danfo.js에서 데이터 파일을 사용하기위해서는 csv파일이 필요한데 실제 공공데이터 사이트에서
제공하는 데이터는 xml 형태이므로 이를 변환해주는 사이트를 통해 데이터 정제가 필요
4. Javascript : Danfo.js 라이브러리를 이용하기 위한 기본적인 언어로써 해당 데이터를 
필요에 따라 다룰수 있게 만드는 언어


### 추가로 우리가 만드는 웹사이트의 목적
=> 해당 **xml 데이터에서 제공하는 것들로써 만들어내는 의미있는 데이터의 결과** 및 추가 세부 코로나 관련 내용


