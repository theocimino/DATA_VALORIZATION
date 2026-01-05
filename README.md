# DATA_VALORIZATION
Le dataset il va parler mon copain
## Principe
Le but est de mettre en commun le travail pour le projet de valorisation de données. Les analyses sont faites en R.

## DATASET
Le dataset à explorer est [celui-ci](https://www.kaggle.com/datasets/deeplumiere/load-pred-dataset) et le but est de le nettoyer puis pratiquer certaines analyses statistiques de plus en plus poussées, pour finalement faire de la prédiction de features. Ici, on tentera de prédire les chances de remboursement d'un prêt d'argent par une banque en fonction d'une 20aine de features initiales.

## Process 
### Setup de l'environnement
- Cloner le projet en local pour implémenter du code
- Ouvrir la racine du projet dans vscode
- importer l'environnemnt virtuel conda (si conda déjà sur la machine) de la manière suivante :
  ```bash conda env export --from-history > environment.yml```

- Installer l'extension R sur VScode
- Activer l'environnement et le kernel pour coder et faire tourner du code

### Implémentation du code

C'est chill alors on peut push du code sur une branche personnelle ou bien directement sur le main ! 
Quoi qu'il en soit pour mettre en commun le code : 
```bash
# 1. Récupérer le projet une fois
git clone <url>
cd <projet>

# 2. Avant de commencer une nouvelle tâche
git checkout main
git pull
git checkout -b feature/nom_tache

# 3. Pendant que tu codes
git status
git add .
git commit -m "un ptit message sympa pour expliquer tout ça"

# 4. Pousser ta branche
git push -u origin feature/nom_tache   # 1re fois
git push                               # ensuite

# 5. Mettre ta branche à jour avec main (si besoin)
git checkout feature/nom_tache
git merge main

```
! Ces commandes fonctionnent uniquement à la racine ou dans un sous-répertoire du projet.
