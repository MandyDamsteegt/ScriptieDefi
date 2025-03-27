# Credit Card Fraud Detection met Machine Learning

Dit project richt zich op het ontwikkelen en evalueren van machine learning-modellen voor het detecteren van online betaalfraude. Door gebruik te maken van zowel een bestaande (primaire) dataset als een synthetisch gegenereerde dataset, is onderzocht hoe goed verschillende modellen in staat zijn om frauduleuze transacties te herkennen, met extra aandacht voor generaliseerbaarheid en class-imbalance.

## Inhoud van deze repository

Deze repository bevat:

- FD_MD.ipynb: Het hoofdnotebook waarin de gehele analyse is uitgevoerd, inclusief datavoorbewerking, visualisatie, modeltraining en evaluatie.
- test_new_dataset_md2.ipynb: Het notebook waarin het gemaakte model getest wordt op de secundaire data.
- Synthetic_Fraud_Dataset_md2.csv.zip: Een synthetisch gegenereerde dataset (secundair) die is gebruikt om het model te testen op generaliseerbaarheid.
- Link naar de primaire dataset onlinefraud.csv die gebruikt is voor het trainen van de data. Deze staat onderaan in deze README.

## Modellen en technieken

In dit project zijn onder andere de volgende modellen toegepast:

- Logistic Regression
- Random Forest
- XGBoost (met hyperparameter-tuning en ondersteuning voor class weighting)
  
Daarnaast is gebruikgemaakt van technieken zoals:

- Feature engineering gericht op saldo-afwijkingen en transactiegedrag
- Class-imbalance aanpak met scale_pos_weight
- Evaluatie op synthetische én reële data


## Primaire dataset

De primaire dataset (onlinefraud_dataset.csv) is afkomstig van een gesimuleerde mobiele betalingsomgeving en bevat meer dan 6 miljoen transacties. De dataset is te groot om direct in deze repository te hosten.  
Je kunt de dataset downloaden via: [Kaggle: Online Fraud Detection](https://www.kaggle.com/datasets/jainilcoder/online-payment-fraud-detection).
