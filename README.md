# Analyse exploratoire et ACP

## Présentation du projet

L'agence **"Santé publique France"** a lancé un appel à projets pour trouver des idées innovantes d’applications en lien avec l'alimentation.

Avant de présenter notre application, il s'agit d'effectuer un travail nécessaire sur les données.       
La faisabilité de l'applicaton repose sur la qualité de la base de données et la compréhension des données.    

Le travail sur les données est regoupé en deux parties:     
- Nettoyage des données: reccupérer un set exploitable          
- Analyse exploratoire : comprendre la structure des données      

L'application sera présentée succintement dans la conclusion de la partie 2.

### Notebook 1: 🛠 nettoyage des donnéés 
- Représentation graphique des valeurs nulles
- ⌛️Variables temporelles
- Suppression des colonnes identiques
- Gestion des outliers (IQR & Filtres)
- Suppression des variables qualitatives inutiles
- Imputations des données manquantes
    - Imputation par la méthode de la médian      
    - Imputation par la méthode du plus proche voisin KNN
    - Imputation par la méthode Iterative-Imputer 

### Notebook 2 : analyse exploratoire des données


- Analyse en Composantes principales (ACP)
    - Cercle des corrélations
    - Représentation des individus dans le premier cercle factoriel
- Corrélation deux à deux et tests de Pearson     
- Matrice des corrélations
- Analyse graphique
- ANOVA
  
### Conclusion
Ce projet vise à montrer comment utiliser les fonctions et méthodes de base propre à python pour réaliser des clusters, et faire une étude exploratioire complète.   

Ce projet fait partie de la formation data-scientist par CentraleSupélec & Openclassrooms (Certificat niveau bac+5) .



