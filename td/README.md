L'objectif de ce TD est de produire un script permettant d'interagir avec une base de donnée contenant des informations de plusieurs personnes (nom, prénom et numéro de sécurité social).
L'interaction avec la base de donnée consiste à récupérer les informations d'une personne et à réaliser des traitements dessus.
Le premier traitement que l'on souhaite réaliser consiste à itérer sur la base de donnée et tester si les numéros de sécurité social énregistrés sont valides.

# Consignes

Créez un dépôt TD_SSN sur Gitlab ou Github

Ajoutez moi à ce dépôt 

Publiez votre code et ses modifications dans le dépôt

# Exercice 1 - Créez un code Python analysant les numéros de sécurité social

Puisque nous souhaitons commencer par analyser la validité des Numéros de Sécurité Social (SSN), vous allez débuter le projet en créant :

- une classe Personne qui :
	- encapsule le nom, prénom et numéro de sécurité social d'une personne
	- possède une méthode publique `has_valid_ssn` qui déclenche l'analyse du SSN et retourne `True` s'il est valide, `False` sinon.
- une classe Ssn qui :
	- encapsule un numéro de sécurité social
	- possède une méthode publique `is_valid` qui retourne `True` si le SSN est valide, `False` sinon.

Un SSN est valide si :

- il est composé des bonnes valeurs possibles
- il a le bon nombre de caractère
- sa clef de contrôle est valide


![alt text](https://github.com/MoraisSebastien/DockerLesson/tree/tmp/readme/td/imgSSN.jpeg?raw=true)
