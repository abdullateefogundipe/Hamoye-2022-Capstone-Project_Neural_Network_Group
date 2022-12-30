


### 1.0 INTRODUCTION


Generally, in sports, injuries are disliked but unavoidably common. It doesn’t matter whether a sport is played individually or as a team, injuries can cause significant damage physically, mentally, psychologically, financially and in extreme cases severe health issues and death. It is therefore essential to understand the key factors that contribute to players fitness and performance which include the health level of athletes, emotional status, magnitude of exercise and its physical intensity.


The ability to forecast the manifestation of a provocative injury event is difficult due to the factors related to the individual athlete and external factors and unforeseeable circumstances such as contact with other players. Therefore, we have focused our model to predicting injuries based on the training data gathered.


###   2.0 AIMS AND OBJECTIVES

The aim of this project was to develop a machine learning model that can predict injuries based on the training regimen of an athlete. This can be used to make injury prevention approaches easier to develop.


###   3.0 Flow Process

![image](https://user-images.githubusercontent.com/16369782/201543738-c7c3f881-f81a-40ca-8277-8defef4db721.png)



###   4.0 Model Training and Evaluation

As shown from the table below, the project prediction was based on three models on the weekly approach dataset namely, the DNN, K-NN, and XGBoost algorithm while on the daily approach, the project implemented four models, namely, DNN, K-NN and XGBoost. Thus, the best-performing model on the daily dataset was K-NN with an accuracy of 97%. The weekly dataset on the other hand, k-NN was the best model with about 97% accuracy (f1-score). Furthermore, the feature with the highest influence on injury status was the ‘sum of max km’ with about 34.5 to 4.7 km per day according to explorations on the data. 

![image](https://user-images.githubusercontent.com/16369782/201543754-f3154d87-a8c9-4b80-9461-d5b6dab00dea.png)



####   5.0 Machine Learning Model Deployment
[Deployment Link](https://joshuaowie-hamoye-2022-capston-day-injury-prediction-app-6hl92m.streamlit.app/)


```
https://joshuaowie-hamoye-2022-capston-day-injury-prediction-app-6hl92m.streamlit.app/
```


A web application was built to illustrate the daily injury prediction from runners training routine or schedule using the KNN model. The web application takes in imputations of 10 training activities or routines of runners over a course of 7 days and predicts if a runner will have an injury or not when following such plan/routine. The application was created and deployed on streamlit cloud, ready for consumption. The figure below shows the deployment dashboard.

![image](https://user-images.githubusercontent.com/16369782/201544104-e8954bca-2358-4a04-ae74-f2a7a66244ec.png)

![image](https://user-images.githubusercontent.com/16369782/201544121-d662d204-1c92-4590-9d84-3d6db3a16862.png)


###   6.0 Power BI Visualisation Dashboard
![image](https://user-images.githubusercontent.com/16369782/201544228-45eb067e-69dc-4c89-bc36-6cf71d42f90e.png)


###   7.0 Conclusion

Finally, to demonstrate consumption of the developed model, the generated k-NN model was deployed using a streamlit cloud framework. The web application uses 10 training activities over 7 days. Thus, the overall system was a success as the complete system was able to provide the required prediction according to the 70 different features. The system which is invariably a model for future expansion can be provided with other features for robustness and more functionality enhancement. Features such as high-level security, Artificial Intelligent (AI) model, and Portable mobile application software to enhance accessibility.

