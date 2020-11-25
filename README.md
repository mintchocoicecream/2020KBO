# **2020KBO**
## Data analysis project
#### *Hyunjeong Seo, Eungkyung O, Seonghun Ahn*

## 데이터 크롤링
- 타겟사이트 : 롯데자이언츠 공식홈페이지, KBO 공식홈페이지, KBReport
### Requirement
- BeautifulSoup(bs4)
- Selenium

## 데이터 전처리
- 수집 데이터 타입 변경 및 결측치 처리
- 팀 이름 통일 ex)넥센 > 키움

## 데이터 분석
### - 단순회귀분석(팀별 타자,투수 연도 및 월 기준 기록 분석)
- 종속변수 : 팀 승률
- 독립변수 : 팀, 선수의 모든 기록 컬럼

### - 다중회귀분석
- 종속변수 : 팀 승률
- 독립변수 : 단순회귀분석에서 상관계수가 0.3이상인 요소 추출

## 예측
- 다중회귀분석
