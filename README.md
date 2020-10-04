# Predicting-Headaches-based-on-Weather

The project predicts the probability of a headache to a given student based on the weather conditions of Halifax and the work schedule. It was a group work and developed as part of the assignment towards the fulfillment of CSCI6515 - Machine Learning for Big Data. 

The below image shows the data about the occurence of headache. 

![Journal](https://user-images.githubusercontent.com/20052459/95027144-b6eaae00-066c-11eb-9f3b-a139533829da.PNG)

The figure shows the workout schedule of a student. 

![workout](https://user-images.githubusercontent.com/20052459/95027194-0c26bf80-066d-11eb-903b-daf982633afe.PNG)

### Data pre-processing
The weather data of Halifax has been obtained from [here](https://climate.weather.gc.ca/). The site contains the weather data from several stations in Halifax. The data from all the stations has been collected and average values of all the stations has been used to make the training data. The prediction was made using weather data from Sept. 01, 2020 to Sept.30, 2020. 

### Descriptive Analysis
An analysis of the data was made in order to get insights about the various features. The following figures shows some of the analysis carried out. Refer `Code.ipynb` notebook for more analysis.

![index_1](https://user-images.githubusercontent.com/20052459/95027641-8c9aef80-0670-11eb-8dbd-44daf6acd953.png)
![index_2](https://user-images.githubusercontent.com/20052459/95027642-8d338600-0670-11eb-981c-d88f4fadf89a.png)
![index](https://user-images.githubusercontent.com/20052459/95027643-8d338600-0670-11eb-9beb-2bb07d207631.png)


### Model Building and Prediction
As seen from the above figures, the data is highly imbalance with `Headache` as a minority class. In order to overcome this, several models have been build with hyper-parameter tuning and sampling techniques. The below figure shows the comparision of performance of different classifiers.
![performance](https://user-images.githubusercontent.com/20052459/95027532-a556d580-066f-11eb-98e8-0e2e472ca9d5.PNG)

### Team
- Abhijeet Singh  
- Tayab Soomro  
- Rashidul Islam  
- Shrey Rameshbhai Vaghela  
- Dhruv Tarpara 

### References
Bach, M., Werner, A., Zywiec, J., & Pluskiewicz, W. (2017). ​The study of under- andover-sampling methods’ utility in analysis of highly imbalanced data on osteoporosis​.https://doi.org/​10.1016/j.ins.2016.09.038

He H., & Garcia, E. A. (2009). Learning from Imbalanced Data. In ​IEEE Transactions onKnowledge and Data Engineering​ (Vol. 21, Issue 9, pp. 1263–1284).https://doi.org/​10.1109/tkde.2008.239

Khalid S., Khalil, T., & Nasreen, S. (2014). ​A survey of feature selection and feature extractiontechniques in machine learning​.http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6918213Prince

P. B., Rapoport, A. M., Sheftell, F. D., Tepper, S. J., & Bigal, M. E. (2004). The effect ofweather on headache. ​Headache​, ​44​(6), 596–602.Shekar, B. H., & Dagnew, G. (2019). Grid Search-Based Hyperparameter Tuning andClassification of Microarray Cancer Data. In ​2019 Second International Conference onAdvanced Computational and Communication Paradigms (ICACCP)​.https://doi.org/​10.1109/icaccp.2019.8882943

Towards AI Team. (2019, May 16). ​How, When, and Why Should You Normalize / Standardize /Rescale Your Data?​ Towards AI — The Best of Tech, Science, and Engineering.https://towardsai.net/p/data-science/how-when-and-why-should-you-normalize-standardize-rescale-your-data-3f083def38ff
