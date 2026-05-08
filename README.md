📌 Superstore Sales Analysis – Power BI Dashboard

<img width="605" height="341" alt="image" src="https://github.com/user-attachments/assets/2dbcb7f8-5d38-4dbd-95b1-c39e1d248517" /> <br>
<img width="608" height="340" alt="image" src="https://github.com/user-attachments/assets/3b07a090-07e3-4a4b-88a9-72aa5cad6e5b" /> <br>
<img width="607" height="341" alt="image" src="https://github.com/user-attachments/assets/3c2eb185-b044-4a5a-95da-69cb09de5f81" />

---

##  Contexte

Dashboard analysant les ventes, la performance commerciale et la logistique du dataset **Superstore Sales** (Kaggle).

## Compétences démontrées

- **Power Query** : nettoyage des données (types)
- **Mesures DAX** :
      +Total Sales = SUM(Sales)
      +Total Profit = SUM(Profit)
      +Margin % = DIVIDE(SUM('Sample - Superstore'[Profit]), SUM('Sample - Superstore'[Sales]), 0)
      +AVG Ship Period (days) = AVERAGEX('Sample - Superstore',DATEDIFF('Sample - Superstore'[Order Date], 'Sample - Superstore'[Ship Date], DAY))
      +Objectif Sales = SUM('Sample - Superstore'[Sales])*1.10
- **Visualisations** : cartes KPI, histogrammes, courbe temporelle, tableau
- **Interactivité** : segment avec "Sélectionner tout", KPI avec objectif

  ## Soure du dataset (kaggle): https://www.kaggle.com/datasets/vivek468/superstore-dataset-final/data

