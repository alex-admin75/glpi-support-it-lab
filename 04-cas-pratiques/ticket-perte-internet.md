# Cas pratique – Perte de connexion Internet

## Objectif
Ce cas pratique illustre le traitement complet d’un **incident réseau**
dans GLPI, depuis la création du ticket par l’utilisateur
jusqu’à sa résolution par le support IT (Niveau 1).


## Contexte

- Utilisateur : Employé bureautique
- Problème signalé : Plus d’accès à Internet
- Impact : Blocage partiel de l’activité
- Type : Incident réseau


##  Création du ticket

### Acteur
- Utilisateur final

### Informations saisies
- Type : Incident
- Catégorie : Réseau → Perte de connexion Internet
- Urgence : Moyenne
- Titre : Perte de connexion Internet
- Description :
  > Depuis ce matin, je n’ai plus accès à Internet sur mon poste.  
  > Les pages web ne s’ouvrent plus.

### Statut
- **Nouveau**


## Qualification du ticket (N1)

### Acteur
- Technicien support N1

### Actions
- Vérification de la catégorie
- Test de l’impact (poste isolé)
- Prise en charge du ticket

### Statut
- **En cours**

## Diagnostic et traitement

### Actions réalisées
- Vérification du câble réseau
- Vérification de l’adresse IP
- Test de connectivité `ping`
- Redémarrage de la carte réseau

### Résultat
- Problème identifié : carte réseau désactivée

## Résolution

### Action corrective
- Réactivation de la carte réseau
- Test de navigation Internet avec l’utilisateur

### Commentaire de résolution
> La carte réseau était désactivée.
> Réactivation effectuée, accès Internet fonctionnel.

### Statut
- **Résolu**

## 5️⃣ Clôture

### Acteur
- Utilisateur / Support IT

### Action
- Validation du bon fonctionnement
- Clôture du ticket

### Statut
- **Clos**


## Conclusion

Incident résolu au niveau 1.  
Temps de résolution court grâce à un diagnostic standardisé.

