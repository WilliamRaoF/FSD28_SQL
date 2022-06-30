# Partie 1:

En utilisant les tables cities, departments et regions

Exercice 1

Quelle requête utiliser pour retrouver la ville qui possède les coordonnées GPS suivantes : 48.66913724637683, 1.87586057971015 ?

Exercice 2

Sans jointure, quelle requête utiliser pour calculer le nombre de villes que compte le département de l'Essonne ?

Exercice 3

Sans jointure, quelle requête utiliser pour calculer le nombre de villes en Île-de-France se terminant par "-le-Roi" ?

Exercice 4

Combien de villes possèdent le code postal (zip_code) 77320 ? Renommez la colonne de résultat n_cities.

Exercice 5

Sans jointure, quelle requête utiliser pour calculer le nombre de villes commençant par "Saint-" en Seine-et-Marne ?

Exercice 6

Quelles villes possèdent un code postal (zip_code) compris entre 77210 et 77810 ?

Exercice 7

Sans jointure, quelles sont les deux villes de Seine-et-Marne à avoir le code postal (zip_code) le plus grand ?

Exercice 8

Quel est le code postal (zip_code) le plus grand de la table cities ?

Exercice 9

Avec un seul WHERE et aucun OR, quelle est la requête permettant d'afficher les départements des régions ayant le code suivant : 75, 27, 53, 84 et 93 ? Le résultat doit afficher le nom du département ainsi que le nom et le slug de la région associée.

Exercice 10

Point important, il sera sans doute nécessaire d'utiliser AS pour obtenir le résultat souhaité.

Quelle requête utiliser pour obtenir en résultat, les noms de la région, du département et de chaque ville du département ayant pour code 77 ? 


# Partie 2:

En utilisant les tables covid et regions

Exercice 1

Quelle requête utiliser pour afficher toutes les données de vaccination uniquement pour le 1er avril 2021 ?

Exercice 2

Quelle requête utiliser pour afficher toutes les données de vaccination uniquement pour le 1er avril 2021 avec le nom de la région concernée ?

Exercice 3

Quelle requête utiliser pour afficher le nombre au cumulé de vaccination première dose toutes régions en 2020 ? Proposez également une solution pour les vaccination deuxième dose.

Exercice 4

Quelle requête SQL utiliser pour afficher le nombre au cumulé de vaccination première dose pour la région avec le code 93 uniquement pour le mois de mars 2021 ?

Exercice 5

Quelle requête utiliser pour afficher le nombre au cumulé de vaccination deuxième dose pour la région avec le code 11 uniquement pour le mois de mars 2021 ?

Exercice 6

Quelle requête SQL utiliser pour afficher le record de vaccination première dose en une seule journée ? Avec une deuxième requête, afficher les informations de la région concernée, dont son nom, ainsi que le jour du record.

Exercice 7

Quelle requête utiliser pour afficher le record de vaccination deuxième dose en une seule journée ? Avec une deuxième requête, afficher les informations de la région concernée, dont son nom, ainsi que le jour du record.

Exercice 8

Quelles requêtes permettent de connaitre quelle région possède la plus grande couverture de vaccination avec une dose et deux doses ? Vous aurez besoin de 4 requêtes pour répondre aux deux questions. Vous aurez besoin du résultat de la première requête pour la deuxième.

Exercice 9

Quelle requête utiliser pour afficher le nom de la région qui a le plus faible taux de couverture de vaccination avec une dose ? Vous aurez besoin de 2 requêtes pour répondre à la question.

Exercice 10

Quelle requête utiliser pour calculer la couverture moyenne entre les différentes régions à la date la plus récente, pour les vaccinations une et deux doses ? Vous renommez les colonnes de résultats : couverture_dose1_avg et couverture_dose2_avg.

Exercice 11

Quelle requête utiliser pour afficher les données de vaccination des régions (avec leur nom) qui possèdent une couveture vaccinale supérieure à 15 % pour la première dose et supérieure à 5 % pour la deuxième dose ?


# Partie 3:

En utilisant les tables covid_vaccin, covid_vaccin_type et departments

Exercice 1

Sans jointure, quelle requête SQL utiliser pour afficher toutes les données de vaccination du 14 février 2021 uniquement, pour le département de Seine-et-Marne (77) ?

Exercice 2

Sans jointure, quelle requête SQL utiliser pour afficher le cumul de toutes les données de vaccination pour tous les vaccins du 14 février 2021 uniquement, pour les départements de l'Essonne (91) et de la Seine-et-Marne (77) ?

Exercice 3

Sans jointure, quelle requête utiliser pour afficher la somme des vaccinations première dose réalisées uniquement avec le vaccin AstraZeneka pour le mois de février 2021 pour le département de la Seine-et-Marne (77) ?

Exercice 4

Sans jointure, quelle requête utiliser pour afficher la somme des vaccinations deuxième dose réalisées avec le vaccin AstraZeneka ou Moderna pour le mois de mars 2021 pour le département de la Seine-et-Marne (77) ?

Exercice 5

Sans jointure, quelle requête utiliser pour afficher le record de vaccination première dose avec un type de vaccin en une seule journée ? Avec une deuxième requête qui exploitera une jointure, afficher toutes les informations possibles pour cette journée record et sur le type de vaccin.

Exercice 6

Sans jointure, quelle requête utiliser pour afficher le record de vaccination deuxième dose avec un type de vaccin en une seule journée ? Avec une deuxième requête qui exploitera deux jointures, afficher toutes les informations possibles pour cette journée record, sur le type de vaccin et sur le département.

Exercice 7

Quelle requête permet de savoir quel département possède le plus grand nombre d'injections première dose pour le vaccin AstraZeneka ? Avec une deuxième requête, afficher uniquement les colonnes suivantes :

    le nom du vaccin ;
    le jour ;
    le nom et le code du département ;
    le nombre cumulé d'injections.

Exercice 8

Quelle requête permet de savoir quel département a eu le moins de vaccinations première dose avec le vaccin COMIRNATY Pfizer/BioNTech ? Avec une deuxième requête, afficher uniquement les colonnes suivantes :

    le nom du vaccin ;
    le jour ;
    le nom et le code du département ;
    le nombre cumulé d'injections.

Exercice 9

Quelle requête permet de connaître la moyenne de vaccinations première dose dans tous les départements pour le vaccin Moderna ? Renommer la colonne de résultat avec avg_moderna.

Exercice 10

Quelle requête utiliser pour afficher les départements (avec leur nom) qui possèdent un nombre d'injections deuxième dose avec le vaccin Moderna supérieur à 9000 ou un nombre d'injections première dose avec le vaccin COMIRNATY Pfizer/BioNTech supérieur à 120000 ? Vous aurez besoin de deux jointures.


# Partie bonus:

Quelle requête SQL utiliser pour compter, sans doublons, le nombre de professionnels de santé en Seine-et-Marne (77) ?

Exercice 2

Quelle requête SQL utiliser pour afficher pour tous les professionnels de santé avec le code postal 77300 les colonnes suivantes : id_pp_nat, prenom, nom, code_postal, ville, departement et région. Vous aurez besoin de plusieurs jointures.
