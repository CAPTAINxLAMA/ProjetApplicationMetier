# ProjetApplicationMetier

## Rôles :
- Client
- Livreur
- Direction

## Règles de Gestion :
- Vérifier que le client à payer avant de réaliser la livraison
- Vérifier que le livreur est disponible pour réaliser le transport
- Vérifier que le compte qui assigne une livraison à un livreur est bel et bien admin


## Risques Métier en cas d'incident :
- Le client ne peut plus commander
- Le livreur ne voit plus les commandes en cours
- La direction ne peut plus effectuer de modifications sur l'appli



## Users Story :
- Client : Ne peut pas modifier les commandes des livreurs
- Livreur : Peut modifier l'ordre des livraisons du lendemain, ne peut pas modifier les commandes si elles sont dans plus de 24H, ne peut modifier que ses commandes
- Direction : Ne peut pas modifier les commandes des livreurs