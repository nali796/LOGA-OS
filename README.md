<div align="center">

# LOGASTAGE

**Toute la scène. Une console.**

Logiciel de régie pour écrans LED, vidéoprojecteurs, projecteurs DMX et lasers.
Windows et Mac.

[**Télécharger la dernière version**](../../releases/latest) · [Toutes les versions](../../releases)

</div>

---

## Présentation

LOGASTAGE pilote tout ton show depuis un seul logiciel : le mur LED, les vidéoprojecteurs, les lumières et les lasers. Ils partagent la même logique de cues, de faders et de pages, et tout suit le tempo de la musique.

Il est conçu pour le live : une interface sombre et lisible en régie, et une télécommande sur téléphone.

## Fonctions

### Vidéo et mapping
- Calques vidéo, image, caméra et générateurs, avec effets et shaders temps réel.
- Changement de source d'un calque à la volée.
- Mapping de murs LED et de sorties vidéo, avec rotation et retournement de chaque sortie.
- **Masques** pour vidéoprojecteur :
  - des effets de contour, et des calques joués uniquement dans un masque ;
  - un redimensionnement proportionnel, une grille de repère et des masques de découpe de sortie.

### Lumière (DMX)
- Sortie **Art-Net** et **sACN**, sans console externe.
- Une large bibliothèque de projecteurs déjà enregistrés, avec leurs différents modes de canaux.
- Un **éditeur de fixtures** pour créer tes propres fiches.
- Un **assistant de patch** : photographie le tableau DMX du manuel, LOGASTAGE lit les canaux et crée la fiche.
- **Looks** : des ambiances lumière à rappeler en un geste.

### Laser
- Une page dédiée aux lasers : formes, textes, tunnels, éventails…
- Les interfaces **ILDA Helios** (USB) et **Ether Dream** (réseau) sont prises en charge.
- Export de fichiers **.ILD**, compatible avec les lecteurs de carte SD.
- Les lasers pilotables en DMX ont leurs profils.

### Musique et tempo
- Détection du BPM au son, bouton TAP ou saisie directe.
- **Horloge MIDI** en entrée.
- **Drops** : le show repère le break, la montée puis le drop, et réagit.

### Contrôle
- **MIDI Learn** sur les boutons, les faders et les paramètres des effets et des calques.
- Chaque appareil MIDI branché apparaît dans la page MIDI et peut être activé ou désactivé, ce qui évite les conflits entre contrôleurs.
- Les faders peuvent être liés aux paramètres des effets ou des calques.
- **Télécommande sur téléphone** : il suffit de scanner un QR code, sans rien installer. La vue 3D de la scène s'affiche en réalité augmentée.

### Projets
- Chaque projet a son dossier, `Documents › LOGASTAGE › Projets`, où sont copiées ses images et vidéos.
- Les shaders, les effets, le mapping MIDI et les fixtures sont enregistrés avec le projet.
- **Partage .loga** : tout le projet (médias, fiches, pages) tient dans un seul fichier.
- **Mode répétition** et enregistrement vidéo du show.
- **Mises à jour** : LOGASTAGE te prévient quand une nouvelle version est disponible.

## Installation

### Windows 10 / 11 (64 bits)
1. Télécharge `LOGASTAGE-Setup-Windows.exe` depuis les [Releases](../../releases/latest).
2. Lance l'installeur.
3. LOGASTAGE s'ajoute à tes programmes, avec un raccourci sur le Bureau.

Si Windows SmartScreen affiche un avertissement, clique sur **Informations complémentaires**, puis sur **Exécuter quand même**.

### Mac
| Ton Mac | Fichier |
|---|---|
| Puce Apple (M1, M2, M3, M4) | `LOGASTAGE-Mac-Apple-Silicon.zip` |
| Processeur Intel | `LOGASTAGE-Mac-Intel.zip` |

1. Décompresse le fichier, puis glisse **LOGASTAGE** dans **Applications**.
2. Au premier lancement, fais un clic droit sur l'app, puis **Ouvrir**.
   - Si macOS bloque toujours l'app, va dans **Réglages Système › Confidentialité et sécurité** et clique sur **Ouvrir quand même**.

## Matériel compatible

| Type | Connexion |
|---|---|
| Projecteurs DMX | Art-Net, sACN (interface ou nœud réseau) |
| Lasers | ILDA via Helios (USB) ou Ether Dream (réseau), DMX, export .ILD |
| Contrôleurs | Tout contrôleur MIDI (pads, platines, surfaces de contrôle) |
| Vidéo | Écrans, murs LED, vidéoprojecteurs (plusieurs sorties) |
| Télécommande | Tout téléphone sur le même réseau Wi-Fi |

Pour que la télécommande se connecte depuis ton téléphone, autorise LOGASTAGE sur le réseau local quand ton ordinateur le demande.

## Crédits

Conçu et créé par **ILAN HANSBERGER**.

© 2026 ILAN HANSBERGER. Tous droits réservés.
