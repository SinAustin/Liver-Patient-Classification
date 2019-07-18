# Liver-Patient-Classification

## The problem:
According to the CDC from 2000 to 2015, death rates for chronic liver disease and cirrhosis in the United States increased 31% (from 20.1 per 100,000 to 26.4) among persons aged 45–64 years. Rates in that age group increased 21% for men (from 29.8 to 36.2) and 57% for women (from 10.8 to 17.0). Among persons aged 25–44 years, the death rate for men decreased 10% (from 6.1 to 5.5), and the rate for women increased 18% (from 2.8 to 3.3). Overall, among persons aged ≥65 years, rates increased 3% (from 29.4 to 30.2). Death rates for both men and women increased with age.

## The Goal:
Our goal is to build a model to that can correctly diagnos liver disease based on 10 features, 8 of them being chemical levels in the blood.
Using the intake of harmful foods, gases, and alcohol to predict liver disease in indian patients.
Our SVM ended with a DIAGNOSIS ACCURACY OF 93% FOR FEMALES AND 94% FOR MALES.

## Context:
Patients with Liver disease have been continuously increasing because of excessive consumption of alcohol, inhale of harmful gases, intake of contaminated food, pickles and drugs. This dataset was used to evaluate prediction algorithms in an effort to reduce burden on doctors.
## The Data:
This data set contains 416 liver patient records and 167 non liver patient records collected from North East of Andhra Pradesh, India. The "Dataset" column is a class label used to divide groups into liver patient (liver disease) or not (no disease). This data set contains 441 male patient records and 142 female patient records.

Any patient whose age exceeded 89 is listed as being of age "90".

Columns:

    Age of the patient
    Gender of the patient
    Total Bilirubin
    Direct Bilirubin
    Alkaline Phosphotase
    Alamine Aminotransferase
    Aspartate Aminotransferase
    Total Protiens
    Albumin
    Albumin and Globulin Ratio
    Dataset: field used to split the data into two sets (patient with liver disease, or no disease)
# Results:
## Using the intake of harmful foods, gases, and alcohol to predict liver disease in indian patients. Our SVM ended with a DIAGNOSIS ACCURACY OF 93% FOR FEMALES AND 94% FOR MALES.

Acknowledgements

This dataset was downloaded from the UCI ML Repository:

Lichman, M. (2013). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science.
Inspiration

Use these patient records to determine which patients have liver disease and which ones do not. 
