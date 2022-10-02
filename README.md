# Stock_Analysis
주가 데이터 분석 텀 프로젝트

## 사용 개발 스택
- python
- mysql

## 주가 데이터 분석
- krx, fnguid를 크롤링 하여 데이터 수집  
주가데이터 수집 → 주가 데이터 분석 → 종목 추출
주가데이터 분석을 이용하여 조건에 부합하는 종목을 추천해준다.

### 가치주

- 이익대비 저평가 종목 : PER
- 장부가치대비 저평가 종목 : PBR
- 매출대비 저평가 종목 : PSR
- 현금흐름대비 저평가 종목 : PCR
    
    **가치지표 결합하기**
    
- 가치투자 4대장 콤보 : (PER+PBR+PSR+PCR)
- 실적대비 기업가치 : EV/EBITDA ^ EV Sales
- 그레이엄의 청산가치 : NCAV
- PEG 기반 종목 추출

### 우량주

- 투자 효율이 좋은 기업 : ROA, ROE
- 잔여이익모델 : RIM
- 영업효율이 좋은 기업 : GP/A
- 존버 할 수 있는 기업 : 안정성 지표
- 쑥쑥 자라는 기업 : 성장률 지표
- 부지런한 기업 : 회전율 지표
- 해자가 있는 기업 : 이익률 지표
