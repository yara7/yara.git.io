
<yarametwally32@gmail.com>  
<https://www.facebook.com/yara.metwally.146>    
**Blog**  



**Diabetes prediction**   
**Introduction**    
Diabetes is considered as one of the deadliest and chronic diseases. Our project aims to predict diabetes based on many factors(features), like: age, family history, blood pressure, ... etc. You can check and download our dataset . [here](https://www.kaggle.com/edubrq/diabetes).      .

**Data Analysis**   
By looking into our dataset, we found that we have some missing data, so we solved this by replacing these missing values in each attribute with the mean value of the data of this attribute   

 |      | Pregnancies | Glucose | Blood pressure | Skin Thickness | Insuline | BMI |	Diabetes Pedigree Function |	Age
|------------ | ------------- | ---------- | --------- | ------------ | --------- | -------- |  
mean | 13.38 | 	121.86 | 	72.75 | 	26.6 | 	118.66 | 	32.45 | 	0.74 | 	33.24 |           
**Methods**     
When model is divided into train and validation, it means that the training part wasn't considered in the validation part, and similarly the validation part wasn't considered in the training part. That's why we used the cross-validation, so that the whole data will be considered in both training and validation. See following diagram show more explanation.[Source](https://www.kaggle.com/shrutimechlearn/step-by-step-diabetes-classification-knn-detailed?fbclid=IwAR36cCUBqicQlEJy_f8eKcNljb1GO1CKwIM5h0pEGa_ZozAgs7ySI6-Ol2k).    

![cross](https://scontent-hbe1-1.xx.fbcdn.net/v/t1.15752-9/74173849_470629050231734_1191953158075580416_n.png?_nc_cat=101&_nc_ohc=-H7DITJIJyYAQmrQiJ1wTiALhAA3qlCeP4FbEQXu3caEALooNKbYK5kUw&_nc_ht=scontent-hbe1-1.xx&oh=a005546569f41c5beb50ff99de9c2be1&oe=5E71C7F3)
    
    
We used 2 methods: Linear Discriminant Analysis and K Nearest Neighbors, for prediction.  
**Linear Discriminant & Logistic Regression**  
[Source](https://newonlinecourses.science.psu.edu/onlinecourses/sites/stat508/files/lesson09/image_01.gif).  

![LDA](https://newonlinecourses.science.psu.edu/onlinecourses/sites/stat508/files/lesson09/image_01.gif)  
**K Nearest Neighbors**  
[Source](https://www.researchgate.net/profile/Zainab_Sultani/publication/328146770/figure/fig3/AS:679495715536897@1539015811173/kNN-classification-example.ppm)    
![Knn](https://www.researchgate.net/profile/Zainab_Sultani/publication/328146770/figure/fig3/AS:679495715536897@1539015811173/kNN-classification-example.ppm)  
**Here are the results:** 

 |               |  	Linear Discriminant Analysis | K Nearest Neighbors Classifier
|------------ | ------------- |
Accuracy      |	               0.7708     |          	0.77             |      
Sensitivity  |  	0.5672  |     	0.92   |  
Specificity  |  	0.88  |  	0.49  | 
P-value(CI 95%) |  	0.0000339 |  	0.0005  |



