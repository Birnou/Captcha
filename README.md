# CAPTCHA Mathématique en PHP

Ce projet propose une solution simple et sécurisée de CAPTCHA basé sur des opérations mathématiques. Il permet de protéger un formulaire contre les soumissions automatisées en demandant à l'utilisateur de résoudre un calcul simple.

## Fonctionnalités

- **Génération dynamique** d'une image contenant une opération mathématique.
- **Système de tokens** pour lier chaque CAPTCHA à une réponse unique et temporaire.
- **Validation côté serveur** pour s'assurer que l'utilisateur a bien résolu le CAPTCHA.
- **Transmission des données en JSON**, facilitant l'intégration avec JavaScript.
- **Sécurité renforcée** : chaque CAPTCHA est unique et ne peut être réutilisé.

## Installation

### Prérequis
- Serveur web avec **PHP 7.4+**
- Extension **GD** activée pour la manipulation des images
- **Apache, Nginx** ou tout serveur prenant en charge PHP

### Téléchargement et configuration
