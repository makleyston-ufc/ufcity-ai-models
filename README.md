<!-- <div class="view">
<img src="https://makleyston-ufc.github.io/ufcity/assets/img/ufcity-logo.png" alt="UFCity" width="200"/>
<p><b>Building smart cities smartly.</b></p>
</div>

<div class="view">
  <a href="https://makleyston-ufc.github.io/ufcity"> <img src="https://img.shields.io/badge/UFCity_webpage-0076D6?style=for-the-badge&logo=internetexplorer&logoColor=white"> </a>

  <a href="https://github.com/makleyston-ufc/ufcity-ai-models"> <img src="https://img.shields.io/badge/View_on_GitHub-181717?style=for-the-badge&logo=github&logoColor=white"> </a>
</div> -->

# UFCity AI models

## [Slow traffic forecast](/slow-traffic-forecast)
**Dataset:** [Urban traffic density in cities](https://www.kaggle.com/datasets/tanishqdublish/urban-traffic-density-in-cities?resource=download)

**Objetivo:** identificar lentidão na cidade com base nas condições, climáticas, hora, dia, horário de pico, acidentes e densidade do tráfego da cidade.

**Método utilizado:** Regressão baseada em árvores de decisão.

**Ferramenta utilizada:** Random Forest Regressor

**Resultado:**  
- Mean Squared Error: 1.289537341629248
- R2 Score: 0.9688701457764887

<img src="./slow-traffic-forecast/images/chart.png" alt="UFCity" width="600" height="400"/>

<a href="https://github.com/makleyston-ufc/ufcity-ai-models/tree/main/slow-traffic-forecast"> <img src="https://img.shields.io/badge/View_on_GitHub-181717?style=for-the-badge&logo=github&logoColor=white"> </a>

## [weather-forecast](/weather-forecast)
**Dataset:** [CityPulse](http://iot.ee.surrey.ac.uk:8080/datasets.html#weather)

**Objetivo:** prever tendência de séries com base em dados climáticos, como pressure, humidity, temperature, wind direction, and speed sensors.

**Método utilizado:** Regressão baseada em médias móveis para analisar tendências de séries.

**Ferramenta utilizada:** AutoRegressive Integrated Moving Average (ARIMA)

**Resultado:**  
- hum  ARIMA(5,1,2)(0,0,0)[0]          
- tempm  ARIMA(1,1,3)(0,0,0)[0]          
- wspdm  ARIMA(0,1,2)(0,0,0)[0]          
- wdird  ARIMA(4,1,4)(0,0,0)[0]
- pressurem  ARIMA(4,1,5)(0,0,0)[0]          
- dewptm  ARIMA(2,1,2)(0,0,0)[0]

<div style="display: flex; flex-direction: row;">
  <img src="./weather-forecast/images/chart-temp.png" alt="UFCity" width="300" height="200" style="margin-right: 10px;">
  <img src="./weather-forecast/images/chart-pressurem.png" alt="UFCity" width="300" height="200" style="margin-right: 10px;">
  <img src="./weather-forecast/images/chart-wdird.png" alt="UFCity" width="300" height="200">
</div>


<a href="https://github.com/makleyston-ufc/ufcity-ai-models/tree/main/weather-forecast"> <img src="https://img.shields.io/badge/View_on_GitHub-181717?style=for-the-badge&logo=github&logoColor=white"> </a>