# Feature Selection with QuickReduct

## Description du projet
Ce projet vise à sélectionner les attributs les plus importants dans un jeu de données. Une bonne sélection peut améliorer les performances des modèles d'apprentissage automatique en éliminant les informations inutiles.

Nous utilisons principalement l'algorithme **QuickReduct**, qui repose sur la **théorie des rough sets**. Cet algorithme identifie les caractéristiques pertinentes sans avoir besoin d'informations supplémentaires sur les données.

### Comment ça marche
1. **Rough Sets** : Cette méthode regroupe les objets similaires en fonction de leurs attributs et permet de déterminer lesquels sont vraiment importants.
2. **QuickReduct** : Cet algorithme analyse les attributs et sélectionne ceux qui maintiennent la même capacité de prédiction que l'ensemble initial.
3. **Tests et Visualisation** : Nous appliquons ces algorithmes sur des jeux de données du site UCI Machine Learning et montrons les résultats sous forme de graphiques 📊.

### Pourquoi c'est important
La sélection des attributs permet de simplifier les modèles et d'améliorer leur précision, ce qui est crucial dans divers domaines comme la finance, la santé et le marketing.

## Installation
Pour exécuter ce projet, vous aurez besoin de :
- Python 3.11.1
- Jupyter Lab 3.5.3

Assurez-vous d'installer les bibliothèques suivantes :
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- fuzzy-rough-learn
