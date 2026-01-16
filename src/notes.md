
# Ce que le système doit faire
1- Gestion des colis

# Ce qu'il ne fait pas

# Acteurs:
- Client final
- Opérateur colis
- Oérateur stock
- Administrateur
- La poste
- Système Email

Profil utilisateur:
Opérateur de colis, Opérateur de stock, administrateur


# Actions
- Gestion de colis
- Gestion de la fidélité
- Gestion de stocks de goodies
- Faire les inventaires
- Gestion de liste d'emballage
- Envoie d'email, newsletters, impression de statistiques
- Gestion de profil utilisateur
- Gestion de clients
- Gestion des emplacement

# Point Client




## Action Gestion de colis



# Regle métier
 ## 📦 Règles liées aux commandes et colis

    - Une commande est associée à un seul client

    - Une commande contient un ou plusieurs goodies

    - Une commande donne lieu à un seul colis

    - Un colis est expédié uniquement via La Poste

    - Un colis peut avoir un numéro de suivi postal

    - Les commandes ont un statut (en cours, expédiée, archivée…)
 ## 🎁 Règles liées aux goodies et points

  - Chaque goodies nécessite un nombre précis de points

  - Les stocks de goodies doivent être décrémentés

  - Une commande n’est valide que si les points sont suffisants

 ## Info
   - clients (code client, nom, prénom, genre, adresse, genre, adresse N2, adresse N3, cp, ville, tel, email)
    tous obligatoire sauf: Adresse N°2, Adresse N°3 et email et newsletter

## Profil utilisateur


# contraintes


