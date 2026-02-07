# Configuration initiale de GLPI

### Objectif
Ce document décrit la configuration initiale de **GLPI 10.0.6** après installation,
afin de préparer l’outil à une utilisation en **support informatique professionnel**.
L’objectif est de disposer d’un environnement structuré pour la gestion des tickets
et le travail des équipes de support **niveau 1 et 2**.


## 1. Connexion et sécurisation du compte administrateur

### Connexion initiale
- URL : 
```arduino 
http://<IP_SERVEUR>/
```
- Identifiants par défaut :
  - Utilisateur : `glpi`
  - Mot de passe : `glpi`

### Actions à réaliser
- Changer immédiatement le mot de passe administrateur
- Vérifier la langue et le fuseau horaire


## 2. Paramétrage général de GLPI

###  Accès
`Configuration → Générale`

### Paramètres importants
- **Nom de l’application** : GLPI – Support IT
- **Fuseau horaire** : Europe/Paris
- **Format de date** : jj/mm/aaaa
- **Suivi des tickets** : Activé


## 3. Création des profils utilisateurs

### Accès
`Administration → Profils`

### Profils mis en place

#### Utilisateur (Self-service)
- Création de tickets
- Suivi de ses propres tickets
- Ajout de commentaires

#### Support N1 & N2
- Accès à tous les tickets
- Modification du statut des tickets
- Ajout de suivis et solutions
- Attribution de tickets

#### Administrateur
- Accès complet à GLPI
- Gestion des utilisateurs, profils et paramètres
- Supervision globale


## 4. Création des utilisateurs

### Accès
`Administration → Utilisateurs`

### Types d’utilisateurs
- Utilisateurs finaux (employés)
- Techniciens support
- Administrateurs GLPI

Pour chaque utilisateur :
- Nom / Prénom
- Identifiant
- Profil associé
- Entité (par défaut)


## 5. Paramétrage des catégories de tickets

### Accès
`Configuration → Catégories`

### Exemple de catégories
- Réseau
  - Perte de connexion Internet
  - Wi-Fi indisponible
- Matériel
  - Poste ne démarre pas
  - Écran défectueux
- Logiciel
  - Application non fonctionnelle
  - Problème de licence

## 6. Paramétrage des urgences et priorités

### Accès
`Configuration → Urgences`  
`Configuration → Priorités`

### Exemple de niveaux
- Faible
- Moyenne
- Haute
- Critique

Les priorités permettent de mieux organiser le traitement des tickets selon leur impact.


## 7. Paramétrage des statuts de tickets

Statuts utilisés dans le workflow :
- Nouveau
- En cours
- En attente
- Résolu
- Clos

Ces statuts permettent de suivre précisément l’avancement du traitement des incidents.


## 8. Configuration des notifications

### Accès
`Configuration → Notifications`

Notifications possibles :
- Création de ticket
- Attribution à un technicien
- Changement de statut
- Résolution du ticket

Les notifications peuvent être envoyées par e-mail selon les profils.

## 9. Vérification du fonctionnement

### Tests réalisés
- Création d’un ticket par un utilisateur
- Attribution du ticket à un technicien
- Changement de statut
- Ajout d’un suivi
- Résolution et clôture du ticket

### Résultat attendu
- Workflow fonctionnel
- Interface claire
- Gestion fluide des tickets



