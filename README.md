# Mon projet Flask DevSecOps

![CI/CD](https://github.com/FarabiTakwa/flask-devsecops-/actions/workflows/ci.yml/badge.svg)

## Description

Ce projet est une *mini application Flask* avec une *pipeline CI/CD sécurisée*.  
Il montre la mise en place d’une intégration continue et d’un déploiement continu avec *Docker*, *GitHub Actions* et *Trivy* pour le scan de vulnérabilités.

- *Stack utilisée :* Python / Flask, Docker, GitHub Actions, Trivy  
- *Fonctionnalité principale :* Page “Hello World” accessible via Flask  
- *Pipeline DevSecOps :*
  - Build de l’image Docker
  - Scan de l’image avec Trivy pour détecter les vulnérabilités
  - Badge CI/CD pour indiquer le succès du build
## Objectif du projet

- Démontrer les bonnes pratiques DevOps et DevSecOps
- Créer un workflow complet d’intégration continue pour un projet web simple

