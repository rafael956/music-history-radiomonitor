# 🎧 Music History – RadioMonitor

Ce dépôt publie chaque jour la liste des musiques détectées pour la première fois par [RadioMonitor.fr](https://radiomonitor.fr), une plateforme indépendante de suivi des diffusions musicales sur les radios françaises.

Chaque fichier `musiques-YYYY-MM-DD.md` correspond aux titres identifiés automatiquement à la date donnée. Ces musiques ont été détectées pour la première fois par notre système ce jour-là.

## 📂 Structure des fichiers

- `musiques-2025-07-10.md` → Musiques détectées le 10 juillet 2025
- `musiques-2025-07-11.md` → Musiques détectées le 11 juillet 2025
- etc...

Le contenu est au format Markdown, et inclut les informations suivantes pour chaque titre :

- 🎵 **Titre**
- 🎤 **Artiste** (et featurings)
- 💿 **Album**
- ⏱️ **Durée** (en secondes)
- 🧬 **ISRC** (identifiant international de la musique)
- 🖼️ **Pochette**

Les données nous sont communiquées par les APIs de Spotify et de Deezer. RadioMonitor n'est pas responsable en cas de données eronnées, ce qui peut être possible.

## 🛠️ Génération automatique

Ce dépôt est mis à jour automatiquement chaque jour par un script côté serveur.  
S'il n'y a pas de nouveauté détectée un jour donné, un fichier est quand même généré avec une mention explicite.

## 📅 Utilisation

Les fichiers peuvent être :

- consultés en ligne,
- utilisés par des scripts externes pour analyse ou archivage,
- intégrés dans des flux de veille musicale, playlists ou études de tendances.

## 📄 Licence

Ce dépôt est à usage informatif. Les données proviennent de détections automatisées et peuvent comporter des erreurs.  
Les titres, noms d’artistes et pochettes restent la propriété de leurs ayants droit respectifs.

---

✨ Suivez l’évolution de la scène musicale jour après jour avec [RadioMonitor.fr](https://radiomonitor.fr)
