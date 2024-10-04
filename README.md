# 서울 날씨 변화 분석 (1994-2024)
> 이 프로젝트는 1994년부터 2024년까지 서울의 날씨 데이터를 분석하여 계절 변화와 온도 추이를 조사합니다. 특히 봄과 가을이 짧아졌다는 가설을 검증하는 것을 목표로 합니다. 



## 프로젝트 개요

🚀**프로그래머스 데이터분석 데브코스 4기 2차 프로젝트** 

- **개요**: Python을 활용한 데이터 분석 및 시각화
- **진행 기간**: 2024.9.24 - 2024.9.30
- **GitHub 저장소**: [Seoul Weather Analysis](https://github.com/dev-jhjoo/SeoulWeatherAnalysis)

## 주요 발견

1. **계절 변화**: 계절 시작일 분석 결과, 봄과 여름이 점점 빨리 시작되고 있으며, 가을은 늦게 시작되는 경향이 확인되었습니다. 이는 계절 패턴이 변화하고 있음을 나타냅니다.
   
2. **온도 추세**: 서울의 평균 기온은 점차 상승하고 있으며, 특히 여름철 온도 상승이 두드러집니다. 이는 최근 몇 년간의 폭염에 대한 인식을 뒷받침합니다.

3. **봄과 가을의 기간**: 5°C에서 20°C 사이의 일수를 분석한 결과, 봄과 가을에 해당하는 날의 수가 줄어들고 있어 이 계절들이 짧아졌다는 가설을 뒷받침합니다.

## 데이터 출처

- **데이터셋**: [Kaggle](https://www.kaggle.com/datasets/alfredkondoro/seoul-historical-weather-data-2024/data)에서 제공된 서울의 역사적인 날씨 데이터

## 사용된 도구

- **Python**: 데이터 정제, 변환 및 시각화
- **Pandas**: 데이터 처리 및 분석
- **Seaborn & Matplotlib**: 데이터 시각화

## 시각화 내용

- 연도별 계절 지속 기간 분석 (봄, 여름, 가을, 겨울)
- 특정 온도 범위(5°C ~ 20°C) 내 일수 추세 분석
- 연도별 계절 패턴 변화를 보여주는 선형 회귀 추세선

## 결론

이번 분석은 봄과 가을이 점점 짧아지고 여름 온도가 상승하는 경향이 있음을 확인했습니다. 이는 전반적인 지구 온난화와 관련이 있으며, 이러한 변화는 특히 이커머스 전략에서 시즌별 상품 기획 및 소비자 행동에 영향을 미칠 수 있습니다.

---

자세한 결과는 [최종 보고서](./SeoulWeatherAnalysis_Report.pdf)를 참고해주세요.
