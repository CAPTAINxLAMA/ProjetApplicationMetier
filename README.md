# ProjetApplicationMetier
 STEAM2.0
## Rôles :
- User
- Content Creator
- Moderator

## Règles de Gestion :
- Vérifier que le User à payer avant de lui donner le contenu qu'il demande.
- Vérifier que le Content Creator est éligible pour publier du contenu.
- Vérifier que le compte qui souhaite bannir un user ou un content creator est bel et bien Moderator.

## Risques Métier en cas d'incident :
- Le User ne peut plus acheter de contenu.
- Le Content Creator ne voit plus les contenus qu'il a publié.
- Le Moderator ne peut plus bannir qui que ce soit.

## Users Story :
- User peut : 
    - Acheter des contenus.
    - Liker des contenus.
- User ne peut pas : 
    - Créer et publier du contenu.
    - Bannir des User et des Content Creator.
- Content Creator peut :
    - Créer et publier du contenu.
    - Avoir les mêmes droits que les User.
- Content Creator ne peut pas :
    - Bannir des User et des Content Creator.
- Moderator peut :
    - Bannir des User et des Content Creator.
    - Avoir les mêmes droits que les User.
    - Avoir les mêmes droits que les Content Creator.
- Moderator ne peut pas :
    - Bannir d'autres Moderator.
## Matrice de droit :

|          | ajouter des commande | supprimer des commandes | modifier une commande | voir une commande| assigner un livreur à une commande | supprimer le livreur assigné | modifier la date de livraison | supprimer un clients | voir la liste des clients
|----------|---|---|---|---|---|---|---|---|---|
| Admin    | x | x | x | x | x | x | x | x | x |
| manager  |   |   |   | x | x | x | x |   | x |
| client   | x | x | x | x |   |   |   |   |   |
| livreur  | x |   |   | x |   |   | x |   |   |
