# 출처와 이용조건

확인일: 2026-11-22. 법률 검토를 거친 내용은 아닙니다. 판단 근거는 코드 저장소 docs/data_contract.md 5절에 있습니다. 공공기관이 이 데이터를 후원하거나 보증하지 않습니다.

## 자체 가공 (행정동 배정, 거리 계산, 행정안전부 코드 대응)
- 이용조건: 통계청 SGIS 경계로 위치만 판정한 계산 결과입니다. 경계 데이터 자체는 포함하지 않습니다(법률 검토를 거친 판단은 아님).

## 통계청 한국행정구역분류 (행정동 코드·이름)
- 이용조건: 공개된 분류 코드
- 출처 표시 문구: 통계청 한국행정구역분류

## 국토교통부 전월세 실거래가 (오피스텔, 연립다세대)
- 이용조건: 공공데이터포털 이용허락범위 제한 없음
- 출처 표시 문구: 국토교통부 전월세 실거래가 자료(공공데이터포털)
- 링크: https://www.data.go.kr/data/15126475/openapi.do
- 링크: https://www.data.go.kr/data/15126473/openapi.do

## 소상공인시장진흥공단 상가(상권)정보
- 이용조건: 공공데이터포털 이용허락범위 제한 없음
- 출처 표시 문구: 소상공인시장진흥공단 상가(상권)정보(공공데이터포털)
- 링크: https://www.data.go.kr/data/15083033/fileData.do

## 서울 생활이동 (서울특별시·KT)
- 이용조건: 공공데이터포털 15087677: 제3자 권리 포함 저작권 표시, 공공누리 제1유형. 같은 계열 수도권 생활이동: 가공한 통계·지표 이용 허용(출처 표시), 원본 유상 재배포 금지
- 출처 표시 문구: 공공누리 제1유형에 따라 서울특별시 '서울 생활이동' 데이터 이용. 출처: 서울특별시·KT, 서울시 통신데이터
- 링크: https://data.seoul.go.kr/dataVisual/seoul/seoulLivingMigration.do
- 링크: https://www.data.go.kr/data/15087677/fileData.do
- 링크: https://data.seoul.go.kr/dataList/OA-22657/F/1/datasetView.do

## 서울시 역사마스터 정보
- 이용조건: 공공누리 제1유형(2026-10-22). 2026-11-22 열린데이터광장 표시는 이용허락범위 제한 없음
- 출처 표시 문구: 공공누리 제1유형에 따라 서울특별시 '서울시 역사마스터 정보' 이용
- 링크: https://data.seoul.go.kr/dataList/OA-21232/F/1/datasetView.do

## 통계청 SGIS 센서스용 행정구역경계(읍면동) 2025-06-30
- 이용조건: SGIS 통합 이용약관 제15조: 사전 승낙 없는 복사·복제·변경·타인 제공 불가, 영리행위 불가
- 링크: https://sgis.mods.go.kr/view/member/clause
- 링크: https://sgis.mods.go.kr/jsp/member/copyright.jsp

## 비공개 컬럼

출처의 이용조건에 따라 공개 파일에서 제외한 컬럼입니다.

- dong_profile.am_peak_congestion: 서울교통공사 혼잡도 데이터에서 온 값입니다. 검토 당시(2026-10-22) 변경 금지 조건(공공누리 제3유형)이 붙어 있어 제외했으며, 공개 여부를 다시 검토할 예정입니다.
- dong_profile.area_km2: 통계청 SGIS 경계로 계산한 값입니다. SGIS 이용약관상 제3자 제공이 금지돼 있어 공개하지 않습니다.
- dong_profile.convenience_store_per_km2: 행정동 면적으로 나눈 값입니다. 면적이 SGIS 경계로 계산한 값이라(SGIS 이용약관상 제3자 제공 금지) 공개하지 않습니다. 업소 수는 공개 컬럼에 있습니다.
- dong_profile.internal_pediatric_clinic_per_km2: 행정동 면적으로 나눈 값입니다. 면적이 SGIS 경계로 계산한 값이라(SGIS 이용약관상 제3자 제공 금지) 공개하지 않습니다. 업소 수는 공개 컬럼에 있습니다.
- dong_profile.laundry_per_km2: 행정동 면적으로 나눈 값입니다. 면적이 SGIS 경계로 계산한 값이라(SGIS 이용약관상 제3자 제공 금지) 공개하지 않습니다. 업소 수는 공개 컬럼에 있습니다.
- dong_profile.nearest_congestion_station_distance_m: 서울교통공사 혼잡도 데이터에서 온 값입니다. 검토 당시(2026-10-22) 변경 금지 조건(공공누리 제3유형)이 붙어 있어 제외했으며, 공개 여부를 다시 검토할 예정입니다.
- dong_profile.nearest_congestion_station_nm: 서울교통공사 혼잡도 데이터에서 온 값입니다. 검토 당시(2026-10-22) 변경 금지 조건(공공누리 제3유형)이 붙어 있어 제외했으며, 공개 여부를 다시 검토할 예정입니다.
- dong_profile.nearest_congestion_station_route: 서울교통공사 혼잡도 데이터에서 온 값입니다. 검토 당시(2026-10-22) 변경 금지 조건(공공누리 제3유형)이 붙어 있어 제외했으며, 공개 여부를 다시 검토할 예정입니다.
- dong_profile.pharmacy_per_km2: 행정동 면적으로 나눈 값입니다. 면적이 SGIS 경계로 계산한 값이라(SGIS 이용약관상 제3자 제공 금지) 공개하지 않습니다. 업소 수는 공개 컬럼에 있습니다.
- dong_profile.supermarket_per_km2: 행정동 면적으로 나눈 값입니다. 면적이 SGIS 경계로 계산한 값이라(SGIS 이용약관상 제3자 제공 금지) 공개하지 않습니다. 업소 수는 공개 컬럼에 있습니다.
