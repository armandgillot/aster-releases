# Aster

Lecteur IPTV indépendant pour Android et Fire TV, avec interface en français.

[Télécharger la dernière version](https://github.com/armandgillot/aster-releases/releases/latest)

Version actuelle : **0.8.28** — [Télécharger l’APK](https://github.com/armandgillot/aster-releases/releases/download/v0.8.28/aster-0.8.28.apk).

- Vérifications automatiques de la licence et des mises à jour à chaque ouverture ou retour dans l’application.
- Moteur de lecture Media3 1.11.1, avec des améliorations de gestion des canaux et des buffers audio.

- Sources Xtream activables ou désactivables individuellement sans supprimer les identifiants ni le catalogue.
- Lecteur : sauts progressifs en maintenant la timeline et accélération des appuis répétés sur ±10 secondes. Logo des chaînes TV en bas à droite.
- Favoris : filtre « Non vu » et suppression des favoris vus avec confirmation.
- Apparition en fondu des images chargées.

- Recherche sur les plateformes : texte indicatif réduit et affiché sur une seule ligne, avec points de suspension si nécessaire.

- Lecteur : déplacements de 5 secondes sur la timeline et cumul des clics rapprochés sur ±10 secondes.
- Analyse des versions plus tolérante aux serveurs lents et aux fichiers sans durée annoncée, avec possibilité de réessayer.
- Favoris : carrousels Films, Séries et Chaînes, filtre « Vu » et suppression par sélection.
- Placeholders acteurs, header de saga fixe et commandes du lecteur simplifiées.

- TV : plantage corrigé lors des changements de filtres, notamment « Séries → Tout » et « Populaires → Nouveautés ».
- Filtres et focus conservés pendant le remplacement des résultats ; retours de fiche et de chaîne vérifiés.

- Plateformes : premiers résultats reconnus affichés plus tôt, notamment sur Crunchyroll avec « Nouveautés ».
- Vérifications des titres traduits en parallèle et chargement du filtre précédent suspendu.
- Pages conservées au retour, ordre du catalogue et reconnaissance multilingue préservés.

- Catalogue multilingue : titres traduits et alternatifs officiels reconnus pour les films et les séries.
- Recherche des sources sans identifiant TMDB et recherche dans les plateformes améliorées.
- Anciens rejets réexaminés automatiquement, sans réimporter les sources.
- Dates de synchronisation conservées lors des migrations du catalogue.

- TV : filtres et recherche restent visibles au défilement ; Retour retrouve les filtres sans déplacer les cartes.
- Recherche et boutons alignés sur une hauteur commune de 48 dp.
- Mobile : en-tête défilant et recherche compacte.

- Espace adulte : retiré des séries, zapping haut/bas rétabli sur TV et retour de page stabilisé.
- BRUT X reclassé hors de l’espace adulte ; classification fondée sur les catégories fournisseur.
- Disponibilité des sagas corrigée, avec prise en charge des libellés Star Wars comportant un numéro d’épisode.
- Migration automatique du catalogue existant, sans nouvel import.

- Les films sont aussi retrouvés grâce à l’identifiant TMDb transmis par le fournisseur, même si son titre ou son année varie.
- Les versions des catégories françaises sont privilégiées et le titre est vérifié avant d’associer une source.

- Qualité réellement lue affichée avec les commandes du lecteur.
- Logos centrés sur un fondu sombre dans les cartes horizontales ; titre texte conservé uniquement sous la carte et jaquettes verticales inchangées.
- Logos préchargés, cache partagé et priorité aux images des titres.
- Accueil plus réactif, rubriques conservées pendant l’actualisation et lectures redondantes réduites.
- Historique : date de visionnage et numéro de saison/épisode sous le titre, dans la carte.
- Dernière saison regardée présélectionnée et centrée ; navigation des fiches acteur améliorée.
- Espace adulte : catégories reclassées avec des marqueurs plus précis, sans réimporter les sources.
- Catalogue tolérant aux limites TMDB, zapping plus réactif et mémoire libérée entre les recherches.
- Chaînes de tous les pays de retour dans TV en direct ; sur téléphone, la liste garde sa position au retour d’une fiche.

Les mises à jour de production conservent vos sources, profils, favoris et historique.

Une licence Aster active est nécessaire depuis la version 0.7.1. Demandez votre clé à la personne qui vous a fourni l’application.
Aster ne fournit aucun abonnement ni flux IPTV : chaque utilisateur configure ses propres sources Xtream Codes.

Les versions de production proposent les mises à jour dans **Paramètres › Application → Vérifier les mises à jour**. Le téléchargement est vérifié avant l’installation, puis Android ou Fire OS demande une confirmation.
Les installations de test debug utilisent une autre signature et ne peuvent pas être remplacées directement par ces APK de production.

Ce dépôt contient uniquement les APK de production, leurs manifestes et leurs notes de version. Les sources et les clés de signature ne sont pas publiées.
