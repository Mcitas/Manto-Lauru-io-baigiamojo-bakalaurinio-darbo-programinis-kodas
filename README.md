# Mažmeninės prekybos prekių pardavimų prognozavimas

Šioje repozitorijoje pateikiamas Manto Lauručio bakalauro baigiamajame darbe „Mažmeninės prekybos prekių pardavimų prognozavimas taikant mašininio mokymosi metodus atsargų valdymo sprendimams“ naudotas programinis kodas.

Jupyter užrašinės vykdomos tokia tvarka:

1. `01_FE.ipynb` – sukuria papildomus kalendorinius ir išorinius kintamuosius.
2. `02_EDA.ipynb` – atlieka pradinę duomenų analizę.
3. `03_testines_aibes_sudarymas.ipynb` – atrenka 46 laiko eilutes modelių testavimui (taip pat vaizuodajama sklaidos diagrama pradinei duomenų analizei).
4. `04_ARIMA_SARIMAX.ipynb` – apmoko SARIMA ir SARIMAX bei sugeneruoja prognozes.
5. `05_LightGBM.ipynb` – apmoko LightGBM ir sugeneruoja prognozes.
6. `06_LSTM_NeuralForecast.ipynb` – apmoko LSTM ir sugeneruoja prognozes.
7. `07_REZULTATAI.ipynb` – apskaičiuoja metrikas ir palygina modelių rezultatus.
