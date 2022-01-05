# Measure-of-Diabetes-progression
A quantitative measure of disease progression one year after baseline
---
<br>Diabetes dataset
----------------
<br>
Ten baseline variables, age, sex, body mass index, average blood
pressure, and six blood serum measurements were obtained for each of n =
442 diabetes patients, as well as the response of interest, a
quantitative measure of disease progression one year after baseline.<br>
**Data Set Characteristics:**
<br>
  :Number of Instances: 442<br>

  :Number of Attributes: First 10 columns are numeric predictive values

  :Target: Column 11 is a quantitative measure of disease progression one year after baseline

  :Attribute Information:
      - age     age in years
      - sex
      - bmi     body mass index
      - bp      average blood pressure
      - s1      tc, total serum cholesterol
      - s2      ldl, low-density lipoproteins
      - s3      hdl, high-density lipoproteins
      - s4      tch, total cholesterol / HDL
      - s5      ltg, possibly log of serum triglycerides level
      - s6      glu, blood sugar level

Note: Each of these 10 feature variables have been mean centered and scaled by the standard deviation times `n_samples` (i.e. the sum of squares of each column totals 1).

---
---
<br><br>
#Model Summary<br><br>
![image](https://user-images.githubusercontent.com/37467941/148165218-fbf1cd88-400d-42c2-b4a2-a7db834099c7.png)

#Unregularization/Regularization comparision<br><br>
![image](https://user-images.githubusercontent.com/37467941/148165283-c1c07743-9fdf-4429-bdf7-f1de46ce37b1.png)

#Result<br><br>
![image](https://user-images.githubusercontent.com/37467941/148165330-b33487b7-cc8b-4d1a-9293-eb772f40993a.png)

---
