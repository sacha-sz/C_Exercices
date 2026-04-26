# 📚 NF16 – Travaux Pratiques en C

Ce dépôt contient les codes sources des travaux pratiques (TP) réalisés dans le cadre de l'UV **NF16** à l'UTC, consacrée aux **structures de données et algorithmes en C**.

Chaque TP est organisé dans un dossier indépendant et peut être compilé séparément.

<br/>

## 📌 Contenu des TP

| TP   | Thème principal                          | Dossier              |
|------|------------------------------------------|----------------------|
| TP1  | Bases du langage C                       | [`TP/TP1/`](TP/TP1/) |
| TP2  | Récursivité & complexité                 | [`TP/TP2/`](TP/TP2/) |
| TP3  | Listes chaînées                          | [`TP/TP3/`](TP/TP3/) |
| TP4  | Arbres binaires de recherche (ABR)       | [`TP/TP4/`](TP/TP4/) |

<br/>

## 🗂 Détail des exercices

### TP1 – Bases du langage C

Cinq séries d'exercices couvrant les fondamentaux du C :

| Exercice | Contenu |
|----------|---------|
| **EX1** | Entrées/sorties, variables, types, opérateurs |
| **EX2** | Structures de contrôle (`if`, `switch`, boucles) |
| **EX3** | Tableaux et manipulation de données |
| **EX4** | Pointeurs et passage par référence |
| **EX5** | Chaînes de caractères et fonctions de la bibliothèque standard |

### TP2 – Récursivité & complexité

- **EX1** : Factorielle et Fibonacci — versions itérative et récursive avec comparaison des temps d'exécution
- **EX2** : Exercices complémentaires sur la récursivité

### TP3 – Listes chaînées

Simulation d'une élection présidentielle à l'aide de **listes chaînées** :

- Structure `electeur` (nom, numéro CIN, choix de vote)
- Gestion de plusieurs listes : gauche, droite, blanc
- Interface interactive en ligne de commande

Fichiers : `election_presidentielle.{c,h}`, `interface_presidentielle.{c,h}`, `main.c`

### TP4 – Arbres binaires de recherche (ABR)

Indexation de fichiers texte à l'aide d'un **arbre binaire de recherche** :

- Lecture et parsing de fichiers texte
- Construction d'un index des mots (positions, occurrences)
- Interface interactive en ligne de commande

Fichiers : `texte.{c,h}`, `interface_fichier.{c,h}`, `main.c`

<br/>

## 🛠 Compilation

Un compilateur C standard suffit (GCC recommandé).

```bash
# Exemple pour TP1/EX1
gcc TP/TP1/EX1/TP1-EX1-1.c -o ex1 && ./ex1

# Exemple pour TP3 (plusieurs fichiers)
gcc TP/TP3/*.c -o tp3 && ./tp3

# Exemple pour TP4
gcc TP/TP4/*.c -o tp4 && ./tp4
```

<br/>

## 🧰 Technologies utilisées

- **Langage C** (C99) — [Wikipedia](https://fr.wikipedia.org/wiki/C_(langage))
- **GCC** — compilateur recommandé

<br/>

## 📄 Licence

Ce projet est sous licence **MIT** – voir le fichier [LICENSE](LICENSE) pour plus de détails.

<br/>

## 👤 Auteur

- **[@sacha-sz](https://github.com/sacha-sz)**

<br/>

## 🔗 Références

- [🔒 Cours NF16 sur Moodle (accès UTC requis)](https://moodle.utc.fr/course/view.php?id=673)
- [UTC – Université de Technologie de Compiègne](https://www.utc.fr/)
