Journal Articles 

Corina 

Strength prediction and optimization for ultrahigh-performance concrete with low-carbon cementitious materials – XG boost model and experimental validation
https://www.sciencedirect.com/science/article/pii/S0950061823013193?ref=pdf_download&fr=RR-2&rr=985d15bd5c16a4c4
This article aims to determine the compressive strength of ultra high performance concrete using recycled materials when made in order to make the concrete cheaper to create to reduce greenhouse gas emissions it creates in its current state. The study focused on the 28 day compressive strength as the main output. 
The study uses XG Boost method due to it being able to pick outliers without introducing much sensitivity to the model. The model predicted with a 95.6% accuracy and was always within a 15% error margin.  
The original benchmarking model suggested overfitting due to the differences between the test data and the training data. Due to the overfitting the study fine tuned the model optimizing hyper parameters that were found to be most significant. The study suggests that for the best results other properties should be analyzed such as durability in order to better improve the model.
There were 297 collections of data from 21 different studies. They evaluated 27 variables and found that only 12 of them were statistically significant. The raw data was not normalized in the case of this study. 

Analysis of the 10-day ultra-marathon using a predictive XG boost model
https://uwf-flvc.primo.exlibrisgroup.com/discovery/fulldisplay?docid=cdi_doaj_primary_oai_doaj_org_article_986cc6e5973948ed919ab7ac5176113a&context=PC&vid=01FALSC_UWF:UWF&lang=en&search_scope=CentralIndex&adaptor=Primo%20Central&tab=CentralIndex&query=any,contains,XG%20Boost&offset=10&pcAvailability=true
This study aims to predict the running speed based off of an athlete’s individual characteristics to determine which characteristic may influence speed the most since there is a lack of data when it comes to athletes who perform 10-day ultra-marathons. Based on other studies that have been conducted in the past the authors hypothesize that the fastest 10-day runners originate from Europe. 
The model chosen for this study was the XG Boost Regression Model which was used to predict running speed. The study used and iterative process called the hold-out evaluation in order to train and evaluate the model. The model determined that origin of the athlete was the most influential factor when determining an athlete's running speed. Almost all factors were significant except gender, if the surface was concrete, and the event id. Age group was found to be the second most important factor. The model also identified that running on asphalt is faster than running on any other surface. 
Limitations of the model start with limited data, the origin of the athletes mostly came from USA, Russia, Germany, Ukraine, the Czech Republic, and Slovakia. 
The data was provided by the Deutsche Ulatramarathon Vereinigung (DUV) which contains race data with the athletes first and last name, age group, gender, country of origin, race location, year, race performance in distance and average running speed, as well as the type of race and the running surface. The dataset contained 958 races from 452 runners from 46 countries. Based on the dataset analysis the study found that the fastest runners originated from Finland and Israel. 

Identifying clinical risk factors correlate with suicide attempts in patients with first episode major depressive disorder
https://www.sciencedirect.com/science/article/pii/S0165032721008260
This article aims to identify the major indicators correlated with suicide attempts. The study used data from 1,718 patients who were recruited from the Department of Psychiatry First Clinical Medical College of Shanxi Medical University in Taiyuan, China. These patients had been diagnosed with major depressive disorder. They included patients between the ages of 16-60 years old who had never received psychotropic medications or other treatments, and who had no serious illnesses. These patients were divided into those who had attempted suicide before and those who had not. Those who had attempted suicide were divided into recenter attempters with less than or equal to 14 days and those who have attempted more than 30 days prior to the assessment.
It is important because clinicians are expected to make a determination if the patient is at risk for a suicide attempt. There has been limited data produced in the last 50 years and many studies have been based on this same set of data.
The chi-squared test, Kruskal-Wallis test, student t-test, and the Mann-Whitney U test were used to compare the clinical variables between the groups. An XG Boost algorithm was created from gradient boosted decision trees and assembly algorithms were created. These two algorithms were combined by bagging and boosting which increased the XG-Boost performance. 60% of the data was used to train the model and 40% was used to test the model. The performance of the model was evaluated using AUC and ROC curves. The model found that if a depressed person has psychotic systems such as excitement, hostility, and anxiety along with elevated thyroid function test it is highly likely that the patient may commit suicide within 14 days.
The major limitation in this study is that is does not predict risk factors for future suicidal behavior it is a retrospective model, therefore further study will need to be conducted from a prospective analysis. Variables that could widely influence the model outcome were also left out such as family psychiatric history, social support networks etc. and these are items that should be included moving forward with a prospective study.

