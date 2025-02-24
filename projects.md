---
layout: page
title: Projects
cover-img: /assets/img/projects.jpg
subtitle: Something I have done
---

### Development of an Application Programming Interface (API) for Real Time Financial Data in the Julia Programming Language
<img src="/assets/img/wallst.jpg" width="700" height="350"> <br/><br/>
As there are only a limited number of free or low cost vendors for financial data stream, therefore, I built [a Julia-based REST API](https://github.com/Paliquant/PQPolygonSDK.jl) that can access real-time exchange data from a web-based API called [Polygon.io](https://polygon.io/). The wrapper is capable of accessing 15+ different market data endpoints from US stock exchanges and reduce the time cost in data preprocessing by 60%.<br/><br/><br/>


### Portfolio Optimization of NASDAQ-100
<img src="/assets/img/stock2.jpg" width="700" height="350"> <br/><br/>
In 2020, more and more people enter the investment market, making portfolio optimization a hot issue. We developed [a mixed-integer linear programming model](https://github.com/ycpan1012/Portfolio-Optimization-Model), which applied to the NASDAQ-100 in the US stock market, to determine the optimal holding ratio between every asset. We also investigate the optimal trade-off between rate of return and risk to maximize profit.<br/><br/><br/>


### Predicting Wine Preferences from Physicochemical Properties
<img src="/assets/img/wine.jpg" width="700" height="350"> <br/><br/>
[In this project](https://github.com/ycpan1012/Wine-Quality-Prediction), I analyzed data of red and white variants from Portuguese Vinho Verde wine to identify chemical properties that would influence the quality of win using R. Utilizing machine learning algorithms including logistic regression, KNN, support vector machine, and random forest, I found a model that can best identify properties that affect the quality of red and white wine and forecast the classification with over 90% accuracy.<br/><br/><br/>


### Development of a Computationally-Efficient Model for Simulation of Ionic Surfactant Micellization
<img src="/assets/img/morse.png" width="700" height="350"> <br/><br/>
Typically, it takes way more time to simulate solutions with ionic molecules such as sodium chloride since it is complicated to calculate the electrostatic forces in a dynamic system. In this project, a simpler model based on [Morse Portential](https://en.wikipedia.org/wiki/Morse_potential) was developed to approximate the intermolecular forces in ionic solution. The model not only successfully reproduces the critical micelle concentration (CMC), sphere-to-rod transition, and the salt effect with error lower thatn 10%, but also provide 4x lower computational cost for its calculation. [An extended research](https://www.aiche.org/conferences/aiche-annual-meeting/2019/proceeding/paper/376bg-modelling-micellization-rhamnolipid-biosurfactant-mesoscale-simulation) was presented on the AIChE Annual Meeting in Nov. 2019.
