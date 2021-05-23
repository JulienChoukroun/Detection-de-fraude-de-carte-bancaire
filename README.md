Ce projet est réalisé dans le cadre de la formation de cycle d'ingénieur (deuxième année) de l'Ecole Polytechnique de l'Université Côte d'Azur.
***
# Detection-de-fraude-de-carte-bancaire

## Présentation
Ce projet a été réalisé avec le langage R.
Le code se trouve aussi sur Kaggle : https://www.kaggle.com/julienchoukroun99/d-tection-de-fraude-de-carte-bancaire

### Objectifs :
* Décrire, traiter et analyser statistiquement les données d'un dataset choisi sur Kaggle : Credit Card Fraud Detection.
* Réaliser une analyse avancée en utilisant des méthodes de machine learning (logistic regression).

Exemple de résultat sur l'analyse des données :

![alt text](https://github.com/JulienChoukroun/Detection-de-fraude-de-carte-bancaire/blob/main/Images/heure.png "Densité des transactions au cours d'une journée")

![alt text](https://github.com/JulienChoukroun/Detection-de-fraude-de-carte-bancaire/blob/main/Images/transaction.png "Distribution des montants des transactions par classe")

Réalisation d'une logistic regression (ici nous sommes en présence d'un dataset **déséquilibré**) :

![alt text](https://github.com/JulienChoukroun/Detection-de-fraude-de-carte-bancaire/blob/main/Images/regression_logistic.png "Logistic Regression")

Résultat lorsque l'on prend l'intégralité du dataset :

![alt text](https://github.com/JulienChoukroun/Detection-de-fraude-de-carte-bancaire/blob/main/Images/100-sans%20Reduction.png "Intégralité du dataset")

Résultat lorsque l'on prend autant de données frauduleuses que de non frauduleuses :

![alt text](https://github.com/JulienChoukroun/Detection-de-fraude-de-carte-bancaire/blob/main/Images/50_50-superieure_0_1.png "Autant de frauduleuses que de non frauduleuses")

Résultat lorsque l'on réalise de la Weighted Logistic Regression :

![alt text](https://github.com/JulienChoukroun/Detection-de-fraude-de-carte-bancaire/blob/main/Images/Weighted_regression.png "Weighted Logistic Regression")