Hybrid Machine Learning Approaches for Predicting and Diagnosing Major Depressive Disorder
https://www.proquest.com/docview/3046786375?accountid=14787&pq-origsite=primo&sourcetype=Scholarly%20Journals
This paper’s goal is to test multiple machine learning models that predict and diagnose major depressive disorder using clinical, demographic, and electroencephalography (EEG) data. The dataset includes EEG data from people diagnosed with MDD, patient information such as age, gender, medication history, symptom severity, annotations marking the EEG data, and metadata surrounding the EEG data.
This study is important because the machine learning models can help provide valuable insights for more effective intervention and personalized treatment strategies.
The data was split for 70% used for training and 30% used for testing. The top 20  features for the models were selected by performing information gain, gain ratios, gini decrease and chi-squared tests. Six models were developed and tested using the following methodologies logistic regression using ElasticNet, SVM with a linear kernel, Random Forest, XGBoost, LightGBM, and CatBoost. Since my focus is XG Boost those are the models I am interested in. The XG Boost uses extreme gradient boosting and avoids overfitting by using regularization methods. The XG Boost model was set to the maximum depth of the tree as 6 and the learning rate as 0.30. The CatBoost model resulted in the best performance but the XG Boost model was very close in model performance. The XG Boost model resulted in an accuracy of 92.5%, precision of 76% and recall of 94.2% while the CatBoost model resulted in an accuracy of 93.1%, precision of 76.4% and recall of 97.9%.  This study further backed up these finding by performing K-fold cross validation and ROC analysis.
More research is to be done on exploring additional attributes and further fine tuning of the hybrid models with the addition of more diverse datasets. While the model can identify major depressive disorder more personalized intervention suggestions could come with additional datasets.

Prediction of seasonal infectious diseases based on hybrid machine learning approach
https://research.ebsco.com/c/imx7og/viewer/pdf/ff4a3en7vb?route=details&auth-callid=79a2ec32-2fd0-4dca-917c-fb72fd1265f0
The goal of the article is to predict seasonal disease outbreaks in order to gain control of these epidemics decreasing the spread of the outbreaks.
It is important to monitor and predict potential disease outbreaks in order to prevent massive casualties as seen with the COVID-19 outbreak in 2020/2021. 
The data was gathered from multiple sources in the Madurai district between 2019 and 2020 with 21,764 samples with 29 features each but 26 being selected for analysis. First a Antlion Optimization Algorithm (ALO) was utilized to determine the best feature selection. The ALO algorithm uses binary encoding and the best antlion was kept in each iteration. Once the features were selected a random forest algorithm integrated with the XG Boost methodology was used to classify the diseases. The Radom forest was trained using the bootstrap sampling approach two thirds of the data was used for training and one third was used for testing. No attribute was picked as internal node but a random max depth attribute was chosen to serve as a branching node. For further accuracy XG Boost was used to create scalable and adaptable tree optimization which sped up the original random forest model.
Using the ALO method the main constraint is that it is constrained by the exploration rate. The data limitation is that only one district was used for prediction on of the model so it is most accurately used on for that specific district so more work will need to be done to expand the model. The accuracy of the model was 96.17% with a precision of 93.95% and a recall rate of 95.86%

