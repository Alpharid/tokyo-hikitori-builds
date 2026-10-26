# Tokyo Hikitori : Gokudō Runner — builds

Jeu VR solo : un yakuza tout en blanc fait des livraisons à pied dans les ruelles de Tokyo, en 1996, la nuit, sous la
pluie, et se bat contre les chinpira qui lui barrent la route. Ralenti et time stop.

Ce dépôt ne contient que les **builds** (binaires). Le code du jeu est privé.

## Jouer

1. Il faut un **PC VR** : casque Quest relié par Quest Link, Air Link ou Virtual Desktop, ou un casque SteamVR.
2. Télécharger **[TokyoHikitoriLauncher.exe](https://github.com/Alpharid/tokyo-hikitori-builds/releases/download/launcher/TokyoHikitoriLauncher.exe)**
   une fois et le garder : il télécharge le jeu, le vérifie, le met à jour, et se met à jour lui-même.
3. Windows peut afficher un avertissement SmartScreen (l'exe n'est pas signé) : *Informations complémentaires* >
   *Exécuter quand même*.
4. Choisir **STABLE** (éprouvé) ou **UNSTABLE** (les dernières nouveautés, peut planter), puis *再生 ▶ JOUER*.

Le jeu s'installe dans `%LOCALAPPDATA%\TokyoHikitori\` (plusieurs Go).

## Un problème ?

Envoyer au développeur le journal du jeu :
`%LOCALAPPDATA%\TokyoHikitori\channels\<canal>\<version>\TokyoHikitori\Saved\Logs\TokyoHikitori.log`
(la première ligne « Build: » dit quelle version tourne).
