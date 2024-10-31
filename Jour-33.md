# Objectifs journaliers

## Mercredi 30/10/2024 :

### Introduction à PostgreSQL et DCL

- [X] Découverte de PostgreSQL
  - [X] Identifier les différences entre MySQL et PostgreSQL
  - [W] Savoir Expliquer les avantages de PostgreSQL
  - [X] Savoir Choisir les cas d'usage adaptés à PostgreSQL

- [ ] Installation et Configuration
  - [X] Installation de PostgreSQL sur la machine
  - [X] Installation de pgAdmin 4
  - [X] Installation de pgcli
  - [ ] Configuration initiale
    - [X] Ports
    - [X] Mot de passe postgres
    - [X] Création du premier utilisateur
  - [X] Test de la connexion

- [X] Data Control Language (DCL)
  - [X] Gestion des utilisateurs
    - [X] Savoir construire des requêtes CREATE USER
    - [X] Savoir modifier des utilisateurs avec ALTER USER
    - [X] Savoir supprimer des utilisateurs avec DROP USER
    - [X] Savoir utiliser les rôles PostgreSQL
  
  - [ ] Gestion des droits
    - [X] Savoir attribuer des privilèges avec GRANT
      - [X] Droits sur les bases de données
      - [ ] Droits sur les tables
      - [ ] Droits sur les colonnes
    - [X] Gérer la révocation avec REVOKE
      - [ ] Comment retirer des droits sur une base de données, une table ou une colonne ?
      - [ ] Quel est l'impact d'une révocation en cascade ?

  - [ ] Les bonnes pratiques de sécurité
    - [ ] Comment appliquer le principe du moindre privilège dans PostgreSQL ?
    - [ ] Quand utiliser des rôles plutôt que des utilisateurs individuels ?
    - [ ] Comment auditer efficacement les droits d'accès ?