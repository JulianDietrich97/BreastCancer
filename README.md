# BreastCancer (In progress)
## Introduction
Breast carcinoma is a prevalent cancer affecting women globally. The process of normal cells transitioning into cancer cells involves multiple stages. The morphological characteristics of the nucleus serve as a distinct indicator for cancer diagnosis. Throughout the progression of the disease, there is a gradual alteration in nuclear parameters from benign to malignant. Breast cancer has been associated with variations in nuclear size, shape, chromatin pattern, as well as the size and number of nucleoli [1]. These morphometric features of the nucleus have demonstrated the ability to predict the prognosis of breast cancer patients [2].

Objective evaluation of nuclear changes occurring during these transformative steps is crucial. As a result, nuclear morphometry can serve as a valuable diagnostic tool.

In recent years, data science techniques have emerged as powerful tools to extract valuable insights from large-scale datasets, aiding in early detection, diagnosis, and treatment decisions. In this project, we embark on a comprehensive analysis of a breast cancer dataset, employing various data science techniques to gain a deeper understanding of the factors influencing this disease.

In this dataset, features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass and characteristics of the cell nuclei present in the image are described.


Figure 1: Fine needle aspirate procedure.
![Fine needle aspiration](https://github.com/JulianDietrich97/BreastCancer/assets/117474938/bc745ea9-6d5c-41bc-b2e7-2edb2436fa6a)


Figure 2: Fine needle aspiration from left breast mass which was showing tumor cells with atypical nuclei and abundant cytoplasm with vacuolation and granularity (Diff-Quik stain, ×400) (Mahrous et al., 2012).
![Fine-needle-aspiration-from-left-breast-mass-which-was-showing-tumor-cells-with-atypical_W640](https://github.com/JulianDietrich97/BreastCancer/assets/117474938/32ffa05c-d2f4-4c17-8515-5bbd7b21fd51)



## Project:
### Question:
How effectively can data science methodologies be employed to classify breast cancer cases based on morphometric features of cell nuclei, and how does the performance of different classification algorithms compare in accurately distinguishing between benign and malignant cases?

## Steps:
### 1- Exploratory Analysis
My initial step involves exploratory analysis, where I delve into the dataset to uncover hidden patterns, relationships, and trends among various variables. By visualizing and summarizing the data, I intend to identify crucial features and gain preliminary insights into the underlying structure of the dataset. This exploration will serve as the foundation for formulating relevant research questions and setting the course for subsequent analyses.

### 2- K-Means
Moving forward, I will apply clustering analysis techniques to group similar instances within the breast cancer dataset based on their intrinsic characteristics. By employing clustering algorithms, I hope to identify distinct subgroups of patients with similar clinical profiles. This analysis has the potential to reveal valuable insights and shed light on specific patient populations that may require tailored treatment strategies or further investigation.

### 3- Predictive modeling
Lastly, I will employ predictive modeling techniques to develop accurate models capable of predicting the likelihood of malignancy based on various nuclear morphometric attributes of the cells. Utilizing machine learning algorithms and leveraging insights gained from earlier stages, my goal is to construct robust predictive models. These models can potentially aid in early detection, risk assessment, and personalized treatment recommendations.


## Bibliography
Pienta KJ, Coffey DS. Correlation of nuclear morphometry with progression of breast cancer. Cancer. 1991;68:2012–6. [PubMed] [Google Scholar]
Cui Y, Koop EA, van Diest PJ, Kandel RA, Rohan TE. Nuclear morphometric features in benign breast tissue and risk of subsequent breast cancer. Breast Cancer Res Treat. 2007;104:103–7. [PMC free article] [PubMed] [Google Scholar]

Mahrous, Mervat & Morsy, Walid & Al-Hujaily, Ahmed & Al-Sulimani, Sameerah. (2012). Breast Metastasis from Renal Cell Carcinoma: Rare Initial Presentation of Disease Recurrence after 5 Years. Journal of breast cancer. 15. 244-7. 10.4048/jbc.2012.15.2.244. 
