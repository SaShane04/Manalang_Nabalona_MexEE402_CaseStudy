<div align="center">

# 📊 MexEE 402: Data Preprocessing Case Study

### Manalang_Nabalona_MexEE402_CaseStudy

**MexEE Elective 2: Data Science and Machine Learning**
Batangas State University, Alangilan Campus
1st Semester, AY 2026–2027

</div>

---

## 👥 Members

| Name | Student Number | Section |
|:---|:---:|:---:|
| Manalang, Matt Amiel | 23-05791 | MEXE 4102 |
| Nabalona, Trixie Ashennette | 23-04508 | MEXE 4102 |

---

## 📓 Notebooks

| Chapter | Topic | Notebook |
|:---:|:---|:---:|
| Ch 1–3 | Loading & Cleaning Data | [Open in Colab](https://colab.research.google.com/drive/156cKcg1zs73pm2q0m1B6YX-iOb8az1Th?usp=sharing) |
| Ch 4 | Feature Engineering | [Open in Colab](https://colab.research.google.com/drive/1drT1DWkIVGKOdsHMC-BJV-fTDx2ySQBC?usp=sharing) |
| Ch 5 | Scaling & Normalization | [Open in Colab](https://colab.research.google.com/drive/17p8myB6PnyGvRpSy-nuh68l4k7PHGpMi?usp=drive_link) |
| Ch 6 | Dealing with Outliers | [Open in Colab](https://colab.research.google.com/drive/1CM0fKc1SucWkFmI4mPS4Gv2fxBEJsgMU?usp=drive_link) |
| Ch 7 | Feature Selection | [Open in Colab](https://colab.research.google.com/drive/1hJxQ9zkOu0MmVG6OMwCrjG60zVPJAH-P?usp=drive_link) |
| Ch 8 | Preprocessing Pipeline (Titanic) | [Open in Colab](https://colab.research.google.com/drive/1eg7rGtqDXdYt29Dagaj-Hq6PHoVVVEty?usp=drive_link) |
| Ch 9 | Ch 9 | [Open in Colab](https://colab.research.google.com/drive/1jyNhfPufiExcVCfGzLWh5fyAyLs0oT4t?usp=drive_link) |

## What we learned

One short paragraph per chapter, Ch1_2_3 to Ch9. Say what the chapter taught
you and what surprised you. Not what the library does, but what you understood.

### Chapter 1_2_3
-  Chapter 1 taught us that data preprocessing is basically the preparation of raw data before using it for analysis or machine learning. We understood that data is not always clean or complete because it can have missing, inconsistent, or unnecessary information. What stood out to us was that preprocessing is not just about cleaning errors, but it can also affect how well the machine learning model performs. It made me realize that even if the model itself is good, poor-quality data can still lead to poor results.
- In chapter 2, we understood that before actually analyzing data, we first need to understand what kind of data we were working with. The dataset used was about video game sales, and we learned how to examine its columns, data types, and basic statistics. One thing we found interesting was how much information can already be learned just by looking at the structure and summary of a dataset. Before doing any complicated analysis, simply checking the data can already reveal things like missing values, numerical ranges, and the general condition of the dataset.
- For chapter 3, cleaning data is important because messy or unnecessary data can affect the reliability of the analysis. We learned that missing values can be handled by filling them with appropriate values or by removing the affected data, depending on the situation. We also learned that unnecessary features, duplicate entries, and extreme values may need to be removed. What we found notable was that not every unusual value should automatically be considered an error, so cleaning data still requires judgment on whether the information is actually useful or not.

### Chapter 4
- Chapter 4 circulates with feature engineering as not only about cleaning data but also about creating new information from the data that we already have. We learned that combining or transforming existing variables can make patterns easier to see and can give a machine learning model more useful information. What surprised me was that a simple calculation, like dividing lemonade sales by temperature, can already become a new feature that gives a different perspective on the data. I also learned that categorical data needs to be encoded differently depending on whether the categories have an order or not.
  
### Chapter 5
- In this chapter, we came to understand that data scaling is used to make features with different numerical ranges more comparable to each other. In the example, study hours had much smaller values than grades, so without scaling, the grades could have more influence simply because their numbers were bigger. One realization we had was that the actual size of a number can affect how a machine learning model treats a feature, even if the feature itself is important. I also learned that scaling is not automatically required for every machine learning problem because it depends on the data and the algorithm being used.

### Chapter 6
- This chapter taught me that extreme data points can severely distort models just like electrical noise corrupts a sensor signal, and it showed me how statistical tools like Z-scores and the Interquartile Range (IQR) provide reliable mathematical boundaries to detect them. What surprised me was how straightforward yet powerful these numerical thresholds; such as looking beyond three standard deviations or 1.5 times the IQR, are for isolating disruptive anomalies without manual guesswork.
  
### Chapter 7
- This chapter taught me how crucial it is to address gaps in datasets through proper imputation methods and to normalize feature ranges so that models can learn effectively without bias toward larger numerical values. What surprised me was how significantly unscaled features can distort the optimization path of algorithms like gradient descent, making data preparation just as critical as the choice of the model itself.
  
### Chapter 8
- This chapter taught me how to turn text categories into numbers that algorithms can understand, and how to simplify datasets with too many columns by shrinking them down to the essentials. What surprised me was how easily a massive amount of data can be reduced into just a few key variables without losing the important patterns.

### Chapter 9
- This chapter taught me how to handle a messy, multi-type dataset like the Titanic passenger records by systematically chaining cleaning, transformation, reduction, and encoding steps into a cohesive pipeline. What surprised me was the sheer depth of structured housekeeping required before any machine learning model can even touch the data, highlighting that preprocessing is rigorous and iterative.

## Errors we found

After reviewing the project with three AI tools: Claude, Gemini, and ChatGPT, no significant errors were found in the original VS Code files. All of the files in the Google Colab notebooks were also executed successfully without any errors. The functions and syntax used in the code worked as intended and produced the expected results.

## Note on AI tools

We indeed used AI in making this "**Data Preprocessing Case Study**". We used Gemini and Claude for cross-checking our code from the vs codes to the colabs and making our READ_me better looking. Chatgpt was then used to enhanced our answers to the questions asked. 

## References

McKinney, W. (2021). Python for Data Analysis, 3rd ed. O'Reilly.
VanderPlas, J. Python Data Science Handbook.
Any other page or article you used.
