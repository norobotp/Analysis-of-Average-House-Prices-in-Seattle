# 🏘️ Analysis of Average House Prices in Seattle

This project explores trends and seasonality in average house prices across various neighborhoods in Seattle using time series analysis and forecasting methods.

## 🔍 Overview
We aimed to:
- Analyze historical price data from the Seattle housing market
- Decompose trends, seasonality, and irregular components
- Forecast future price patterns using SARIMA and exponential smoothing models

## 📈 Key Features
- **Data preprocessing**: Handling missing values, converting timestamps, and aggregating monthly averages
- **Decomposition**: Using STL (Seasonal and Trend decomposition using Loess)
- **Modeling**:
  - SARIMA (Seasonal ARIMA)
  - ETS (Error-Trend-Seasonal models)
  - AIC-based model selection and diagnostics
- **Visualization**: Plots for trend, seasonality, and prediction intervals

## 📁 Output
The HTML report includes:
- Data source description and summary statistics
- Visual decomposition of trends and seasonal cycles
- Model performance comparison
- 12-month forecast of average house prices by neighborhood

## ⚙️ Technologies Used
- `R`, `forecast`, `ggplot2`, `tsibble`, `fable`, `feasts`
- Time series forecasting and seasonal decomposition

---

## 💡 Motivation
This project was conducted as part of a graduate-level course at the University of Michigan to apply modern time series forecasting tools to real estate market data and derive actionable insights on price dynamics in Seattle.

---

# 🏘️ 시애틀 평균 주택 가격 분석

이 프로젝트는 시애틀 내 다양한 지역(neighborhoods)의 **평균 주택 가격 변화 추세 및 계절성**을 시계열 분석 기법을 통해 분석하고, 향후 가격을 예측한 결과입니다.

---

## 🔍 개요

본 프로젝트의 주요 목표는 다음과 같습니다:

- 시애틀 부동산 시장의 과거 가격 데이터를 분석  
- 가격의 추세, 계절성, 불규칙 요소를 분해  
- SARIMA 및 지수 평활(ETS) 모델을 활용해 향후 가격을 예측  

---

## 📈 주요 특징

- **데이터 전처리**: 결측값 처리, 타임스탬프 변환, 월별 평균 가격 집계  
- **시계열 분해**: STL (Seasonal and Trend decomposition using Loess) 사용  
- **모델링 기법**:
  - SARIMA (계절 ARIMA)  
  - ETS (오차-추세-계절 모델)  
  - AIC 기반 모델 선택 및 진단 수행  
- **시각화**:
  - 가격 추세 그래프  
  - 계절성 도식화  
  - 예측 구간(신뢰 구간 포함) 시각화  

---

## 📁 결과물

HTML 보고서에는 다음 내용이 포함됩니다:

- 데이터 출처 설명 및 요약 통계  
- 추세 및 계절성 분해 시각화  
- 모델 성능 비교  
- **지역별 평균 주택 가격에 대한 향후 12개월 예측 결과**  

---

## ⚙️ 사용 기술

- `R`, `forecast`, `ggplot2`, `tsibble`, `fable`, `feasts`  
- 시계열 예측 및 계절 분해 분석 도구 활용

---

## 💡 프로젝트 동기

본 프로젝트는 **미시간대학교의 대학원 시계열 분석 수업**의 일환으로 수행되었으며, **부동산 시장 데이터에 최신 예측 기법을 적용**해 **시애틀 지역의 가격 동향에 대한 인사이트 도출**을 목표로 하였습니다.

