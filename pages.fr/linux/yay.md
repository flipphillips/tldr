# yay

> Yet Another Yogurt: Un outil pour Arch Linux pour construire et installer des paquets depuis le Arch User Repository.
> À regarder : `pacman`.

- Recherche interactivement et installe des paquets depuis les dépôts et l'AUR:

`yay {{package_name|search_term}}`

- Synchronise et mets à jour tous les paquets depuis les dépôts et l'AUR:

`yay`

- Synchronise et mets à jour seulement les paquets de l'AUR:

`yay -Sua`

- Installe un nouveu paquet depuis les dépôts et l'AUR:

`yay -S {{package_name}}`

- Recherche dans la base de données de paquets un mot clé depuis les dépôts et l'AUR: 

`yay -Ss {{keyword}}`

- Montre des statistiques sur les paquets installés et la santé du système:

`yay -Ps`