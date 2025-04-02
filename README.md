
#  mltoolkit

  

##  💫 About Developer:

  

###  Banish J

  

🤖 AI & ML Developer | Data Science & Analytics Expert

🌐 Web Apps & IoT Skilled | Awesome UI Creator

💻 AI is my main focus! 👾

  

##  📞 Contact

#####  **☎️**  [9444333914](tel:9444333914)

#####  **📧**  [mail@banish.in](mailto:mail@banish.in)

#####  **🌐**  [Banish](https://www.banish.in)

  

##  Core Concept

*This python package is mde to simplify your ml tasks and make you to run large program at few lines of code it simplifies your program and imprpve your productivity.*

## About this Package

*A Python package that automates ML workflows, trains multiple models with one line of code, and identifies the best performer for faster deployment.*

### Key Features:

✅ Single-Line Model Training –** Train multiple ML models simultaneously with minimal code.

✅ Automated Accuracy Comparison – Generates performance tables and highlights the best model.

✅ Boosts Productivity – Reduces repetitive tasks, speeding up research and deployment.

### Use Cases:

🔹 Quick Prototyping – Ideal for testing multiple algorithms in research or hackathons.

🔹 Automated Benchmarking – Compare models effortlessly for optimal performance.

🔹 Beginner-Friendly ML – Simplifies model training for students and new developers.

**Why It Stands Out:**

🚀 Saves Time – No manual coding for each model; instant results.

📊 Smart Decision-Making – Auto-selects the best model based on accuracy.



##  Algorithm accuracy table

```python

from mltoolkit import Regression as regressor

  

acc_table, best_param = regressor.svm(independent, dependent)

acc_table

```

###  output

---

  

| | C | linear | rbf | poly | sigmoid |
| -- | -- | -- | -- | -- | -- |
|1|C 10|0.022506|-0.08521|-0.082239|-0.099652|
| 2 |C 100|0.563729|-0.113243|-0.084659|-0.132517|
|3|C 500|0.64177|-0.10929|-0.064037|-0.582106|
|4|C 1000|0.669795|-0.102105|-0.032889|-2.022042|
|5|C 2000 | 0.767813 |-0.090715 |0.02603|-6.818809
|6|C 3000|0.764471|-0.079182|0.083426|-14.702022|
|7|C 7000|0.734434|-0.028374|0.291094|-73.122034|

  
  

###  how to use

  

```python

from mltoolkit import Regression as regressor

  

acc_table, best_param = regressor._algname_(independent, dependent)

acc_table

```

-  replace `_algname_` with `svm, decision_tree, random_forest, knn` for Regression

  

-  replace `_algname_` with `decision_tree, random_forest, knn` for Classification

  

-  replace `Regression` with `classifier` if its a classification problem statement

  

##  Model accuracy table

  

```python

from mltoolkit import Regression as regressor

  

reg_report = regressor.fit_model(independent, dependent)

reg_report

```

###  output

---

  

| | Metrics | Random Forest | Linear Regression | Poisson Regression | Decision Tree | Support Vector Machine | KNN |
| -- | -- | -- | -- | -- | -- | -- | -- |
1 | MSE | 20770567.875901 | 32304679.499094 | 30757741.967819 | 45999841.979685 | 172821773.971895 | 112965815.146866 |
2 | MAE 4557.473848 | 5683.720568 | 5545.966279 | 6782.318334 | 13146.169555 | 10628.537771 |
3 | R2 2714.117549 | 3985.71256 | 3748.157793 | 3099.796517 | 8532.534486 | 7417.95403 |
4 | RMSE 0.868069 | 0.794807 | 0.804632 | 0.707817 | -0.097732 | 0.282462 |
5 | R2ADJ | 0.867407 | 0.793777 | 0.803653 | 0.706352 | -0.103238 | 0.278863

  
  

###  how to use

  

```python

from mltoolkit import Regression as regressor

  

reg_report = regressor.fit_model(independent, dependent)

reg_report

```

  

-  replace `Regression` with `classifier` if its a classification problem statement

-  replace `fit_model` with `fit_save` to save the best model
