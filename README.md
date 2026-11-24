# Pour Flore ♡

Une expérience d’anniversaire douce et interactive, réalisée en HTML, CSS et JavaScript natifs. Aucun outil de compilation, dépendance, compte ou backend n’est nécessaire : ouvrez `index.html` dans un navigateur ou publiez le dossier sur un hébergeur de site statique.

Adresse prévue après activation de GitHub Pages : [https://lynx-dot489.github.io/flore-birthday/](https://lynx-dot489.github.io/flore-birthday/)

## Personnalisation

- **Lettre et messages :** modifiez directement les textes dans `index.html`. Le texte de la lettre se trouve dans la section `id="lettre"` ; les dix raisons dans `id="raisons"` ; la surprise dans `id="secret"` ; et le message final dans `id="final"`.
- **Notre univers :** modifiez les quatre pages de `storyPages` et les messages des boutons `.universe-star` dans `index.html`. Les secrets de chaque page se trouvent dans la propriété `secret` correspondante.
- **Musique :** placez un fichier audio (par exemple `musique.mp3`) à côté de `index.html`, puis ajoutez `src="musique.mp3"` à l’élément `<audio id="birthday-audio">`. La musique ne démarre qu’après le clic sur le bouton Musique.

L’expérience s’adapte aux petits écrans et respecte le réglage de réduction des animations du navigateur.
