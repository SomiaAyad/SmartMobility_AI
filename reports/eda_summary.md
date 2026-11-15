# Rapport d'exploration des données (EDA)

## 1. Objectif

L'objectif de cette étape est d'explorer le dataset *Seoul Bike Sharing Demand* afin de mieux comprendre les variations du nombre de vélos loués par heure.

L'exploration permet d'étudier la demande à travers différentes variables temporelles et météorologiques.

## 2. Visualisation des données

Six graphiques ont été réalisés pour analyser :

 La distribution du nombre de vélos loués.
 L'évolution chronologique de la demande.
 Le profil horaire de la demande.
 La demande selon les saisons.
 La demande pendant les jours fériés et les jours non fériés.
 La relation entre la demande et les précipitations.

Les observations et les limites de chaque graphique sont présentées dans le notebook `03_eda.ipynb`.

## 3. Fonctionnement du service

Une comparaison a été réalisée entre les heures où le service fonctionne et celles où il ne fonctionne pas.

Les résultats montrent que les heures de fermeture présentent généralement zéro location. Ces valeurs correspondent à l'indisponibilité du service et ne doivent pas être interprétées comme une faible demande.

## 4. Exercices individuels

### 4.1 Moyenne des locations par heure

La fonction `groupby()` a été utilisée pour regrouper les données selon l'heure, puis `mean()` a permis de calculer le nombre moyen de vélos loués pour chaque heure.

### 4.2 Comparaison des distributions

Une comparaison des distributions a été réalisée pour étudier les différences du nombre de vélos loués entre les jours de semaine et les jours fériés.

## 5. Conclusion

Cette étape d'exploration a permis de mieux comprendre les variations de la demande de vélos et d'identifier plusieurs variables susceptibles d'influencer les locations.
Les résultats obtenus serviront de base pour la prochaine étape : la préparation des données et la construction des modèles de Machine Learning.
