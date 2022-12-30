# Hedonic 가격모형을 활용한 서울특별시 내 Airbnb 숙소 가격 결정요인 연구

Hedonic Pricing model을 바탕으로 서울특별시 내 에어비앤비 숙박 가격 결정 요인 분석

## File Description

`Airbnb_crawl-v2.ipynb` airbnb 내부 자료 crawling 파일. requires `selenium`>=4.0

`지하철역_거리계산.ipynb` 지하철역 정보 지오코딩 파일

`prep.ipynb` review scoring 파일. requires `python` 3.6

`airbnb_hedonic.ipynb` Hedonic Modeling 파일

`인근 지하철역 정보 추가.csv` 숙소 내부 정보 + 지하철역 거리 정보 파일

`pororo_scoring.csv` 숙소 review scoring 결과 파일
## Methods

### 데이터 수집
**에어비앤비 내부 정보**

method: selenum crawling

수집 대상: 서울특별시 내 에어비앤비 숙소 800개 표본 선정,

`숙박 가능 인원` `침대 수` `욕실 수` `평균 평점` `리뷰 수` `슈퍼호스트 여부` `본인인증 여부` `호스트 응답률` `보증금 유무` `청소비 유무`
`보안카메라 유무` `세탁기 유무` `무료 주차 가능 여부` `사진 수` `리뷰 목록` `위치` 수집

**외부 정보**

지하철역 위치 정보: 서울교통공사 노선별 지하철역 정보 + kakao map api로 지하철역 이름 및 주소 정보 수집


### 데이터 전처리
TBD

### 회귀분석
