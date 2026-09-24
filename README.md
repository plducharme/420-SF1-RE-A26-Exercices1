# 420-SF1-RE Exercice individuel noté 1 Automne 2026

## Décomposition d'un nombre en somme de puissances et calcul de la somme des chiffres

### Instructions
- Le code doit être contenu dans le ficheir ``decomposition.py``
- Écrire votre nom. prénom et utilisateur github dans l'espace prévu à cet effet dans le fichier
- Faire un ``commit and push`` dans Pycharm effectue une remise.
  - Vous pouvez faire plusieurs remises, la dernière version à la date limite de remise sera corrigée.
  - Pour faire un ``commit and push``
    - utiliser la vue ``commit`` en haut à gauche
    - sélectionner ``decomposition.py``
    - Entrer un commentaire
    - cliquer sur ``commit and push``
    - Vous pouvez vérifier dans votre dépôt dur github que le ``push`` a fonctionné

![commit and push](commitpush.png)

### Requis fonctionnels
Écrire un programme Python qui demande à l'utilisateur de saisir un nombre positif. Le programme doit :
1.	Décomposer le nombre saisi en une somme de puissances de 10.
2.	Calculer la somme des factoriels des chiffres de ce nombre.
3.	Répéter l'opération tant que l'utilisateur ne saisit pas 0 (zéro).

#### Exemple 1 de fonctionnement
```
Entrez un nombre positif (0 pour arrêter) : 543
543 = 5*10**2 + 4*10**1 + 3*10**0
La somme des factoriels des chiffres de 543 est : 150
```
*Respectez l'affichage demandé (i.e. l'espace avant et après le ``+``)*

**Explication**

- Décomposition: 543= 5 x 10<sup>2</sup> + 4 x 10<sup>1</sup> + 3 x 10<sup>0</sup>
- Somme des factoriels
  - 5! = 120
  - 4! = 24
  - 3! = 6
  - Somme = 120 + 24 + 6 = 140

#### Exemple 2 de fonctionnement
```
Entrez un nombre positif (0 pour arrêter) : 205
205 = 2*10**2 + 0*10**1 + 5*10**0 
La somme des factoriels des chiffres de 205 est : 122
```

**Explication**
- Décomposition: 205 = 2 x 10<sup>2</sup> + 0 x 10<sup>1</sup> + 5 x 10<sup>0</sup>
- Somme des factoriels
  - 2! = 2
  - 0! = 1
  - 5! = 120
  - Somme = 2 + 1 + 120 = 123


### Rappel sur les factoriels
``n! = n*(n-1)*(n-2)*...*1``
- Le factoriel de 0 est égal à 1
- Le factoriel est seulement défini pour les entiers positifs

* Note: il est possible d'utiliser ``math.factorial(n)`` 


### Barême de correction
- L'exercice est noté sur 20 et compte pour 5% de la note finale
  - 3 points pour les commentaires
    - Vos commentaires devrait expliqués la logique subséquente
    - L'utilité des variables déclarées
  - 14 points pour la logique et le bon fonctionnement du code
  - 3 points pour le respect de l'affichage
- Des points seront enlevés pour :
  - nom d'identificateurs non significatifs
  - Non-respect des PEP-008 (conventions de python)


