# 소셜 유입 유저의 초기 이탈 분석을 통한 랜딩 UX 개선안 도출
Google Merchandise Store 사용자 행동 로그를 활용하여 유입 채널별 초기 이탈 차이를 분석하고, 소셜 유입 사용자의 랜딩 이후 행동을 추적해 주요 이탈 병목을 파악하고 전환 개선 방향을 도출한 프로젝트입니다.

## 분석 목적
Google Merchandise Store 사용자 행동 로그를 활용하여 유입 채널별 초기 이탈 차이를 분석하고, 소셜 유입 사용자의 랜딩 이후 행동을 추적해 주요 이탈 병목을 파악하고 전환 개선 방향을 도출합니다.

## 주요 분석 흐름
1. JSON 로그 데이터 평탄화 및 핵심 행동 변수 선별
2. 유입 채널 및 랜딩 경로 기준 사용자 그룹화
3. 채널·랜딩 경로별 행동 및 전환 지표 비교와 통계적 검증
4. 초기 이탈 완화를 위한 Middle-funnel 랜딩 UX 개선 가설 도출

## 사용 기술
- Python
- pandas
- numpy
- matplotlib
- seaborn
- scipy
- BigQuery

## 파일
- `01_social_traffic_bounce_analysis.ipynb` : 전체 분석 코드

## 데이터
본 프로젝트는 Google Merchandise Store의 Google Analytics Sample Dataset을 활용했습니다.
분석에 사용한 원본 parquet 파일은 용량 문제로 Repository에 포함하지 않았습니다.
