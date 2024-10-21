# KendoApp

## Matrice des exigences

### Organisez les exigences par catégorie :
- Fonctionnelles : fonctionnalités, cas d’utilisation, scénarios. (ID EF-)
- Non fonctionnelles : performances, sécurité, compatibilité, accessibilité. (ID ENF-)
- Contraintes : contraintes liées au matériel, au logiciel ou à l'environnement de développement. (ID CN-)

### Explications des colonnes :
- ID : Identifiant unique de l'exigence (ex : EF-001 pour exigence fonctionnelle, ENF-001 pour exigence non fonctionnelle).
- Catégorie : Fonctionnelle ou Non fonctionnelle.
- Description de l'exigence : Explication détaillée de l'exigence.
- Priorité : Priorité (ex : Élevée 3, Moyenne 2, Faible 1).
- Source : D’où provient l’exigence (ex : document, réunion avec les parties prenantes).
- Cas de Test associé : Cas de test qui valide cette exigence.
- Statut : Statut actuel de l’exigence (ex : En cours, Termine, A faire).

### Tableau

|ID|Catégorie|Description de l'exigence|Priorite|Source|Id test|Statut
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
|EF-001|Fonctionnelle|Saisie des inscriptions via fichier formaté|3|pratique fédérale (pré-inscription)||A faire|
|EF-002|Fonctionnelle|Saisie des inscriptions via formulaire|1|||A faire|
|EF-003|Fonctionnelle|Saisie des informations de la compétition via formulaire|3|obligation fédérale||A faire|
|ENF-001|Non Fonctionnelle|fichier format libre (texte, XML, ...) pour le stockage des données|3|choix de format non propriétaire||A faire|
|EF-004|Fonctionnelle|répartition aléatoire des compétiteurs dans les poules (1ere phase de la compétition)|3|norme fédérale||A faire|
|EF-005|Fonctionnelle|option : placer 4 compétiteurs identifiés dans chacune des 4 premières poules en position 1|1|norme fédérale pour certaines compétitions||A faire|
|ENF-002|Non Fonctionnelle|format PDF pour les sorties impression|2|||A faire|
|EF-006|Fonctionnelle|editer les feuilles de poules|3|modèle fédéral||A faire|
|EF-007|Fonctionnelle|saisie des résultats des poules via formulaire|3|||A faire|
|EF-008|Fonctionnelle|option : choix du type de poule (poule de 3, 4 ou 5)|1|||saisie des résultats des poules via formulaire|
|EF-009|Fonctionnelle|répartir les compétiteurs sortie de poule dans le tableau final|3|tableau modèle fédéral||A faire|
|EF-010|Fonctionnelle|saisie des résultats du tableau final via formulaire|3|||A faire|
|CN-001|Contrainte|langage de développement multiplateforme (windows, linux, mac)|2||||
||||||||
||||||||

### Tableau des sources

|ID|Lien/image|
|:-----:|:-----|
|EF-006||
|EF-009||
|||
