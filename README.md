# Les principales fonctions d'openpyxl

La documentation officielle est disponible [ici](https://openpyxl.readthedocs.io/en/stable/tutorial.html).

---

## I. Récupérer le code

```bash
git clone https://github.com/surybang/medas_openpyxl.git
cd quick_tutorial_openpyxl
```

> 💡 Vous pouvez aussi **forker** ce dépôt pour le garder sur votre propre GitHub et y revenir plus tard.

---

## II. Configurer l'environnement

Ce projet utilise [uv](https://github.com/astral-sh/uv) pour gérer les dépendances.

Si `uv` n'est pas installé sur votre poste :

```bash
pip install uv # dans le Terminal
```

Synchronisez ensuite l'environnement virtuel :

```bash
uv sync
```

---

## III. Utiliser le tutoriel

1. Ouvrez `tutorial.ipynb` dans VS Code
2. Exécutez la première cellule (`pip install -e .`) pour installer les dépendances
3. Exécutez les cellules suivantes **dans l'ordre**
3. Vérifiez les modifications dans les fichiers générés (`fichier.xlsx`, `rapport.xlsx`)
4. Expérimentez avec les paramètres
5. Consultez la [documentation](https://openpyxl.readthedocs.io) pour approfondir
