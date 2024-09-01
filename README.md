# H1N1 AND SEASONAL FLU VACCINE

As the world struggles to vaccinate the global population against COVID-19, an understanding of how people’s backgrounds, opinions, and health behaviors are related to their personal vaccination patterns can provide guidance for future public health efforts. Your audience could be someone guiding those public health efforts.

![A MAN SNEEZING](/covid%20images/MAN%20SNEEZING.jpeg)


This challenge: can you predict whether people got H1N1 and seasonal flu vaccines using data collected in the National 2009 H1N1 Flu Survey? This is a binary classification problem, but there are two potential targets: whether the survey respondent received the seasonal flu vaccine, or whether the respondent received the H1N1 flu vaccine. Please choose just one of these potential targets for your minimum viable project.
This is a dataset that was sourced from *DRIVEN DATA ORG* ,with an aim of finding the effectiveness of the H1N1 and flu vaccines.<https://www.drivendata.org/competitions/66/flu-shot-learning/data/#data>


![Image of mother receiving covid vaccine](/covid%20images/covid%20vaccine1.jpeg)

## Background information on H1N1

The H1N1 flu, sometimes called swine flu, is a type of influenza A virus.

During the 2009-10 flu season, a new H1N1 virus began causing illness in humans. It was often called swine flu and was a new combination of influenza viruses that infect pigs, birds and humans.

The World Health Organization (WHO) declared the H1N1 flu to be a pandemic in 2009. That year the virus caused an estimated 284,400 deaths worldwide. In August 2010, WHO declared the pandemic over. But the H1N1 flu strain from the pandemic became one of the strains that cause seasonal flu.

Most people with the flu get better on their own.

But flu and its complications can be deadly, especially for people at high risk. The seasonal flu vaccine can now help protect against the H1N1 flu and other seasonal flu viruses.
<https://www.mayoclinic.org/diseases-conditions/swine-flu/symptoms-causes/syc-20378103>
![IMAGE OF A CHILD VACCINATED](/covid%20images/covid%20children%20vaccine.jpeg)

## H1N1 SYMPTOMS
The symptoms of flu caused by H1N1, commonly called the swine flu, are similar to those of other flu viruses.

Symptoms usually start quickly and can include:

-Fever, but not always.
-Aching muscles.
-Chills and sweats.
-Cough.
-Sore throat.
-Runny or stuffy nose.
-Watery, red eyes.
-Eye pain.
-Body aches.
-Headache.
-Tiredness and weakness.
-Diarrhea.
-Feeling sick to the stomach, vomiting, but this is more common in children than adults.
Flu symptoms develop about 1 to 4 days after you're exposed to the virus.

## THE AIM OF THIS PROJECT
Therefore this project seeks to ascertain peoples behaviour in the administration of H1N1 and other flu vaccines in the wake of covid 19.
this will help in determine the best strategy in the adminitration of the covid vaccine that has almost the same impact as the H1N1 pandemic.
### What is covid 19?

Coronavirus disease 2019 (COVID-19) is a highly contagious viral illness caused by severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2). COVID-19 has had a catastrophic effect on the world, resulting in more than 6 million deaths worldwide. After the first cases of this predominantly respiratory viral illness were reported in Wuhan, Hubei Province, China, in late December 2019, SARS-CoV-2 rapidly disseminated worldwide. This compelled the World Health Organization (WHO) to declare it a global pandemic on March 11, 2020
<https://www.ncbi.nlm.nih.gov/books/NBK554776/>

![IMAGE OF COVID VIRUS](/covid%20images/covid19.jpeg)

### What next?

After successfully cubbing the H1N1 and other flu outbreaks in the past.The public health stakeholdeers are seeking ways to mitigate the spread of the coranvirus among the public.
And based on past experinces,setbacks and successes ,this project seeks to highlight the best approch towards minimizing the impact of the corona to the public.

## Problem description
Your goal is to predict how likely individuals are to receive their H1N1 and seasonal flu vaccines. Specifically, you'll be predicting two probabilities: one for h1n1_vaccine and one for seasonal_vaccine.

Each row in the dataset represents one person who responded to the National 2009 H1N1 Flu Survey.

## Labels
For this project, there are two target variables:

<span style="color:green;">h1n1_vaccine</span> - Whether respondent received H1N1 flu vaccine.

<span style="color:green;">seasonal_vaccine</span> - Whether respondent received seasonal flu vaccine.

Both are binary variables: 0 = No; 1 = Yes. Some respondents didn't get either vaccine, others got only one, and some got both. This is formulated as a multilabel (and not multiclass) problem.

## The features in this dataset
The dataset has  36 columns. The first column respondent_id is a unique and random identifier. The remaining 35 features are described below.

1. <span style="color:red;">For all binary variables</span>: 0 = No; 1 = Yes.

2. <span style="color:red;">h1n1_concern</span>- Level of concern about the H1N1 flu.
       0 = Not at all concerned; 
       1 = Not very concerned; 
       2 = Somewhat concerned; 
       3 = Very concerned.
3. <span style="color:red;">h1n1_knowledge</span> - Level of knowledge about H1N1 flu.
       0 = No knowledge; 
       1 = A little knowledge;
        2 = A lot of knowledge.
