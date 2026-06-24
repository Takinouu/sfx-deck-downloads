# SFX Deck

**Gestionnaire personnel de bruitages et sons pour le montage vidéo.**

Organisez, recherchez, écoutez et glissez-déposez vos fichiers audio directement vers Premiere Pro, DaVinci Resolve, After Effects et toute application compatible.

100% hors ligne · Aucun compte requis · Non destructif · Gratuit

---

## ⬇️ Téléchargement

> 🔗 **Lien permanent — toujours la dernière version :**
> **<https://github.com/Takinouu/sfx-deck-downloads/releases/latest>**
> Mettez **ce** lien en favori et partagez-le : il redirige automatiquement vers la version la plus récente. Évitez de copier un lien contenant un numéro de version (`…-v1.0.x.exe`), il deviendra obsolète.

### Dernière version : **1.0.3**

#### macOS (Apple Silicon — M1 / M2 / M3)

| Format | Lien | Usage |
|---|---|---|
| **DMG** (recommandé) | [⬇ SFX-Deck-macOS-v1.0.3.dmg](https://github.com/Takinouu/sfx-deck-downloads/releases/download/v1.0.3/SFX-Deck-macOS-v1.0.3.dmg) | Glisser dans Applications · 131 Mo |
| ZIP | [⬇ SFX-Deck-macOS-v1.0.3.zip](https://github.com/Takinouu/sfx-deck-downloads/releases/download/v1.0.3/SFX-Deck-macOS-v1.0.3.zip) | Archive directe · 125 Mo |

> Testé sur macOS 13 Ventura, 14 Sonoma et 15 Sequoia · Apple Silicon uniquement (arm64)

#### Windows (x64 — Windows 10 / 11)

| Format | Lien | Usage |
|---|---|---|
| **Installeur** (recommandé) | [⬇ SFX-Deck-Windows-Setup-v1.0.3.exe](https://github.com/Takinouu/sfx-deck-downloads/releases/download/v1.0.3/SFX-Deck-Windows-Setup-v1.0.3.exe) | Installation standard · 118 Mo |
| Portable | [⬇ SFX-Deck-Windows-Portable-v1.0.3.exe](https://github.com/Takinouu/sfx-deck-downloads/releases/download/v1.0.3/SFX-Deck-Windows-Portable-v1.0.3.exe) | Sans installation · 117 Mo |

> Testé sur Windows 10 et 11 (64-bit)

📋 [Voir toutes les versions](https://github.com/Takinouu/sfx-deck-downloads/releases)

---

## 🆕 Nouveautés de la 1.0.3

- **Mise à jour intégrée** — l'app détecte les nouvelles versions et se met à jour depuis l'interface (macOS : mise à jour signée et vérifiée ; Windows : installeur automatique). Plus besoin de revenir télécharger ici à chaque version.
- **Paramètres en fenêtre** — les réglages s'ouvrent désormais dans une fenêtre dédiée (croix de fermeture, Échap, clic à l'extérieur).
- Corrections de robustesse et de sécurité.

> Déjà sur une version précédente ? Inutile de re-télécharger : ouvrez l'app, la mise à jour vous sera proposée automatiquement.

---

## Installation macOS

L'application n'est pas encore signée avec un certificat Apple. macOS peut afficher un avertissement à la première ouverture.

### Via le DMG

1. Ouvrir le fichier `.dmg`
2. Glisser **SFX Deck** dans le dossier **Applications**
3. Éjecter le DMG

### Ouvrir l'application (première fois)

macOS bloque les apps non signées par défaut. Deux méthodes pour l'autoriser :

**Méthode 1 — Terminal (recommandée)**
```bash
xattr -cr "/Applications/SFX Deck.app"
```
Puis double-cliquer sur l'app normalement.

**Méthode 2 — Sans Terminal**
1. Faire un **clic droit** sur `SFX Deck.app`
2. Choisir **Ouvrir**
3. Cliquer **Ouvrir** dans la boîte de dialogue

Cette autorisation n'est nécessaire qu'une seule fois.

---

## Installation Windows

L'application n'est pas encore signée avec un certificat Windows. SmartScreen peut afficher un avertissement.

### Via l'installeur (.exe)

1. Double-cliquer sur `SFX-Deck-Windows-Setup-v1.0.3.exe`
2. Si Windows SmartScreen s'affiche :
   - Cliquer **"Informations complémentaires"**
   - Cliquer **"Exécuter quand même"**
3. L'installation se fait en un clic
4. SFX Deck apparaît dans le menu Démarrer

### Via la version portable

1. Double-cliquer sur `SFX-Deck-Windows-Portable-v1.0.3.exe`
2. Même procédure SmartScreen si nécessaire
3. L'app se lance directement, sans installation

---

## Fonctionnalités

- **Bibliothèque locale** — scan récursif de vos dossiers audio (WAV, MP3, AIFF, FLAC, M4A, AAC, OGG…)
- **Recherche instantanée** — par nom, chemin, dossier source
- **Filtres combinables** — favoris, format, collection, dossier
- **Lecture intégrée** — autoplay, contrôle du volume, raccourci Espace
- **Waveform stéréo** — générée en temps réel, mise en cache pour un affichage instantané
- **Sélection d'extrait** — cliquer-glisser dans la waveform pour sélectionner une section
- **Drag & drop** — glisser le fichier original ou un extrait WAV vers Premiere Pro, DaVinci Resolve…
- **Copie vers projet** — copier les sons dans un sous-dossier `SFX/` de votre projet
- **Collections et favoris** — organisez vos sons préférés
- **Arborescence** — naviguez par dossiers et sous-dossiers
- **Mise à jour intégrée** — nouvelles versions détectées et installées depuis l'app
- **100% hors ligne** — aucune connexion internet, aucun compte, aucun tracking

---

## Données locales

Toutes les données restent sur votre machine, jamais en ligne.

### macOS
| Données | Emplacement |
|---|---|
| Base de données | `~/Library/Application Support/sfxdeck/sfxdeck.db` |
| Cache waveform | `~/Library/Application Support/sfxdeck/waveform-cache/` |
| Fichiers temporaires | `/tmp/sfxdeck-extracts/` |

### Windows
| Données | Emplacement |
|---|---|
| Base de données | `%APPDATA%\sfxdeck\sfxdeck.db` |
| Cache waveform | `%APPDATA%\sfxdeck\waveform-cache\` |
| Fichiers temporaires | `%TEMP%\sfxdeck-extracts\` |

---

## Non destructif — garanties

SFX Deck ne modifie, renomme, déplace ni supprime jamais vos fichiers audio.

| Action | Ce qui se passe réellement |
|---|---|
| Drag & drop | Envoi du chemin du fichier — l'original reste en place |
| Extrait temporaire | Fichier WAV créé dans le dossier temp — supprimé automatiquement |
| Copie vers projet | Copie dans `SFX/` — l'original reste en place |
| Favoris / collections | Stockés dans SQLite uniquement — jamais dans les fichiers |

---

## Formats audio supportés

WAV · MP3 · AIFF · FLAC · M4A · AAC · OGG · OPUS · WMA
(extensions en majuscules ou minuscules)

---

## FAQ

**L'app est-elle gratuite ?**
Oui, SFX Deck est gratuit.

**Comment mettre à jour ?**
Depuis la 1.0.2, l'app vérifie les nouvelles versions au démarrage et propose la mise à jour directement dans l'interface. Vous n'avez plus besoin de revenir télécharger manuellement.

**Mon Mac Intel est-il supporté ?**
Le build actuel est compilé pour Apple Silicon (arm64). Intel sera ajouté dans une prochaine version.

**Puis-je l'utiliser avec Premiere Pro sur Windows ?**
Oui. Glissez vos sons directement depuis SFX Deck vers le panneau Projet de Premiere Pro.

**Où sont stockées mes données ?**
Uniquement sur votre machine (voir tableau "Données locales" ci-dessus). Aucune donnée n'est envoyée en ligne.

**L'app modifie-t-elle mes fichiers audio ?**
Non. SFX Deck est 100% non destructif.

**Pourquoi macOS / Windows affiche un avertissement ?**
L'app n'est pas encore signée avec un certificat payant. Voir les instructions d'installation ci-dessus pour l'autoriser.

---

## Signalement de problèmes

[Ouvrir une issue](https://github.com/Takinouu/sfx-deck-downloads/issues)

---

## Historique des versions

📋 [Toutes les releases sur GitHub](https://github.com/Takinouu/sfx-deck-downloads/releases)
