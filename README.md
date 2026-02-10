# 🎯 TD Git - Maîtrisez le Contrôle de Version
test
Bienvenue dans ce TD pratique de **3 heures** pour maîtriser Git ! 🚀

Ce TD vous guidera à travers **4 phases progressives** pour apprendre les concepts essentiels de Git : de la création de branches aux techniques avancées de récupération de commits. Vous allez manipuler l'historique, créer des hooks Git, et découvrir comment Git garde trace de tout.

## 📋 Prérequis

Avant de commencer, assurez-vous d'avoir :

- ✅ **Git** installé sur votre machine
- ✅ Un **IDE** ou éditeur de texte (VS Code, Sublime, etc.)
- ✅ Une connaissance de base de Git (commit, push, pull)
- ✅ Un compte GitHub et accès en écriture à ce dépôt

## 🗺️ Les 4 Phases du TD

### [Phase 1 : Les Bases 🌱](doc/phase-1-basics.md)
*Durée estimée : 15-20 min*

Créez votre première branche, ajoutez votre nom dans le fichier `authors.md`, et poussez vos modifications. Une révision rapide des fondamentaux pour bien démarrer.

**Objectif** : Maîtriser les branches et les commits conventionnels

---

### [Phase 2 : Git Hooks 🪝](doc/phase-2-hooks.md)
*Durée estimée : 30-60 min*

Votre Senior en a marre des messages de commit sales ! Créez un hook Git qui force l'utilisation de Conventional Commits. Si le message ne commence pas par `feat:`, `fix:`, ou `chore:`, le commit doit échouer.

**Objectif** : Automatiser la qualité des commits avec un hook `commit-msg`

---

### [Phase 3 : Nettoyer l'Historique 🧹](doc/phase-3-history.md)
*Durée estimée : 20-30 min*

Oups ! Un fichier `.env` avec des secrets s'est retrouvé dans votre historique Git. Vous devez le supprimer avant que quelqu'un ne le voie. Apprenez à réécrire l'historique Git en toute sécurité.

**Objectif** : Supprimer un commit de l'historique avec `git reset` ou `git rebase`

---

### [Phase 4 : L'Investigation 🔍](doc/phase-4-recovery.md)
*Durée estimée : 40-60 min*

Git ne perd jamais rien ! Vous allez enquêter sur la branche d'un autre étudiant pour retrouver un commit "supprimé", décoder un secret, et prouver vos talents de détective Git.

**Objectif** : Utiliser `git reflog` pour récupérer des commits perdus

---

## 💡 Conseils pour Réussir

- 🤝 **Entraide** : N'hésitez pas à vous aider entre étudiants
- 🔍 **Recherche** : Google et la documentation Git sont vos amis
- ⚠️ **Attention** : Certaines commandes sont destructives, lisez bien avant d'exécuter
- 🎯 **Objectif** : Comprendre les concepts, pas juste finir vite

## 📚 Ressources Additionnelles

Une fois le TD terminé, voici quelques ressources pour aller plus loin :

### Documentation Officielle
- [Git Documentation](https://git-scm.com/doc) - La référence complète
- [Pro Git Book](https://git-scm.com/book/fr/v2) - Le livre gratuit en français

### Git Hooks
- [Git Hooks Guide](https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks) - Tous les hooks disponibles
- [Conventional Commits](https://www.conventionalcommits.org/) - La spécification complète

### Commandes Avancées
- [Git Reflog Explained](https://git-scm.com/docs/git-reflog) - Récupérer l'impossible
- [Interactive Rebase](https://git-scm.com/book/en/v2/Git-Tools-Rewriting-History) - Réécrire l'historique

### Nettoyage d'Historique
- [Git Filter-Repo](https://github.com/newren/git-filter-repo) - Outil recommandé pour nettoyer l'historique
- [BFG Repo-Cleaner](https://rtyley.github.io/bfg-repo-cleaner/) - Alternative rapide pour supprimer des fichiers sensibles
- [Removing Sensitive Data](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/removing-sensitive-data-from-a-repository) - Guide GitHub officiel

---

## 🚀 Prêt à Commencer ?

Rendez-vous sur [Phase 1](doc/phase-1-basics.md) pour démarrer votre aventure Git !

Bon courage ! 💪
