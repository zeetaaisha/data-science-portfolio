# Fetal Health Predictor
## Overview
The purpose of this model is to classify fetuses into 3 different health classes based on a series of 22 features from cardiotocography (CTG) scans, such as baseline fetal heart rate, number of fetal movements per second, and number of uterine contractions per second. These classes are: 1 - normal, 2 - suspect, and 3 - pathological.

The data for this project was sourced from kaggle.com; the link can be found [here](https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification). The fetal_health.csv file accompanying this notebook is nearly identical to the original kaggle dataset, with the exception of adjustments made to the headers for enhanced readability. For instance, the column name "fetal_health" was changed to "Fetal Health". The same procedure was followed for all column headers. The data was not altered.

## Utility
The Fetal Health Predictor serves a critical role in obstetrics and healthcare by providing a non-invasive means of assessing the health status of fetuses during pregnancy. The model's classification into normal, suspect, or pathological categories based on CTG scans enables healthcare professionals in these ways:

**Early Detection**: Identify potential health issues in fetuses early in the pregnancy, allowing for timely intervention and care.

**Risk Stratification**: Classify the level of risk associated with each fetus, assisting healthcare providers in prioritizing resources and attention to high-risk cases.

**Informed Decision-Making**: Empower expectant parents with valuable information about the health of their unborn child, enabling informed decision-making regarding prenatal care and potential medical interventions.

**Resource Optimization**: Optimize the allocation of medical resources by focusing on cases that require additional monitoring or intervention, thereby improving overall healthcare efficiency.

By leveraging machine learning and data-driven insights, the Fetal Health Predictor contributes to improved prenatal care and better outcomes for both mothers and infants. This project represents a valuable tool in the realm of maternal-fetal medicine, offering a reliable and efficient means of assessing fetal health.

## Model Building
The model building process involves creating, tuning, and comparing several machine learning models. The best-performing model is then fine-tuned to meet specific specifications.
