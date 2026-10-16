# Polynesia Connect — event images

*[Version française plus bas](#version-française)*

Images generated automatically for the events agenda of [polynesiaconnect.com](https://www.polynesiaconnect.com/evenements-en-cours).
This repository is public only so the website can import the images by URL; the site then keeps its own copy.

Layout: `YYYY/<event-slug>.jpg` (1200×810). Images are referenced by commit-pinned URLs, so they never change once used.

The routines push their images on branches `claude/cards-…`; [`.github/workflows/merge-image-branches.yml`](.github/workflows/merge-image-branches.yml) merges each one into main with a real merge (never squash or rebase, so the linked commits stay in main's history) and deletes it. A branch that contains anything other than images is left for the owner.

© Polynesia Connect — all rights reserved. Please do not reuse these images without permission.

---

## Version française

Visuels générés automatiquement pour l'agenda de [polynesiaconnect.com](https://www.polynesiaconnect.com/evenements-en-cours).
Ce dépôt est public uniquement pour que le site puisse importer les images par URL ; le site en garde ensuite sa propre copie.

Structure : `AAAA/<slug-de-l-evenement>.jpg` (1200×810). Les images sont référencées par des URL liées à un commit : elles ne changent plus une fois utilisées.

Les routines poussent leurs images sur des branches `claude/cards-…` ; [`.github/workflows/merge-image-branches.yml`](.github/workflows/merge-image-branches.yml) fusionne chacune dans main par une vraie fusion (jamais de squash ni de rebase, pour que les commits liés restent dans l'historique de main) puis la supprime. Une branche qui contient autre chose que des images est laissée au propriétaire.

© Polynesia Connect — tous droits réservés. Merci de ne pas réutiliser ces visuels sans accord.
