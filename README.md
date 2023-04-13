# Cyclist-travel-lane-and-helmet-detection-
This project aims to detect if a cyclist is traveling on a cyclist travel lane &amp; wearing a helmet.  

A simplified method for the detection of cyclist travel lanes and helmets is proposed in this project. 
This vision-based system is mainly divided into two different detectors. 
The first detector detects whether the cyclist in the input source is traveling on the dedicated cyclist travel lane. 
The second detector detects whether the cyclist in the previous input source has a helmet on his/her head.

## Dataset

The vision-based cyclist travel and helmet detection system is trained and tested on a custom dataset containing 
17,000 images. These images belong to four distinct classes: cyclist lane, non-cyclist lane, cyclist with a helmet, 
and cyclist without a helmet.


![image](https://user-images.githubusercontent.com/75938096/231680129-e8fd6e03-c083-494a-bfe3-63ff09563a87.png)


#### Dataset Link:
Cyclist lane: 1500 images 
https://drive.google.com/drive/folders/1KyDOpBIP1kZ_lhzHTBkzFNAXUQKHCbLy?usp=sharing

Normal lane: 1500 images 
https://drive.google.com/drive/folders/10QLSltYCC8YEzK9IYc_eBcG1B--Vb6B0?usp=sharing

Cyclist with helmet: 7000 images 
https://drive.google.com/drive/folders/1zArOiEzDqZStInFcxIfqMjdmH9ih4fl_?usp=sharing

Cyclist without helmet: 7000 images
https://drive.google.com/drive/folders/1S6hSSIp1xk9pxygNfKaxPaoNHOFKsNx0?usp=sharing


## Working 

- The classification was done using multiple algorithms for both cyclist lane detection and helmet detection. 
- The algorithms such as decision tree, random forest, KNN, SVM, GNB, and AdaBoost were implemented on training data. 
- The training and testing images were taken such as there were 80% training images and 20% testing images.

![image](https://user-images.githubusercontent.com/75938096/231680625-89acbba2-0a03-4902-8e8e-6613f343a64f.png)


## Performance Evaluation 

Cyclist travel lane detection: 

![image](https://user-images.githubusercontent.com/75938096/231681802-5dda81fc-d431-457d-9d39-ce7ccafea799.png)

Cyclist’s helmet detection:

![image](https://user-images.githubusercontent.com/75938096/231682300-71384c76-0550-435f-91ed-727d575bddbb.png)






