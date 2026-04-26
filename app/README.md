# projet-git-groupe

Projet GIT/GitHub - Site Web

## Gestion des conflits

### Cause du conflit

Deux développeurs ont modifié la même ligne (le titre de la section hero) dans des branches différentes.

### Méthode de résolution

1. `git pull origin develop --allow-unrelated-histories`
2. Résolution manuelle du conflit dans VS Code en choisissant "Accept Both Changes"
3. Modification du titre en "Bienvenue sur notre projet collaboratif"
4. `git add . && git commit -m "fix: resolve merge conflict"`
5. `git push origin feature-conflit-b`
6. Merge de la Pull Request
