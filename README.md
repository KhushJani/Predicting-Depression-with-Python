# Predicting-Depression-with-Python
Depression is a mental health disorder characterized by a persistent feeling of sadness or loss of interest in activities you once enjoyed, usually with no known cause. According to the WHO, approximately 280 million people in the world are living with this illness, and over 700,000 people die yearly from suicide linked to depression. If you ask me, these are huge numbers and should be of Public Health concern.
 
One of the causes of depression is chronic stress, and it is no wonder this disorder is prevalent among University students, but:

1. What proportion of students are depressed?
2. What are the factors that most likely indicate a student is depressed?
3. Are students of a particular gender more prone to this illness?
4. Can we predict if a student is depressed if we have some data?

# SOLUTION
Variables Used for this Analysis:
1. **phq_score:** A score evaluated from an assessment known as the Patient Health Questionairre (PHQ) to determine the severity of mental health problems such as depression. You can learn more about it [here](https://neurospatms.com/everything-you-need-to-know-about-the-phq-9-test/).
    - 0 - 4: None-minimal or Normal
    - 5 - 9: Mild
    - 10 - 14: Moderate
    - 15 - 19: Moderately-severe
    - 20 - 24: Severe
2. **depression_severity:** Estimated from the **phq_score**.
3. **depressiveness:** Whether the participant has clinical depression or not.
4. **depression_diagnosis:** Diagnosis by a mental health specialist as clinically depressed or not.
5. **depression_treatment:** Undergoing treatment or not.
6. **suicidal:** Likelihood of committing suicide with True being most likely.
7. **gad_score:** A score evaluated from an assessment known as Generalized Anxiety Disorder-7 (GAD-7) questionairre to determine the severity of one's anxiety. You can learn more about it [here](https://www.corc.uk.net/outcome-experience-measures/generalised-anxiety-disorder-assessment-gad-7/).
    - 0 - 4: None-minimal or Normal
    - 5 - 9: Mild
    - 10 - 14: Moderate
    - 15 - 21: Severe
8. **anxiety_severity:** Estimated from the **gad_score**.
9. **anxiety_diagnosis:** Diagnosis by a mental health specialist as having Generalized Anxiety Disorder or not.
10. **anxiety_treatment:** Undergoing anxiety treatment or not.
11. **epworth_score:** A test score used to measure daytime sleepiness. You can learn more about it, or even take yours [here](https://healthysleep.med.harvard.edu/narcolepsy/diagnosing-narcolepsy/epworth-sleepiness-scale).
    - 0 - 10: Normal range in healthy adults
    - 11 - 14: Mild sleepiness
    - 15 - 17: Moderate sleepiness
    - 18 - 24: Severe sleepiness
12. **sleepiness:** Likelihood of daytime sleepiness with True being most likely estimated from the **epworth_score**.
13. **bmi:** Body Mass Index of participant measured in kg/m²
14. **who_bmi:** The various categories of nutritional health by Body Mass Index(BMI) according to the WHO. To learn more about it, click [here](https://www.who.int/europe/news-room/fact-sheets/item/a-healthy-lifestyle---who-recommendations).
    - Below 18.5: Underweight
    - 18.5 - 24.9: Normal weight
    - 25.0 - 29.9: Pre-obesity/Overweight
    - 30.0 - 34.9: Class I Obesity
    - 35.0 - 39.9: Class II Obesity
    - Above 40: Class III Obesity
15. **age:** Age of participant ranging from 18 - 31.
16. **gender:** Sex of participant i.e either Male or Female.
17. **school_year:** Current school year ranging from 1 - 4.

# HYPOTHESES
1. The average BMI of a male student is higher than a female student
2. About 64% and 26% of University students are normal and overweight respectively
3. Male students are two times more likely to be overweight than female students
4. Male students are about two times more likely to be severely depressed
5. Female students are two times more likely to experience severe anxiety than males
6. Female students are more likely to be depressed than male students
7. 25% of depressed students receiving treatment are suicidal
8. Students who are depressed have a higher BMI than those who are not
9. Obese Students are 2.5 times more likely to be depressed than normal students
10. Approximately 90% of depressed students are not receiving treatment
11. Approximately 2 out of 5 students have mild depression
