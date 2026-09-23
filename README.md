# BlockBoat — Boat Run 3D

Jeu de courses de bateau voxel en 3D, jouable au clavier et sur téléphone.

## Lancer en local

```bash
npm install
npm run dev
```

Ouvrir l'adresse indiquée par Vite. Pour la production : `npm run build`.

## Déployer sur Vercel

Importer ce dossier comme projet Vite sur Vercel, ou exécuter `vercel --prod` après connexion au compte. Le dossier de sortie est `dist`.

## Jouer

Choisir une des trois pistes, puis « Jouer en solo ». Sur ordinateur : flèches gauche/droite, Q/D ou A/D. Sur téléphone : boutons gauche/droite. Pour le multijoueur, choisir la même piste, créer/rejoindre un code de salon, partager le lien et lancer chaque course. Les autres joueurs apparaissent en direct sur le parcours et leurs temps s'affichent à l'arrivée.

Le multijoueur utilise Trystero, une découverte par relais MQTT et des connexions WebRTC directes entre navigateurs. Il nécessite une connexion internet et peut échouer sur certains réseaux restrictifs. Les salons ne conservent ni compte ni classement permanent. Le meilleur temps solo est enregistré localement dans le navigateur.
