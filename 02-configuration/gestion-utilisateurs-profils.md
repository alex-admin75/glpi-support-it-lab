# Gestion des utilisateurs et des profils dans GLPI

Une bonne gestion des **utilisateurs** et des **profils** dans GLPI, facilite
le contrôler les droits d’accès et les responsabilités de chaque acteur
dans un contexte de **support informatique professionnel**.
Elle permet aussi d’assurer la sécurité, la traçabilité
et l’efficacité du traitement des tickets.


## 1. Concepts clés

### Utilisateur
Un utilisateur représente une personne utilisant GLPI :
- Utilisateur final
- Technicien support
- Administrateur

### Profil
Un profil définit :
- Les droits d’accès
- Les actions autorisées
- Les fonctionnalités visibles

Un utilisateur peut être associé à **un ou plusieurs profils**.  

### Accès à la gestion des profils

GLPI propose des profils par défaut, qui peuvent être personnalisés
ou dupliqués selon les besoins.

## 2. Profils utilisés dans le projet

### Profil Utilisateur (Self-service)

**Rôle :**
Utilisateur final déclarant des incidents.

**Droits principaux :**
- Créer un ticket
- Consulter ses tickets
- Ajouter des suivis/commentaires
- Joindre des fichiers

**Restrictions :**
- Pas d’accès aux tickets des autres utilisateurs
- Pas de modification de statut

### Profil Support N1
**Rôle :**  
Qualification des demandes utilisateurs, traitement des incidents simples et escalade vers le support N2 si nécessaire.  
**Droits principaux :**
- Accès aux tickets qui lui sont assignés ou à son groupe
- Créer et consulter des tickets
- Modifier le statut des tickets (Nouveau, En cours, En attente)
- Ajouter des suivis (commentaires, actions effectuées)
- Qualifier les tickets (catégorie, priorité, impact)
- S’attribuer un ticket
- Escalader un ticket vers le support N2  

**Fonctionnalités clés :**
- Vue filtrée des tickets N1
- Ajout de commentaires et d’actions de diagnostic
- Lien entre ticket et équipement (lecture seule)
- Respect des procédures et délais de prise en charge

### Profil Support N2

**Rôle :**
Prise en charge et résolution des incidents.

**Droits principaux :**
- Accès à l’ensemble des tickets
- Modifier le statut des tickets
- Ajouter des suivis techniques
- Proposer et valider des solutions
- S’attribuer ou attribuer un ticket

**Fonctionnalités clés :**
- Vue globale des tickets
- Historique des actions
- Traçabilité complète


### Profil Administrateur

**Rôle :**
Administration globale de GLPI.

**Droits principaux :**
- Accès total à GLPI
- Gestion des utilisateurs et profils
- Paramétrage global
- Gestion des plugins
- Supervision et reporting


## 3. Création et gestion des utilisateurs

### Informations configurées
- Nom / Prénom
- Identifiant de connexion
- Adresse e-mail
- Profil associé
- Entité

### Bonnes pratiques
- Un compte par utilisateur
- Profils attribués selon le rôle réel
- Pas de comptes partagés


## 4. Attribution des profils

Chaque utilisateur se voit attribuer :
- Un **profil**
- Une **entité**
- Un niveau d’accès cohérent avec son rôle

## 5. Sécurité et bonnes pratiques

- Principe du **moindre privilège**
- Séparation des rôles (user / tech / admin)
- Comptes administrateurs limités
- Journalisation des actions
- Changement régulier des mots de passe



