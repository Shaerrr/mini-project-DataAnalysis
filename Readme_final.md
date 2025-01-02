# 데이터로 바라본 DLC의 영향력과 방향
## 프로젝트 개요
기간: 2024.12.16 ~ 2024.12.30   
발표 PDF:  
◆ 팀원 및 역할
- 김형후: 스팀 리뷰 데이터 크롤링, dlc 평가지표 제작, 자연어 전처리 및 정규화, 매출 순위 데이터 수집
- 지서연: 스팀 플레이어 수 데이터 수집, 전처리, ITS & 회귀 분석
- 이성복: DLC 별 순위추이 분석, DLC별 리뷰 감성분석 및 키워드 분석
   
본 프로젝트는 게임 DLC(다운로드 콘텐츠)가 게임 산업에 미치는 영향을 데이터 분석을 통해 연구했습니다. 특히 Sims 4를 주요 사례로 활용하여 DLC의 효과와 플레이어 행동 패턴을 분석했습니다. 

## 데이터 수집 및 분석 방법
◆ 데이터 소스
- Steam DB: 플레이어 수, 리뷰 데이터
- EA 공식 웹사이트: DLC 정보
- 총 리뷰 수: 영어 리뷰 15,110개, 한국어 리뷰 2,251개

## 분석 방법론
- Interrupted Time Series 분석 - DLC 출시 전후의 플레이어 수 변화 분석 - Free to Play 전환 효과 분석
- 회귀 분석 - DLC 할인율과 플레이어 수 상관관계 분석 - R-squared 값 기반 영향력 측정
- NLTK 형태소 분석 - 리뷰 텍스트 자연어 처리 - 감성 분석 및 주요 키워드 추출
- apriori 연관 분석 - DLC 구매 패턴 분석 - 연관 규칙 도출

## 주요 연구 결과
◆ DLC 유형별 영향력
- EP(확장팩): 매출 순위에 긍정적 영향
- GP(게임팩): 매출에 미미한 영향
- SP(스터프팩): 변동성 존재
- KIT(키트): 높은 변동성

## 리뷰 분석 결과
◆ 감성 분석
- 긍정: 66.8% 
- 중립: 18.6%
- 부정: 14.6%

## 주요 키워드 
- 긍정: 콘텐츠 품질, 게임성 
- 부정: 가격, 버그

Free to Play 전환 효과
◆ 평균 플레이어 수 증가
- 전환 전: 평균 2만 5천명 
- 전환 후: 평균 4만 5천명

## 활용 방안 및 제안
◆ DLC 개발 전략
- 가격 정책과 안정성 우선 고려
- 정기적 콘텐츠 업데이트 필요
- 유저 피드백 기반 기획

## 모니터링 체계
- 실시간 리뷰 분석
- 플레이어 행동 패턴 추적
- 매출 영향도 측정

## 사용 기술
- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- KoNLPy
- Jupyter Notebook
- Selenium

## 참고 문헌
- 굿모닝증권, "게임 수명 늘려라..."
- W. B. Cullen, "Ex-PlayStation boss predicts PS5 games will cost $200m to make"
- EA 공식 웹사이트
- The Sims 공식 유튜브 채널
- KRAFTON 공식 유튜브 채널
- Steam: https://store.steampowered.com/
- SteamDB: https://steamdb.info/
- Welcome to Steam
- The Steam Winter Sale is on now — find great deals on thousands of games! Plus vote for the finalists in the 2024 Steam Awards.
- Welcome to Steam
- SteamDB:  https://store.steampowered.com/
- SteamDB : https://steamdb.info/