The Impact of the U.S. Macroeconomic Variables on the CBOE VIX Index
https://www.proquest.com/docview/2642416749?accountid=14787&pq-origsite=primo&sourcetype=Scholarly%20Journals
The purpose of the paper is to determine the impact macroeconomic variables have on the stock markets volatility index which is often used a fear index of investor sentiments. 
The study is important because this is an analysis that has not quite been done yet, most studies on the VIX revolve around investor returns or only looked at regression techniques. 
Daily data for the VIX was used from the period May 2007 to December 2021 when there was missing macro data for a particular day the data was forward filled. Macro data with large delays in releases was not chosen for this study while data that only had weekly delays was chosen. There were 23 daily macro features and 32 weekly macro features chosen. Both daily and weekly models are considered to create a more robust analysis. The daily models were tested on 100 trading days while the weekly models were tested on 50 weeks. Multiple model types were analyzed, logistic regression model, light gradient boosted machine classifier, and extreme gradient boosting classifier. To analyze performance this study used the Matthew’s correlation coefficient (MCC) on top of the standard accuracy, precision, recall, and F1 scores. 
The Daily XG Boost model resulted in a mean accuracy score of 55.62% and a validation of 62% with the MCC of 0.2793 which was found to be statistically significant suggesting the model has predictive power. This model determined that the most important feature was economic policy uncertainty index: infectious disease tracker. The Weekly XG Boost model resulted in lower performance results. None of the models returned extremely high performance results which suggests that more work needs to be done and that there is a potentially better model selection then the three analyzed. 

Abigail Penza
Research and application of XGBoost in imbalanced data
https://journals.sagepub.com/doi/full/10.1177/15501329221106935

An investigation of XGBoost-based algorithm for breast cancer classification
https://www.sciencedirect.com/science/article/pii/S2666827021000773

A Tutorial and Use Case Example of the eXtreme Gradient Boosting (XGBoost) Artificial Intelligence Algorithm for Drug Development Applications
https://ascpt.onlinelibrary.wiley.com/doi/full/10.1111/cts.70172

Research on XGboost academic forecasting and analysis modelling
https://iopscience.iop.org/article/10.1088/1742-6596/1324/1/012091/meta

Improving Diagnosis of Depression With XGBOOST Machine Learning Model and a Large Biomarkers Dutch Dataset (n = 11,081)
https://www.frontiersin.org/journals/big-data/articles/10.3389/fdata.2020.00015/full?field&journalName=Frontiers_in_Big_Data&id=523466

Application of a data-driven XGBoost model for the prediction of COVID-19 in the USA: a time-series study 
https://bmjopen.bmj.com/content/12/7/e056685.abstract

Aabiya Mansoor
XGBoost Model and Its Application to Personal Credit Evaluation
https://ieeexplore.ieee.org/abstract/document/8988224

Improved Multiclassification of Schizophrenia Based on Xgboost and Information Fusion for Small Datasets
https://onlinelibrary.wiley.com/doi/full/10.1155/2022/1581958

Child mental health predictors among camp Tamil refugees: Utilizing linear and XGBOOST models
https://www.proquest.com/docview/3105702596/D8E1D25BB54D44E6PQ/2?accountid=14787&sourcetype=Scholarly%20Journals

The prediction of self-harm behaviors in young adults with multi-modal data: an XGBoost approach
https://www.sciencedirect.com/science/article/pii/S2666915324000088

Improving Diagnosis of Depression With XGBOOST Machine Learning Model and a Large Biomarkers Dutch Dataset (n = 11,081)
https://pmc.ncbi.nlm.nih.gov/articles/PMC7931945/

Multiclass Classification of Mental Health Disorders Using XGBoost-HOA Algorithm
https://www.researchgate.net/publication/386988004_Multiclass_Classification_of_Mental_Health_Disorders_Using_XGBoost-HOA_Algorithm

Madelyn Champion

XGBoost To Enhance Learner Performance Prediction
https://www.sciencedirect.com/science/article/pii/S2666920X24000572

Research and application of XGBoost in imbalanced data
https://journals.sagepub.com/doi/full/10.1177/15501329221106935

XGBoost: A Scalable Tree Boosting System
https://dl.acm.org/doi/10.1145/2939672.2939785

eXtreme gradient boosting algorithm with machine learning: A review
https://www.researchgate.net/publication/371202498_eXtreme_gradient_boosting_algorithm_with_machine_learning_A_review

An XGBoost-Based Knowledge Tracing Model
https://link.springer.com/article/10.1007/s44196-023-00192-y

XGBoost, A Novel Explainable AI Technique, in the Prediction of Myocardial Infarction: A UK Biobank Cohort Study
https://pmc.ncbi.nlm.nih.gov/articles/PMC9647306/









