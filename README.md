                                       INTRODUCTION:
  Photoplethysmogram (PPG) signals have in recent years been researched quite a bit and studies have shown that PPG signals contain information about the vital signs of a person especially the BP, the signals make use of  Infra-red light which when travelling through  tissues in the body of a person is absorbed to an extent and reflected back, the reflected light is indicative of the blood flow in a person which helps users derive conclusions on vital signs. 
PPG signals have been used in cuff-less instruments with Machine Learning as the system to extract informative features from the signal and predict BP from it, but obstacles such as poor signal quality, lack of accuracy of Machine Learning algorithms, not enough user readings etc. have hindered the progress of the method. One of the remedies to improving the accuracy of Machine Learning algorithms has been using optimum Hyper-parameters in the algorithm with studies showing that it could improve the accuracy by up to 40%. Hyper-parameter tuning methods of Grid Search, Random Search and Bayesian Search have been the most commonly used Hyper-parameter tuning methods used and have been found in recent years to be effective on improving the Machine Learning algorithms efficiency when working with Medical data. 

                                        PROBLEM DEFINITON:
                                        
The cuff-less measurement of BP has advantages over the cuff-based measurement in the fact that it logistically easier for the user to use the device and is not physically tiring on the user to record the measurements. One of the main drawbacks of the cuff-less based measurement is the fact that the system which is used in the instrument can suffer from inaccuracy. Machine Learning has been increasingly used in recent times as a system for predicting BP in cuff-less measurements, but it suffers from a lot of roadblocks which prevent it from reaching its full potential, one being using optimum Hyper-parameters for its Algorithms. Hyper-parameters are an integral part of any Machine Learning algorithm and tuning the values for the parameters is as import as selecting the algorithm. There are different questions which needs to be answered before Hyper-parameter tuning , which Hyper-parameters in an algorithm to take up for tuning, the value ranges to be specified for each Hyper-parameter to be tuned , the evaluation metric to be taken into consideration to evaluate the accuracy of the tuning method etc.

                                        PROJECT AIM:
                                        
The aim of the Project is to use different Hyper-parameter tuning methods on Machine Learning algorithms and analyze whether the tuning methods can improve the Machine Learning algorithms accuracy in predicting Systolic Blood Pressure (SBP) from PPG derived features.

                                        PROJECT OBJECTIVES:
                                        
The main objectives of the Project would be to-
1.	To do a literature study on the current implementations of Machine Learning algorithms which predict BP from PPG signals with respect to cuff-less devices.
2.	To develop three Machine Learning algorithms to predict SBP from PPG signals which were taken from users in a clinical environment.
3.	To conduct three Hyper-parameter tuning methods on the selected Machine Learning algorithms.
4.	To analyze whether there is an improvement in the accuracy of the Machine Learning algorithms to predict SBP after the Hyper-parameter tuning methods have been conducted.

                                          ML Algorithms& Tuning Methods
The Project based on extensive background study took 3 Machine Learning algorithms which were Support Vector Regressor, Random Forest Regressor and Neural Networks to predict the Systolic Blood Pressure from a dataset of PPG derived features and then tried to analyze whether introducing Hyper-parameter tuning methods of Grid Search, Random Search and Bayesian Search had a positive impact on the algorithm’s accuracy to predict Systolic Blood Pressure.


                                                   CONCLUSION
 The Project has taken 3 Machine Learning algorithms to predict Systolic Blood Pressure from PPG derived features in the context of cuff-less estimation. To tackle some of the issues which could hinder the efficiency of Machine Learning algorithms, the Project took 3 Hyper-parameter tuning methods to analyse whether the Hyper-parameter tuning methods can have a positive impact on the prediction accuracy of the Machine Learning algorithms. The Project concludes with the following points:

• In total 30 features were taken for Machine Learning analysis which were a combination of PPG and Biometric features. The feature selection method showed that only 24 among the 30 were informative of the Systolic Blood Pressure with Age of the user being the most informative feature among the 30 while the Fundamental component magnitude of the PPG signal was found to be the most informative PPG feature.

•	Among the 3 Hyper-parameter tuning methods the Random Search tuning method improved the accuracy of all the 3 algorithms which were Support Vector Regressor, Random Forest Regressor and Neural Network in predicting the Systolic Blood Pressure while the Grid Search tuning method improved the accuracy of the Support Vector and Random Forest Regressors  and the Bayesian Search improved the accuracy of the Random Forests and Neural Network models.

•	The best Hyper-parameter tuned algorithm in terms of MAE was the Bayesian Search tuned Neural Network model which got down to 12.60 mmHg from 12.98 mmHg which was the MAE of the non-Hyper-parameter tuned Neural Network, with the improvement in accuracy being 3%.

•	The Random Search tuning method took the lowest time to find the optimum Hyper-parameters for all the algorithms by taking around 1.3 minutes in average while the Bayesian Search took 4 and Grid Search took 130 minutes on average respectively.

