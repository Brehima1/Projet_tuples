# Projet : Gestion de Données avec les Tuples en Python

## Description du Projet

Ce projet consiste à gérer des données en Python à l’aide de **tuples** et de **listes**. Il est divisé en deux parties principales :

1. **Partie A – Gestion des Informations Étudiants**
   Dans cette partie, le programme permet de gérer les informations des étudiants d’une école. Chaque étudiant est représenté par un tuple contenant son **nom**, son **âge** et sa **moyenne générale**.

2. **Partie B – Gestion des Personnages (Jeu de Rôle)**
   Cette partie gère des personnages d’un jeu de rôle. Chaque personnage est représenté par un tuple contenant son **nom**, sa **classe** et ses **points de vie**. Le programme montre comment mettre à jour les informations lorsque des changements surviennent (par exemple, des points de vie perdus).

---

## Objectifs du Projet

* Manipuler les **tuples** et les **listes** en Python.
* Savoir **récupérer, modifier et ajouter des données**.
* Calculer des valeurs comme la **moyenne générale**.
* Afficher des informations dans un format **lisible et structuré**.
* Appliquer la notion d’**immutabilité des tuples** et trouver des solutions pour mettre à jour les données.

---

## Partie A – Gestion des Étudiants

### Étapes à réaliser :

1. **Création des tuples :**

   * Créer des tuples pour trois étudiants avec nom, âge et moyenne.
   * Stocker ces tuples dans une liste `etudiants`.

2. **Récupération d’informations :**

   * Afficher le dernier étudiant.
   * Afficher la moyenne du premier étudiant.
   * Récupérer le nom, l’âge et la moyenne du deuxième étudiant dans des variables distinctes.

3. **Ajout d’un étudiant :**

   * Ajouter un nouvel étudiant à la liste.

4. **Calcul de la moyenne générale :**

   * Créer un tuple contenant uniquement les moyennes.
   * Calculer la moyenne générale à partir de ce tuple.

---

## Partie B – Gestion des Personnages

### Étapes à réaliser :

1. **Création des tuples pour les personnages :**

   * Créer des tuples pour trois personnages avec nom, classe et points de vie.
   * Stocker ces tuples dans une liste `personnages`.

2. **Modification des points de vie :**

   * Mettre à jour les points de vie d’un personnage (exemple : Torn perd 20 points de vie) en contournant l’impossibilité de modifier directement un tuple.

3. **Affichage des informations :**

   * Afficher les informations du personnage modifié sous une forme lisible :

     ```
     Nom du personnage : [Nom], Classe : [Classe], Points de vie : [Points de vie]
     ```

---

## Technologies Utilisées

* **Python 3**
* Concepts abordés :

  * Tuples et listes
  * Accès aux éléments d’un tuple
  * Immutabilité des tuples
  * Boucles et fonctions intégrées (`sum`, `len`)
  * Formatage de l’affichage

---

## Organisation du Projet

```
Projet-Tuples/
│
├── README.md            # Ce fichier
├── PartieA_Etudiants.py # Script Python pour la gestion des étudiants
└── PartieB_Personnages.py # Script Python pour la gestion des personnages
```

---

## Instructions pour exécuter le projet

1. Cloner le dépôt :

   ```bash
   git clone <URL_DU_DEPOT>
   ```
2. Se déplacer dans le dossier du projet :

   ```bash
   cd Projet-Tuples
   ```
3. Lancer le script Python correspondant à la partie souhaitée :

   ```bash
   python PartieA_Etudiants.py
   ```

   ou

   ```bash
   python PartieB_Personnages.py
   ```

---

## Auteur

Projet réalisé dans le cadre d’un exercice pédagogique pour la pratique des **structures de données en Python**.

---

## Licence

Ce projet est sous licence MIT. Vous pouvez l’utiliser et le modifier librement.
