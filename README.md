# 🏥 Prédiction des AVC avec MongoDB et Apache Spark

## 📌 Description
Ce projet vise à analyser un ensemble de données médicales sur les **accidents vasculaires cérébraux (AVC)** en utilisant **MongoDB** pour le stockage et la gestion des données, ainsi qu’**Apache Spark** pour la distribution et l’optimisation des calculs d’apprentissage automatique.

## 🎯 Objectifs
✅ Stocker et interroger efficacement les données patient dans MongoDB 🗄️  
✅ Effectuer des analyses avancées sur les **facteurs de risque des AVC** 📊  
✅ Construire un **modèle de prédiction d’AVC** à l’aide d’un **réseau de neurones convolutifs (CNN)** 🤖  
✅ Exploiter Apache Spark pour une **exécution distribuée et performante** 🚀  

## 🗂 Dataset Utilisé
📂 **healthcare-dataset-stroke-data.csv**  
🔹 Contient **5110 enregistrements** sur des patients avec des variables médicales et démographiques.  
🔹 Pas de valeurs manquantes.  

## 🏗 Partie A : Gestion des Données avec MongoDB
1️⃣ **Création de la base de données** `Dossier_Patients` 📂  
2️⃣ **Insertion des données patients** avec une limitation de taille et de nombre de documents 📜  
3️⃣ **Création d’index** :  
   - 🔼 **Âge** (ordre croissant)  
   - 🔽 **BMI (Body Mass Index)** (ordre décroissant)  
4️⃣ **Exécution de requêtes analytiques** :  
   - Extraction des patients fumeurs 🏥  
   - Sélection des patients cardiaques en zone urbaine 🏙️  
   - Filtrage des patients selon des critères spécifiques 📑  

## 🏗 Partie B : Prédiction d’AVC avec Apache Spark + CNN
1️⃣ Importation et prétraitement des données avec **RDD Spark** ⚡  
2️⃣ Encodage des variables catégoriques et suppression des colonnes inutiles 🔍  
3️⃣ Séparation des données en **train_set** et **test_set** 📊  
4️⃣ Construction et entraînement d’un **CNN pour la prédiction des AVC** 🧠  
5️⃣ Analyse des performances du modèle via **matrice de confusion** et **précision** 🔎  

## 🔧 Technologies Utilisées
- **MongoDB** (Base de données NoSQL) 🗄️  
- **Apache Spark** (Traitement distribué) ⚡  
- **Python (TensorFlow / Keras)** (Modélisation CNN) 🧠  
- **PySpark** (Interface Spark pour Python) 🐍  

## 📊 Résultats Attendus
✅ **Optimisation du stockage des données médicales** 📁  
✅ **Accès rapide aux informations critiques des patients** ⏳  
✅ **Prédiction efficace des AVC à l’aide d’un CNN** 🎯  
✅ **Accélération des calculs grâce à Spark** 🚀  

