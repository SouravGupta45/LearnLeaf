# LearnLeaf
* ## Overview

The project is based on a computer vision binary classification problem where our primary goal is to detect if a plant is diseased or not by seeing the  picture of its leaf.

Agricultural productivity is something on which the economy highly depends. This is one of the reasons that disease detection in plants plays an important role in the agriculture field, as having disease in plants is quite natural. If proper care is not taken in this area then it causes serious effects on plants and due to which respective product quality, quantity or productivity is affected. For instance a disease named little leaf disease is a hazardous disease found in pine trees in the United States. Detection of plant disease through some automatic technique is beneficial as it reduces a large work of monitoring in big farms of crops, and at a very early stage itself it detects the symptoms of diseases i.e. when they appear on plant leaves.

* ## DATASET

The dataset we used in this implementation is *PLANT VILLAGE DATASET* and can be downloaded from [here](https://www.kaggle.com/emmarex/plantdisease).The dataset contained more than 20000 images but we have used 200 images from each folder which made our total images around 7980. 
Displaying some of it with its label :-

![alt text](https://github.com/SouravGupta45/LearnLeaf/blob/main/Output/Dataset.png "Plant Village Dataset")



* ## Model Architecture
We used a CNN architecture.

![alt text](https://github.com/SouravGupta45/LearnLeaf/blob/main/Output/Model_Summary.png "Model Summary")


* ## EXPERIMENTATION
 
We tried different model Architecture with the same training set and plotted graphs for accuracy vs epoch . There was a lot of information that could be extracted from it.  We found that our CNN model Performed well out of other models and it gave us satisfactory results with an accuracy of dash and a loss of dash . The plot for Xyz model shows that the valid accuracy is not much comparable with train accuracy which shows that the model isnt overfitting.

* ## EXPERIMENTATION PLOTS

    1. ### SVM MODEL
    
    ![alt text](https://github.com/SouravGupta45/LearnLeaf/blob/main/Output/SVM.png "SVM OUTPUT")
            
    2. ### REGRESSION MODEL
    
    ![alt text](https://github.com/SouravGupta45/LearnLeaf/blob/main/Output/Regression.png "Regression OUTPUT")

    3. ### CNN MODEL
    
       ![alt text](https://github.com/SouravGupta45/LearnLeaf/blob/main/Output/Image1.png "CNN OUTPUT")
       
 
* ## CONCLUSION
We made different experimentation with different we different model architecture  on the given PLANTVILLAGE dataset and forecasted a conclusion on the result that the model CNN performs much better than the other model and can be used to design a plant detection system.

# STREAMLIT APP
*Make Sure to install the requirements.txt file before using the app.


   ![alt text](https://github.com/SouravGupta45/LearnLeaf/blob/main/Output/AppUI.png "APP UI")
   ![alt text](https://github.com/SouravGupta45/LearnLeaf/blob/main/Output/AppUI1.png "APP UI")

