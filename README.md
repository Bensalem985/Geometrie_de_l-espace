## 📄 README du Projet Géométrie C++

Ce projet implémente les structures de données de base `Point2f` et `Vector2f` ainsi que les opérations géométriques associées, comme la translation, la rotation, l'addition de vecteurs, le produit scalaire, et la normalisation.

-----

### 📂 Structure du Projet

Les fichiers d'en-tête et les implémentations des classes géométriques se trouvent dans le dossier `geometry/`.

```
.
├── geometry/
│   ├── point.h        (Définition de Point2f)
│   ├── point.cpp      (Implémentation des fonctions de Point2f)
│   ├── vector.h       (Définition de Vector2f)
│   ├── vector.cpp     (Implémentation des fonctions de Vector2f)
│   └── utils.h        (Templates utilitaires: ToString, Print)
└── main.cpp           (Fichier principal de démonstration)
```

-----

### 🛠️ Compilation

Pour compiler le projet, vous devez lier tous les fichiers sources (`.cpp`) ensemble.

Exécutez la commande suivante depuis la **racine du projet** (le répertoire contenant `main.cpp` et le dossier `geometry/`) :

```bash
g++ main.cpp geometry/point.cpp geometry/vector.cpp -o geometrie -I geometry
```

  * **`-I geometry`**: Indique au compilateur de chercher les fichiers d'en-tête (ex: `#include "geometry/point.h"`) dans le dossier `geometry`.

### ▶️ Exécution

Après la compilation, exécutez le programme :

```bash
./geometrie
```

Le programme affichera les résultats des tests unitaires pour les opérations sur les points et les vecteurs.

### 🪪 Infos de l'étudiant

Nom: EPONSE MEKONTSO BEN-SALEM EMMANUEL.

Matricule: 25P927
