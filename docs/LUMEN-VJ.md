# Lumen VJ — application web

Application de mixage visuel live, accessible sur GitHub Pages à `/vj.html`.

## Utilisation

- Ouvrir `vj.html` dans un navigateur moderne (Chrome, Firefox ou Edge récent).
- Charger une vidéo ou une image sur les decks A et B ; les clips vidéo bouclent.
- Mélanger les decks avec le crossfader, régler l'opacité et appliquer les effets master ou par deck.
- Caméra live disponible lorsque le site est servi en HTTPS et que l'accès caméra est autorisé.
- Exporter/importer les paramètres du projet en JSON. Les fichiers médias locaux ne sont volontairement pas copiés dans le fichier projet : il faut les recharger après import.

Le rendu est local au navigateur : aucun média n'est téléversé. Il s'agit d'une première version web pour le live visuel ; elle ne remplace pas le moteur Rust/wgpu ni les fonctions matérielles de tracking, OSC et DMX décrites dans les rapports de phases.
