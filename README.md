# Desktroo — catalogue du Magasin

Catalogue des apps du Magasin de [Desktroo](https://desktroo.fr), le bureau web pour TrueNAS.
Seules les apps Mdm-services.fr y figurent ; elles sont comprises dans l'abonnement Desktroo.

- `catalog.json` : la liste des apps, lue par Desktroo.
- `catalog.json.sig` : sa signature. Desktroo refuse un catalogue non signé, modifié ou plus ancien que le sien.
- `icons/`, `screens/`, `RELEASES/` : visuels et nouveautés affichés dans le Magasin.

Ne pas modifier ces fichiers à la main sur GitHub : ils sont publiés par `publish-store.ps1`.

© 2026 Mdm-services.fr. Tous droits réservés.
