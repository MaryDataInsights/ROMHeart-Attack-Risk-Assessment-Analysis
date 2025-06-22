Introduction 
Heart disease remains a leading cause of mortality globally, and leveraging data for timely detection is more critical than ever.This project explores the use of data  in identifying and understanding key factors associated with heart attacks. By examining a clinical dataset with Power BI, the objective is to uncover meaningful patterns that can aid in early diagnosis and effective prevention strategies.
This report presents a comprehensive analytical approach that combines demographic, physiological, and biochemical indicators—such as age, gender, blood pressure, blood sugar, CK-MB, and troponin levels—to evaluate patients' cardiac risk profiles. The outcome is an interactive dashboard that enables healthcare professionals and decision-makers to derive actionable insights, improve screening processes, and prioritize patient care based on data-driven evidence.
![Heart Attack Dashboard](https://github.com/user-attachments/assets/3841b1d0-1362-4401-84a1-90de29757db6)
Observations
🔸 Adult Age Group:
Heart Attack Prevalence: Out of 646 adults, 56% tested positive — a moderate but significant risk.


Blood Pressure: 68.62% have normal BP, suggesting that elevated BP is not the sole driver of cardiac risk in this group.


Diastolic Pressure: Nearly balanced between positive and negative cases, showing limited differentiation power for diagnosis in adults.


Troponin: Substantially higher in positive cases, reinforcing its value as an early diagnostic biomarker.


Blood Sugar: All blood sugar values originate from this age group under the current filter, pointing to adult-onset metabolic risks (possibly prediabetes or type 2 diabetes) that could be influencing cardiac health.


🔸 Old Age Group:
Data Volume: 620 patients, with unusually high (810) positive results possibly indicating multiple entries or test records per patient.


Blood Pressure: 70% have high BP — hypertension is clearly more common and impactful in this age bracket.


Cardiac Indicators: Elevated troponin levels and BP readings strongly align with positive cases, confirming heart attack risk.


Gender Distribution: Males dominate this age group’s dataset, potentially influencing the outcome patterns.


Blood Sugar: High cumulative values further link metabolic syndrome with cardiac vulnerability in older adults.
Female Patients:
Heart Attack Rate: 56% tested positive — notable but slightly lower than males.


Blood Pressure (BP): 70% of females have normal BP, suggesting BP alone isn’t a strong predictor.


Diastolic BP: Higher cumulative diastolic pressure in positive cases (55%) indicates a moderate link.


Troponin Levels: Elevated troponin in positives (110 vs. 70 units) underscores its diagnostic value.


Blood Sugar by Age: Adult females show the highest blood sugar levels, highlighting metabolic risk in this group.


Male Patients:
Heart Attack Rate: 63% tested positive — a higher prevalence compared to females.


Blood Pressure (BP): 68.63% have normal BP — again pointing to multifactorial causes beyond BP.


Diastolic BP: A significant 64.7% of diastolic total is from positive cases, indicating stronger correlation than in females.


Troponin Levels: Very high troponin levels in positives — even more pronounced than in females.


Blood Sugar by Age: Adult and older males show significantly elevated blood sugar, reinforcing age-related metabolic risk.

Recommendations
Enhance Screening for Adults & Older Age Groups:
 Prioritize regular heart health screenings for adult and elderly males and females, especially targeting blood sugar and diastolic BP.


Use Troponin as a Primary Diagnostic Marker:
 Both male and female data confirm troponin as a strong indicator — this should be central in clinical diagnostics for suspected heart attacks.


BP Should Be Evaluated with Other Metrics:
 Since many patients with normal BP still experienced heart attacks, clinicians should combine BP analysis with other variables (troponin, blood sugar, lifestyle factors).


Implement Gender-Specific Risk Programs:


For females, focus on diastolic pressure and metabolic risk in adult age groups.


For males, monitor both diastolic pressure and blood sugar more aggressively, particularly in adults and seniors.


Preventive Health Education:
 Educate patients — especially middle-aged adults — on lifestyle changes (diet, exercise, stress management) that mitigate blood sugar and cardiac risks.


Data-Driven Personalized Care:
 Encourage healthcare providers to adopt data-driven profiling of patients, using variables like age, gender, troponin, and BP to inform early interventions.

Conclusion 
This project successfully leveraged Power BI to transform raw clinical data into actionable insights regarding heart attack risks across a population of 1,319 patients. Through thoughtful preprocessing, segmentation, and visualization, the analysis revealed several key trends: a high overall prevalence of heart attack cases, elevated risk among adult males and females with high blood sugar levels, and strong correlations between positive outcomes and biomarkers such as troponin and diastolic blood pressure.
