# Prédiction du Diabète à partir de Dossiers Médicaux

## Description du projet
Ce projet vise à prédire la probabilité qu'une personne soit atteinte de diabète en utilisant des dossiers médicaux. Le modèle est entraîné à partir de la base de données des Indiens Pima, qui contient plusieurs indicateurs médicaux tels que le nombre de grossesses, le taux de glucose, la pression artérielle, et d'autres facteurs. L'objectif est de construire un modèle de machine learning capable de classifier efficacement les patients en deux catégories : diabétique ou non-diabétique.

## Contexte
Le diabète, ou diabète sucré (Diabetes Mellitus - DM), est un groupe de troubles métaboliques caractérisé par un taux élevé de sucre dans le sang sur une longue période. Il existe principalement deux types de diabète :

- **Type 1** : Résultant de la destruction des cellules productrices d'insuline dans le pancréas, empêchant ainsi le corps de produire suffisamment d'insuline.
- **Type 2** : Associé à une résistance à l'insuline, où les cellules du corps ne répondent pas correctement à cette hormone.

La majorité des cas de diabète sont de type 2, représentant environ 90 % des cas. Selon des estimations de 2015, 415 millions de personnes dans le monde étaient atteintes de diabète, soit 8,3 % de la population adulte.

## Jeu de données
Le jeu de données utilisé pour ce projet provient de la base de données des Indiens Pima et contient les variables suivantes :

- **Nombre de grossesses (Pregnancies)**
- **Niveau de glucose (Glucose)**
- **Pression artérielle (BloodPressure)**
- **Épaisseur de la peau (SkinThickness)**
- **Insuline (Insulin)**
- **Indice de masse corporelle (IMC) (BMI)**
- **Fonction hérédité du diabète (DiabetesPedigreeFunction)**
- **Âge (Age)**


## Prérequis
Les bibliothèques Python suivantes sont nécessaires pour exécuter ce projet :

`pip install pandas scikit-learn matplotlib seaborn`

## Exécution du projet

1. **Chargez et analysez les données dans un notebook Python.**
2. **Prétraitez les données** gestion des valeurs manquantes, normalisation.
3. **Entraînez différents modèles de machine learning** régression logistique, SVM, etc.
4. **Évaluez les performances du modèle** sur un ensemble de test.
5. **Enregistrez et visualisez les résultats.**
