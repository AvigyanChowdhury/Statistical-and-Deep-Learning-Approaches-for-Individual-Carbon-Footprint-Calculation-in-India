# Statistical-and-Deep-Learning-Approaches-for-Individual-Carbon-Footprint-Calculation-in-India
<h2>Abstract.</h2>
This research addresses a significant gap in knowledge by investigat-
ing the intricate connection between individual behaviours and carbon footprints
in India. The study explored this relationship using statistical and deep-learning
techniques on individual carbon emission data. The data collection process in-
volved an interactive survey covering various factors such as lifestyle choices, di-
etary preferences, transportation habits, energy usage patterns, and demographic
details. Label encoding and standard scaling techniques were applied to prepro-
cess the data. The subsequent phase models several statistical and deep learning
techniques to predict carbon footprints. These models were thoroughly analyzed
to conclude the primary factors, address pertinent research questions on sustain-
able development in India, and guide future investigations. Notably, the findings
emphasized the pivotal role of different lifestyle choices in carbon footprint cal-
culation.

<table border="1">
  <caption>Performances of different regression models for carbon footprint calculation</caption>
  <tr>
    <th>Model</th>
    <th>MSE &darr;</th>
    <th>MAE &darr;</th>
    <th>R2 &uarr;</th>
  </tr>
  <tr>
    <td>Linear Regression (LiR)</td>
    <td>25.1485</td>
    <td>18.6958</td>
    <td>0.4821</td>
  </tr>
  <tr>
    <td>Lasso Regression (LaR)</td>
    <td>22.8057</td>
    <td>17.3657</td>
    <td>0.6199</td>
  </tr>
  <tr>
    <td>Ridge Regression (RR)</td>
    <td>22.1381</td>
    <td>17.9152</td>
    <td>0.6046</td>
  </tr>
  <tr>
    <td>ElasticNet Regression (ER)</td>
    <td>43.7466</td>
    <td>23.2843</td>
    <td>0.3315</td>
  </tr>
  <tr>
    <td>Decision Tree (DT)</td>
    <td>19.6267</td>
    <td>11.8491</td>
    <td>0.7002</td>
  </tr>
  <tr>
    <td>Random Forest (RF)</td>
    <td>7.5875</td>
    <td>8.3584</td>
    <td>0.7786</td>
  </tr>
  <tr>
    <td>Gradient Boosting (GB)</td>
    <td>3.8044</td>
    <td>7.5482</td>
    <td>0.7989</td>
  </tr>
  <tr>
    <td>Support Vector Regression (SVR)</td>
    <td>44.1427</td>
    <td>26.2897</td>
    <td>0.5824</td>
  </tr>
  <tr>
    <td>K-Nearest Neighbors (KNN)</td>
    <td>53.4981</td>
    <td>28.3549</td>
    <td>0.4412</td>
  </tr>
  <tr>
    <td>Multi-layer Perceptron (MLP)</td>
    <td>1.6268</td>
    <td>1.0217</td>
    <td>0.8963</td>
  </tr>
  <tr>
    <td>Long Short-Term Memory (LSTM)</td>
    <td>2.6268</td>
    <td>1.0217</td>
    <td>0.8163</td>
  </tr>
  <tr>
    <td>Convolutional Neural Network (CNN)</td>
    <td>8.8010</td>
    <td>3.4491</td>
    <td>0.7736</td>
  </tr>
</table>
![comparison](https://github.com/AvigyanChowdhury/Statistical-and-Deep-Learning-Approaches-for-Individual-Carbon-Footprint-Calculation-in-India/assets/146307887/ec11a4f8-713b-4ca1-8193-6f778e679d3a)
