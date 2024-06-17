## 프로젝트 코드 & 기타 파일 모음

- 프로젝트 개요
![KakaoTalk_Photo_2023-08-16-00-27-11](https://github.com/YoungMinDA/Team_project/assets/109095108/5e02065f-3195-4009-ba85-bcac4439b733)


  <img width="492" alt="스크린샷 2023-08-16 오전 8 06 22" src="https://github.com/YoungMinDA/Team_project/assets/109095108/0bd8fb4e-dcfc-4bc7-9510-a5e4cc1d7f5a">


`Preview`

- **팀 구성** : 환경지키조 4인
- **개요 :** 사회의 이해관계와 국가 정책 & 데이터 분석 결과를 바탕으로 ‘**GS25 편의점**’을 폐의약품 수거 플랫폼으로 선정한 **최초의** 입지 분석 프로젝트
- **역할** : 편의점 플랫폼 도입 제안, 데이터 수집 & EDA & 전처리, Tableau 대시보드 개발**(기여도 30%)**
- **성과 :** 플랫폼 도입에서 ****단순 생활인구수가 아닌 폐의약품 위험도 & 발생량, 기존 수거함 위치를 고려한 **GS25 편의점** **지점** 선정 및 **비즈니스 모델** 제안

- **참여** **공모전** :  동대문구 공공데이터 활용 정책 아이디어 공모전 & 제6회 전국 청년 아이디어톤 대회 & 환경부 에코톤 데이터 활용 및 분석 공모전 

**결과** : 최우수상 1위 & 본선 입선 & 예선 탈락

**(1) GitHub :** [프로젝트 분석 코드](https://github.com/YoungMinDA/Team_project/tree/main/%ED%8F%90%EC%9D%98%EC%95%BD%ED%92%88%20%EC%88%98%EA%B1%B0%EC%9C%A8%20%EC%A6%9D%EC%A7%84%EC%9D%84%20%EC%9C%84%ED%95%9C%20%ED%94%8C%EB%9E%AB%ED%8F%BC%20%EC%84%A0%EC%A0%95%20%EB%B0%8F%20%EC%9E%85%EC%A7%80%20%EB%B6%84%EC%84%9D%20%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8)

### 📋프로젝트 개요

---

환경보호를 위한 폐의약품 수거율 증진을 목표로 사회의 이해관계와 국가 정책, 데이터 분석 결과를 기반으로 한 ‘GS25 ’ 폐의약품 수거 플랫폼 입지 분석 프로젝트

| 정보 | 특징 | 형태 | 크기 | 운영기관 | 수집방안 | 출처 |
| --- | --- | --- | --- | --- | --- | --- |
| 국민건강보험공단_의약품 처방정보 | 지역, 연령대, 성별 등을 활용한 폐의약품 발생량 예측 및 위치 선정 | 정형
(csv) | 164,923,800개
(10,994,920,15) | 국민  건강   보험 공단 | 공공  데이터
포털 | https://www.data.go.kr/data/15007117/fileData.do |
| 건강보험심사 평가원_약가마스터_의약품주성분 | 환경의 영향을
미치는 의약품 코드 | 정형
(csv) | 446,832개
(55,854, 8) | 국민  건강   보험 공단 | 공공  데이터   포털 | https://www.data.go.kr/data/15067461/fileData.do?recommendDataYn=Y |
| 전국 GS25 정보 데이터 | ‘수원시’ GS25 ‘택배서비스’ 지점 추출 | 비정형
(Web) | 115,647개
(16,521, 7) | GS25 | GS25 공식  홈페이지(Scraping) | http://gs25.gsretail.com/gscvs/ko/store-services/locations#prev2 |
| 수원시 구, 동별 생활인구 통계  | 수원시 폐의약품 발생량 추정, GS25 편의점 입지 선정 | 정형
(csv) | 2,891개
(49, 59) | 
수원특례시 | 통계로 보는 수원 | https://www.suwon.go.kr/stat/db/suwonStatDBList.do?dbType=B |
| 수원시 권선구 폐의약품 수거 장소 | 폐의약품 수거 장소 & 좌표, 입지분석에 사용 | 비정형
(Web) | 13개                     (13, 1) | 수원 시청 | 수원시 권선구 홈페이지(Scraping) | https://ksun.suwon.go.kr/bbsplus/lst.asp?mnuflag=&code=tbl_bbs_dong_seryu1&skin_div=no&dong=%EC%84%B8%EB%A5%981%EB%8F%99 |
| GIS 건축물 통합 정보 | QGIS 입지 분석 건축물 설정 | 비정형 (shp) |              -  | 국토교통부 | 국가 공간  정보 포털 | http://openapi.nsdi.go.kr/nsdi/eios/ServiceDetail.do?svcSe=F&svcId=F010 |
| 행정구역 shp 데이터 | QGIS 입지 분석 좌표 설정 | 비정형(shp) |              -  | 지오서비스 | GIS Developer | http://www.gisdeveloper.co.kr/?p=2332 |