4. <span style="color:red;">behavioral_antiviral_meds</span> - Has taken antiviral medications. (binary)
5. <span style="color:red;">behavioral_avoidance</span> - Has avoided close contact with others with flu-like symptoms. (binary)
6. <span style="color:red;">behavioral_face_mask</span> - Has bought a face mask. (binary)
7. <span style="color:red;">behavioral_wash_hands</span> - Has frequently washed hands or used hand sanitizer. (binary)
8. <span style="color:red;">behavioral_large_gatherings</span> - Has reduced time at large gatherings. (binary)
9. <span style="color:red;">behavioral_outside_home</span> - Has reduced contact with people outside of own household. (binary)
10. <span style="color:red;">behavioral_touch_face</span> - Has avoided touching eyes, nose, or mouth. (binary)
11. <span style="color:red;">doctor_recc_h1n1</span> - H1N1 flu vaccine was recommended by doctor. (binary)
12. <span style="color:red;">doctor_recc_seasonal</span> - Seasonal flu vaccine was recommended by doctor. (binary)
13. <span style="color:red;">chronic_med_condition</span> - Has any of the following chronic medical conditions: 
         asthma or an other lung condition, diabetes, a heart condition, a kidney condition, sickle cell anemia or other anemia, a neurological or neuromuscular condition, a liver condition, or a weakened immune system caused by a chronic illness or by medicines taken for a chronic illness. (binary)
14. <span style="color:red;">child_under_6_months</span> - Has regular close contact with a child under the age of six months. (binary)
15. <span style="color:red;">health_worker</span> - Is a healthcare worker. (binary)
16. <span style="color:red;">health_insurance</span> - Has health insurance. (binary)
17. <span style="color:red;">opinion_h1n1_vacc_effective</span> - Respondent's opinion about H1N1 vaccine effectiveness.
         1 = Not at all effective; 
         2 = Not very effective; 
         3 = Don't know; 
         4 = Somewhat effective; 
         5 = Very effective.
18. <span style="color:red;">opinion_h1n1_risk</span> - Respondent's opinion about risk of getting sick with H1N1 flu without vaccine.
         1 = Very Low; 
         2 = Somewhat low; 
         3 = Don't know; 
         4 = Somewhat high; 
         5 = Very high.
19. <span style="color:red;">opinion_h1n1_sick_from_vacc</span> - Respondent's worry of getting sick from taking H1N1 vaccine.
         1 = Not at all worried; 
         2 = Not very worried; 
         3 = Don't know; 
         4 = Somewhat worried; 
         5 = Very worried.
20. <span style="color:red;">opinion_seas_vacc_effective</span> - Respondent's opinion about seasonal flu vaccine effectiveness.
         1 = Not at all effective; 
         2 = Not very effective; 
         3 = Don't know; 
         4 = Somewhat effective; 
         5 = Very effective.
21. <span style="color:red;">opinion_seas_risk</span> - Respondent's opinion about risk of getting sick with seasonal flu without vaccine.
         1 = Very Low; 
         2 = Somewhat low; 
         3 = Don't know; 
         4 = Somewhat high; 
         5 = Very high.
22. <span style="color:red;">opinion_seas_sick_from_vacc</span> - Respondent's worry of getting sick from taking seasonal flu vaccine.
         1 = Not at all worried; 
         2 = Not very worried; 
         3 = Don't know; 
         4 = Somewhat worried; 
         5 = Very worried.
23. <span style="color:red;">age_group</span> - Age group of respondent.
24. <span style="color:red;">education</span> - Self-reported education level.
25. <span style="color:red;">race</span> - Race of respondent.
26. <span style="color:red;">sex</span> - Sex of respondent.
27. <span style="color:red;">income_poverty</span> - Household annual income of respondent with respect to 2008 Census poverty thresholds.
28. <span style="color:red;">marital_status</span> - Marital status of respondent.
29. <span style="color:red;">rent_or_own</span> - Housing situation of respondent.
30. <span style="color:red;">employment_status</span> - Employment status of respondent.
31. <span style="color:red;">hhs_geo_region</span> - Respondent's residence using a 10-region geographic classification defined by the U.S. Dept. of Health and Human Services. Values are represented as short random character strings.
32. <span style="color:red;">census_msa</span> - Respondent's residence within metropolitan statistical areas (MSA) as defined by the U.S. Census.
33. <span style="color:red;">household_adults</span> - Number of other adults in household, top-coded to 3.
34. <span style="color:red;">household_children</span> - Number of children in household, top-coded to 3.
35. <span style="color:red;">employment_industry</span> - Type of industry respondent is employed in. Values are represented as short random character strings.
36. <span style="color:red;">employment_occupation</span> - Type of occupation of respondent. Values are represented as short random character strings.
    
## model used
The model used is for classification:Logistic regression and Decision Tree.
```python
#import the necessary classifiers
from sklearn.neural_network import MLPClassifier
from sklearn.neighbors import KNeighborsClassifier
from sklearn.svm import SVC
from sklearn.gaussian_process import GaussianProcessClassifier
from sklearn.ensemble import GradientBoostingClassifier
from sklearn.gaussian_process.kernels import RBF
from sklearn.tree import  DecisionTreeClassifier
from sklearn.ensemble import ExtraTreesClassifier
from sklearn.ensemble import RandomForestClassifier,AdaBoostClassifier
from sklearn.naive_bayes import GaussianNB
from sklearn.discriminant_analysis import QuadraticDiscriminantAnalysis
from sklearn.linear_model import SGDClassifier
from sklearn.multioutput import MultiOutputClassifier
from sklearn.linear_model import LogisticRegression

```
Logistic regression proved to have the best accuracy for the model of choice foolowed by Decision Tree out of the many classification models.

## conclusion
Due to the varied symptoms associated with flu which might also apply to other diseases like common cold the model has a high chance of detecting false positive.This might not be a major problem in giving the vaccine compared to model that has high false negative.

