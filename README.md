# Projet Data Mining : Analyse de Données Médicales

## Équipe INGE2D
Jade IOUALALEN, Karl JUTTIN, Améziane HAOUANOH, Léonie SCHMIT, Kenza LAAZIRI

## Objectif du Projet
Ce projet vise à analyser le jeu de données médical **Pima Indians Diabetes** afin d'extraire des connaissances exploitables et de construire des modèles prédictifs. Nous avons implémenté trois approches majeures du Data Mining :
1. **Règles d'association** (Apprentissage non supervisé)
2. **Classification supervisée** (Comparaison de 4 modèles)
3. **Clustering** (Analyse de groupes)

## Jeu de Données
Le dataset contient des données sur 768 patientes d'origine Pima, avec 8 variables cliniques (Glucose, IMC, Insuline, Age, ...) et une variable cible, 0 : non-diabétique, 1 : diabétique.

## Étapes Réalisées

### 1. Prétraitement
- Nettoyage des valeurs aberrantes avec les zéros remplacés par la médiane.
- Standardisation des données.
- Analyse avec matrices de corrélation et histogrammes.

### 2. Règles d'Association Apriori
- Discrétisation des variables par la médiane.
- Extraction de règles basées sur le **Support**, la **Confiance** et le **Lift**.
- Identification des facteurs de risque les plus corrélés au diagnostic positif.

### 3. Classification Supervisée
Comparaison de quatre algorithmes avec évaluation via Matrice de Confusion :
- **Decision Tree**
- **Random Forest**
- **K-Nearest Neighbors KNN**
- **AdaBoost**

### 4. Clustering Non Supervisé
- **K-Means** Méthode du coude et score de silhouette.
- **Clustering Hiérarchique** Dendrogramme.
- Visualisation 2D via PCA pour valider la séparation des groupes.

