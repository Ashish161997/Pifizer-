# Pifizer-
Machine Learning for Health

Problem Statements:
1. Defining a Patient’s Health Status. For this task we require you to define a patient’s health status based on their diagnostic data. The CCS map will be useful for this. Use whatever you think appropriate to define a robust characterization of each patient’s health status. Ideally, your characterization would be useful for establishing something like “Patient 0123 has anemia and skin infection.”
2. Predicting Heath Status using Prescription Data alone. We now ask you to infer a patient’s health status using only their prescription data. You should think of building a model that would allow you to potentially predict the health status of patients outside the ones provided. It is completely up to you how you decide to accomplish this task. Please feel free to make assumptions to solve this and explain those during the interview

Data Overview:
In this case study you will be tasked to come up with a way to define a patient’s health status using diagnosis data, and then try to predict a patient’s health status using prescription data only. For this task, we are providing you with three datasets simulating data for about 85000 patients over a period of 3 years:
1. Patient Diagnosis. Each row of this dataset contains a patient’s diagnosis provided on a specific date. The diagnosis codes are presented in a standard called ICD-10.
2. Patient Prescriptions. Each row of this dataset contains a patient’s prescription filled on a specific date. The prescriptions are identified by their National Drug Code (NDC); rows also contain drug category, drug group, and drug class.
3. ICD-to-Clinical Categories Map (CCS). Each row in this file contains an ICD-10 diagnosis code (with a slightly different formatting than in the Patient Diagnosis table) and diagnosis descriptions as explained here: https://www.hcup-us.ahrq.gov/toolssoftware/ccs10/ccs10.jsp. Not all diagnosis codes have a CSS code, so you may have to work around this.
