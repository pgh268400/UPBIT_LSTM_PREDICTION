# UPBIT_LSTM_PREDICTION
![image](https://user-images.githubusercontent.com/31213158/120110777-f5a81800-c1a9-11eb-9910-f7ddeb3e5863.png)

LSTM을 활용하여 업비트 시계열 데이터를 학습시킨후  
향후 30steps 까지 미래를 예측합니다.  

데이터는 업비트 비공식 API에서 가져옵니다.  

1step은 몇분봉 데이터로 학습시켰냐에 따라 달라집니다  
ex) 1일봉 데이터로 학습시 => 다음 30일까지 예측  
    1분봉 데이터로 학습시 => 다음 30분까지 예측
