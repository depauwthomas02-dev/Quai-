# Quai

Horaires des trains SNCB / NMBS dans une interface « Liquid Glass » : itinéraires, départs en gare, suivi du train sur la carte et composition du matériel roulant.

Les données en temps réel viennent de l'API publique [iRail](https://docs.irail.be/). Si iRail ne répond pas, l'app passe en mode démo avec des horaires simulés (pastille « Démo » en haut à droite).

## Utilisation

Tout tient dans `index.html`, sans dépendance ni étape de build.

- **En ligne :** activer GitHub Pages (Settings → Pages → Deploy from a branch → `main` / root).
- **Sur iPhone :** ouvrir l'adresse dans Safari → Partager → « Sur l'écran d'accueil ». L'app s'ouvre alors en plein écran.
- **En local :** ouvrir `index.html` dans un navigateur, ou `python3 -m http.server`.

## Fonctions

- Itinéraire entre deux gares, en partant à ou en arrivant avant une heure donnée
- Tableau des départs d'une gare, avec voie et changement de voie
- Détail d'un train : arrêts, retards, position actuelle, composition (M7, AM08 Desiro, I11…)
- Carte schématique du réseau belge, déplaçable et zoomable
- Trajets favoris et gares récentes, enregistrés sur l'appareil
