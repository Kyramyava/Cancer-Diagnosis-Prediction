# Cancer-Diagnosis-Prediction
This project uses publically available data from the Health Information National Trends Survey to create random forests and feedforward neural networks to predict cancer diagnosis in survey participants. "EverHadCancer", which looks at the cancer diagnosis of the participant was used as a target. "FamilyEverHadCancer2", which looks at cancer diagnosis in family members of the participants, to see if there was any correlation between familial cancer diagnosis and the determinants of health that I looked at. A final version of the models was made using "EverHadCancer" as a target and "FamilyEverHadCancer2" as a feature to see how the inclusion of a familial cancer diagnosis affected feature importance and the ability to predict cancer diagnoses in participants. Attached are figures that depict the feature importances for the random forests (RF) and feedforward neural networks (FFN) of the three versions. 
"EverHadCancer":
![image](https://github.com/user-attachments/assets/9e81abf9-62ab-41f5-90ae-8dd33ce5c308)
![image](https://github.com/user-attachments/assets/e3a18fa1-3477-44c1-ab57-09e933b2b11c)
"FamilyEverHadCancer2"
![image](https://github.com/user-attachments/assets/21ef2992-8850-47fc-9db8-1b24097a50eb)
![image](https://github.com/user-attachments/assets/8d45f06b-b98f-4e47-8001-41b1a97cd962)
"EverHadCancer" 2 (the version with "FamilyEverHadCancer2" as a feature):
![image](https://github.com/user-attachments/assets/50efeb45-9b65-44a7-9af3-123e4f76ec89)
![image](https://github.com/user-attachments/assets/12ce2534-c715-4e50-a6fb-56d2f205bcf3)
