# Requêtes incluses
1. ###  Utilisateur qui a reçu le plus de notes
Objectif : Identifier le membre qui a reçu le plus de notes.
Requête : Utilise une jointure entre les tables ratings, member_car, et members pour compter le nombre de notes par membre, puis affiche celui qui a reçu le plus de notes.

2. Utilisateur avec la moyenne de notes la plus élevée
Objectif : Calculer la moyenne des notes pour chaque membre et afficher celui avec la meilleure moyenne.
Requête : Calcule la moyenne des notes données et classe les membres par ordre décroissant pour afficher celui avec la meilleure moyenne.

3. Distribution des notes
Objectif : Compter combien de fois chaque valeur de note (de 1 à 5) a été attribuée.
Requête : Regroupe les notes (grades) et compte combien de fois chaque valeur a été attribuée.

4. Répartition des voitures utilisées dans les trajets
Objectif : Compter combien de trajets ont été effectués avec chaque modèle de voiture.
Requête : Fait une jointure entre les tables cars, member_car, et rides pour compter le nombre de trajets effectués avec chaque voiture.

5. Membres avec le plus grand nombre de trajets et les voitures utilisées
Objectif : Identifier les membres qui ont effectué le plus grand nombre de trajets et les voitures qu'ils ont utilisées.
Requête : Compte le nombre de trajets par membre et par voiture, et affiche les trois membres les plus actifs.

6. Répartition des notes avec CASE pour créer des catégories
Objectif : Classer les notes en catégories ("Mauvais", "Moyen", "Bon") en fonction des valeurs attribuées.
Requête : Utilise la clause CASE pour créer des catégories en fonction des valeurs des notes, puis compte le nombre d'occurrences dans chaque catégorie.

## Tables Utilisées
ratings : Contient les notes données par les membres (grades).
member_car : Contient les relations entre les membres et les voitures utilisées.
members : Informations sur les membres (noms, identifiants, etc.).
cars : Informations sur les voitures (modèles, plaques d'immatriculation).
rides : Détails des trajets effectués par les membres avec leurs voitures.

## Auteur
Chadelle Tcheugoue


