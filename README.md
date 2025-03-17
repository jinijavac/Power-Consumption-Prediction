# Power Consumption Prediction

## 전력 사용량 예측

### 사용한 머신러닝 모델

- Multi-layer Perceptron (MLP)
- Long Short-Term Memory (LSTM)
- Random Forest Regressor (RF)
- Gradient Boosting Regressor (GBR)
- Support Vector Regressor (SVR)
- K-Nearest Neighbors Regressor (KNN)
- XGBoost Regressor (XGB)

---

### 데이터셋 설명

- **HOTD** : 시간 (Hour of the Day)  
- **DOTW** : 요일 (Day of the Week)  
- **Holi** : 공휴일 여부 (Holiday Indicator)  
- **Cons_1, Cons_7** : 과거 전력 소비량 (이전 1시간 및 7시간 전 소비량)  
- **Temp** : 온도 (Temperature)  
- **Humi** : 습도 (Humidity)  
- **WS** : 풍속 (Wind Speed)  
- **WCT** : 체감 온도 (Wind Chill Temperature)  
- **THI** : 온습도 지수 (Temperature-Humidity Index)  
- **Consumption** : 실제 전력 소비량 (Target Variable)  

---

### 모델 성능 평가 (오차 지표)

| Model    | RMSE       | MAE        | MAPE      |
|----------|-----------|-----------|-----------|
| Ensemble | 504.106   | 260.042   | 29.140%   |


