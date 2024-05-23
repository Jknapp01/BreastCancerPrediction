# BreastCancerPrediction

This notebook aims to utilize a machine learning model to predict whether breast cancer patients have malignant or benign tumors. By analyzing various medical and diagnostic data, the model will be trained to distinguish between the two types of cancer, potentially aiding in early detection and treatment decisions. The implementation of this predictive tool could provide significant benefits in clinical settings, improving the accuracy and speed of diagnosis for breast cancer patients.

**If you find this notebook helpful, please upvote and consider reviewing some of my other work.**

I learn from your feedback 🙂

*Some information about this dataset follows:*

### 🦠 **Breast Cancer Data Set**
This dataset contains the characteristics of patients diagnosed with cancer. The dataset contains a unique ID for each patient, the type of cancer (diagnosis), the visual characteristics of the cancer and the average values of these characteristics.

### 📚 **The main features of the dataset are as follows:**
* **id:** Represents a unique ID of each patient.
* **diagnosis:** Indicates the type of cancer. This property can take the values "M" (Malignant - Benign) or "B" (Benign - Malignant).
* **radius_mean, texture_mean, perimeter_mean, area_mean, smoothness_mean, compactness_mean, concavity_mean, concave points_mean:** Represents the mean values of the cancer's visual characteristics.
* There are also several categorical features where patients in the dataset are labeled with numerical values. You can examine them in the Chart area.

Other features contain specific ranges of average values of the features of the cancer image:

* **radius_mean, texture_mean, perimeter_mean, area_mean, smoothness_mean, compactness_mean, concavity_mean, concave points_mean**
Each of these features is mapped to a table containing the number of values in a given range. You can examine the Chart Tables

**Each sample contains the patient's unique ID, the cancer diagnosis and the average values of the cancer's visual characteristics.**

**Such a dataset can be used to train or test models and algorithms used to make cancer diagnoses. Understanding and analyzing the dataset can contribute to the improvement of cancer-related visual features and diagnosis.**

### 💖 **Acknowledgements and Information**

This database has been elaborated for educational purposes and published to reach more people, you can access the original source from the link below, please do not forget to support that data

🔗 https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

This database can also be accessed via the UW CS ftp server:

🔗 ftp.cs.wisc.edu cd math-prog/cpo-dataset/machine-learn/WDBC/

It can also be found at the UCI Machine Learning Repository:

🔗 https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29


