**프로젝트 소개 및 회고 :** <수치 모델 앙상블을 활용한 강수량 예측> 을 주제로 관측값 앙상블 v01~v09 변수를 바탕으로 vv 실강수량을 예측하는 모델을 만들었습니다. 분석 과정에서 주로 사용한 라이브러리는 pandas 와 sklearn 입니다.

featrue engineering 단계에서 장마 변수, 통계적 파생 변수, 시계열 sin,cos 변수를 생성한 것이 예측 점수 향상에 도움이 되었습니다. 모델은 비선형 모델인 RandomForestRegressor 모델로 예측 진행했습니다. 

다양한 변수를 만들어 점수 향상에 도움이 되었지만, 지역별 특성을 살렸더라면 하는 아쉬움에 대회가 끝나고 stn을 분리해서 학습과 예측을 했습니다. 그리고 평가지표 점수가 향상되는 걸 확인해 그 부분이 가장 아쉽습니다. 그래도 입선이라는 성과를 내서 대회장에서 발표를 해 본 경험이 굉장히 뿌듯합니다. 발표를 마치고 심사위원께서 피드백해주신 sin, cos 주기성에 대해 조금 더 공부했습니다.

**대회 링크 :** https://bd.kma.go.kr/contest/main.do

**프로젝트 기간 :** 2024.06.11 - 2024.08.07

**사용 언어 :**  **Python** ver.3.8.19

**역할 :** (2인 팀) 데이터 분석 파트 (EDA, feature engineering, modeling)

**깃허브 링크 :** https://github.com/i2mmmmm/weather_contest
**PPT 링크 :** https://github.com/i2mmmmm/weather_contest/blob/main/4_발표ppt.pdf
