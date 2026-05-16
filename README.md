# Linux-security-lab

### Objectif : 
*Créer et sécuriser une machine Linux avec gestion des utilisateurs, permissions et accès SSH.*

---
#### Contexte :  

Ce labo fait partie de mon cursus en cybersécurité et me permet de pratiquer la gestion des utilisateurs, des permissions et le durcissement d’un serveur SSH.

---
### Ce que j'ai fait :

- Création d'utilisateurs Linux
- Gestion des permissions fichiers
- Sécurisation SSH
- Configuration firewall UFW
- Analyse des logs système

### Détails des étapes : 

- Créé deux utilisateurs séparés (`adminuser` et `attacker`) avec des rôles distincts.
- Protégé un fichier `secret.txt` en ajustant les permissions Unix (chmod).
- Configuré l'accès SSH et vérifié les tentatives de connexion dans les logs système.
- Activé et configuré le firewall UFW pour autoriser uniquement le trafic SSH nécessaire.

### Technologies utilisées :

- VirtualBox
- Linux Ubuntu
- SSH
- UFW firewall

## Résultats :

Voir dossier screenshots.