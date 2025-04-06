
# Prédiction du départ client (Churn) – Projet Télécom

## 🎯 Objectif du projet
L’objectif de ce projet est d’anticiper les départs de clients dans le secteur des télécommunications, 
à l’aide d’un modèle de machine learning entraîné sur des données client réelles.  
Ce type de modèle permet aux équipes marketing de déclencher des actions ciblées avant qu’il ne soit trop tard.

---

## 🧠 Problématique
Perdre un client coûte souvent plus cher que d’en acquérir un nouveau.  
En identifiant les profils les plus à risque de départ, on peut mettre en place des actions personnalisées 
pour améliorer la fidélité client.

---

## 📦 Jeu de données
Le dataset utilisé provient d’un opérateur télécom fictif.  
Il contient des informations sur le profil client, les services souscrits, le contrat, le montant de la facture, etc.

- Nombre d’observations : environ 7 000 clients
- Variable cible : `Churn` (Oui / Non)

---

## ⚙️ Étapes du projet
1. **Exploration des données (EDA)**  
   - Analyse des distributions, corrélations, signaux de churn

2. **Préparation des données**  
   - Nettoyage, encodage, gestion des variables catégorielles

3. **Construction du modèle prédictif**  
   - Algorithme utilisé : classification supervisée (ex : forêt aléatoire, régression logistique)
   - Séparation des données : train/test
   - Évaluation : AUC, matrice de confusion, importance des variables

4. **Interprétation métier**  
   - Quels facteurs influencent le plus le départ client ?
   - Comment peut-on agir sur ces signaux ?

---

## 📈 Résultats obtenus
- Précision de détection : environ 82 %
- AUC : 0.84
- Variables clés :
  - Ancienneté du client
  - Type de contrat (mensuel vs engagement)
  - Services activés (support, sécurité)
  - Montant mensuel de la facture

---

## 📊 Visualisations

- Courbe ROC  
- Graphique d’importance des variables  
- Analyse comparative churn vs non-churn

> 📁 Ces graphiques sont disponibles dans le notebook et le dossier `images/`.

---

## 🧩 Technologies utilisées
- Python (pandas, matplotlib, seaborn, scikit-learn)
- Jupyter Notebook

---

## ✅ Conclusion
Ce projet montre comment la data peut aider à détecter les signaux faibles avant un départ client.  
Il s’agit d’un **projet pédagogique**, mais qui reproduit une logique métier **applicable à des cas réels**.

---

## 🔗 Liens utiles
- [Carrousel LinkedIn du projet – à venir]
- [Portfolio complet de projets – bientôt disponible]

---

