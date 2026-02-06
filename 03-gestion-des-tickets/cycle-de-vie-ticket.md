# Cycle de vie d’un ticket dans GLPI

## Objectif
Ce document décrit le **cycle de vie complet d’un ticket** dans GLPI,
depuis sa création par l’utilisateur jusqu’à sa clôture.
Il s’inscrit dans un contexte de **support informatique niveau 1 et niveau 2**.


##  Vue d’ensemble du cycle de vie

Le cycle de vie d’un ticket suit généralement les étapes suivantes :

1. Création
2. Qualification
3. Attribution
4. Traitement
5. Résolution
6. Clôture

Chaque étape correspond à un **statut** dans GLPI et à une action précise du support IT.


## Création du ticket

### Acteur
- Utilisateur final

### Statut
- **Nouveau**

### Actions
- Description du problème
- Choix de la catégorie
- Définition de l’urgence

### Résultat
- Le ticket est visible par l’équipe support
- Un numéro de ticket est attribué


## Qualification du ticket

### Acteur
- Technicien support (N1)

### Statut
- **En cours**

### Actions
- Analyse du problème
- Vérification de la catégorie
- Ajustement de l’urgence ou priorité
- Demande d’informations complémentaires si nécessaire

### Résultat
- Le ticket est correctement qualifié
- La priorité de traitement est définie


##  Attribution du ticket

### Acteur
- Technicien support ou responsable IT

### Statut
- **En cours**

### Actions
- Attribution à un technicien
- Ajout d’un suivi interne
- Planification de l’intervention si nécessaire

### Résultat
- Le ticket est pris en charge officiellement


## Traitement du ticket

### Acteur
- Technicien support (N1 / N2)

### Statut
- **En cours** ou **En attente**

### Actions
- Diagnostic technique
- Tests et vérifications
- Intervention à distance ou sur site
- Escalade vers le niveau 2 si nécessaire

### Cas particulier : En attente
- Attente de retour utilisateur
- Attente de matériel ou d’une action externe


##  Résolution du ticket

### Acteur
- Technicien support

### Statut
- **Résolu**

### Actions
- Application de la solution
- Description détaillée de la résolution
- Communication vers l’utilisateur

### Résultat
- Le service est rétabli
- Le ticket est prêt à être clôturé


## Clôture du ticket

### Acteur
- Utilisateur ou support IT

### Statut
- **Clos**

### Actions
- Validation de la solution
- Clôture définitive du ticket

### Résultat
- Le ticket est archivé
- Historique conservé pour le reporting

## Bonnes pratiques support IT

- Toujours documenter les actions réalisées
- Mettre à jour le statut à chaque étape
- Communiquer clairement avec l’utilisateur
- Respecter les délais de traitement
- Clôturer uniquement après validation


##  Conclusion

Un cycle de vie bien défini permet :
- Une meilleure organisation du support
- Une traçabilité complète
- Une qualité de service améliorée



