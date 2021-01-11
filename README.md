# Anomaly Detection in Energy Use
![energy_anomaly_detection.jpg](https://i.imgur.com/7bamvQA.jpg)

Despite efforts to reduce waste, energy consumption in buildings has steadily increased in the last decade. Commercial buildings are specifically at risk of using more energy than necessary because of faulty construction, malfunctioning equipment and many other issues. The key problem is that fault detection in buildings for excess energy consumption is often primitive, leading to large amounts of waste. This project was based on a large set of time series data provided by Schneider Electric for a competition. 

Check out our code or our [article on Medium](https://indialindsay1.medium.com/identifying-anomalies-in-commercial-energy-consumption-b0e72f569bb2) to see how we used XGBoost, Bayesian changepoint analysis, and more to pick out anomalies in data heavily influenced by seasonality and propose potential avenues for consumption optimization.

### The Data
[`Schneider Electric Exchange`](https://shop.exchange.se.com/en-US/apps/39025/detecting-anomalies-in-building-energy-usage)  

### Our Code 
[`Data Preprocessing`](https://github.com/lukembravo/energy_anomaly_detection/blob/master/Code/01%20Data%20preprocessing.ipynb) [`Data Visualization`](https://github.com/lukembravo/energy_anomaly_detection/blob/master/Code/02%20Data%20visualization.ipynb) [`Random Forest, XGBoost, & Nearest Neighbors Models`](https://github.com/lukembravo/energy_anomaly_detection/blob/master/Code/03%20Modeling%20-%20Random%20forests%2C%20XGBoost%2C%20Nearest%20Neighbors.ipynb)
[`Basic PyOD for Anomaly Detection`](https://github.com/lukembravo/energy_anomaly_detection/blob/master/Code/04%20Anomaly%20detection%20-%20basic%20PyOD.ipynb) 
[`Bayesian Change Points for Anomaly Detection`](https://github.com/lukembravo/energy_anomaly_detection/blob/master/Code/05%20Anomaly%20detection%20-%20Bayesian%20change%20points%20(Banpei).ipynb) [`Unsupervised KNN & Better PyOD for Anomaly Detection`](https://github.com/lukembravo/energy_anomaly_detection/blob/master/Code/06%20Anomaly%20detection%20-%20KNN%20and%20better%20PyOD.ipynb)

### Our Team
Luke Bravo: [`LinkedIn`](https://www.linkedin.com/in/luke-bravo/)  
Ram Kapistalam: [`GitHub`](https://github.com/rkapistalam) [`LinkedIn`](https://www.linkedin.com/in/ramkapistalam/)  
India Lindsay: [`GitHub`](https://github.com/indialindsay) [`LinkedIn`](https://www.linkedin.com/in/india-lindsay/)  
Mauricio Morales: [`LinkedIn`](https://www.linkedin.com/in/playmaumo/)  
Jocelyne Walker: [`GitHub`](https://github.com/jocelynewalker) [`LinkedIn`](https://www.linkedin.com/in/jocelynewalker/)  
