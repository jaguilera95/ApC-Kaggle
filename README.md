# ApC-Kaggle
Spam or Not Spam Dataset

By: Juan Aguilera Toro 1566837

# Pràctica Kaggle APC UAB 2021-22
### Nom: Juan Aguilera Toro
### DATASET: Spam or Not Spam Dataset
### URL: [kaggle](https://www.kaggle.com/ozlerhakan/spam-or-not-spam-dataset)
## Resum
El Dataset es compon de una gran quantitat d'e-mails on se'ns diu si aquests són o no Spam. De cada e-mail tenim l'string que el representa el cual ens permet veure les paraules que estan escrites al e-mail, i el que hem d'usar per tal de predir si serà o no Spam.
### Objectius del dataset
Volem poder predir si un nou correu es Spam o no ho és.
## Experiments
Durant aquesta pràctica hem realitzat diferents experiments.
### Preprocessat
Al ser un Dataset de text he hagut de tractar els missatges amb llibreries i funcions enfocades al tractament de la llengua. He utilitzat funcions de Natural Language ToolKit per tal de eliminar stopwords igual que per transformat totes les pareules plurals i diferents families de paraules a la seva original.
### Model
| Model | Hiperparametres | Mètrica | Temps |
| -- | -- | -- | -- |
| SVC | cv = 5 | 93.87% | 14'57'' |
| Random Forest Classifies | n_estimators = 100, cv = 5 | 97.64% | 1'32'' |
| Decision Tree Classifier | cv = 5 | 94.62% | 1'26'' |
| KNN | cv = 5 | 87.28% | 18'' |
## Demo
No he generat cap tipus de demo
## Conclusions
El millor model que s'ha aconseguit ha estat Random Forest Classifier.
## Idees per treballar en un futur
Crec que seria interesant indagar més en tractar totes les llengues que hi apareixen en els e-mails.