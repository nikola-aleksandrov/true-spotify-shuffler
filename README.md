# 🔀 True Spotify Shuffle

Un vrai shuffle aléatoire pour tes playlists Spotify — parce que le shuffle natif de Spotify n'est pas vraiment aléatoire.

## 🎵 Démo

👉 [Ouvrir l'application](https://nikola-aleksandrov.github.io/true-spotify-shuffle/)

## ✨ Fonctionnalités

- Récupère toutes tes playlists Spotify
- Mélange vraiment aléatoire (algorithme **Fisher-Yates**)
- Lecture directe sur n'importe quel appareil Spotify connecté (PC, mobile, etc.)
- Synchronisation automatique avec l'app Spotify

## ⚙️ Configuration

1. Crée une app sur le [Spotify Developer Dashboard](https://developer.spotify.com/dashboard)
2. Ajoute cette URL dans **Redirect URIs** :
   ```
   https://nikola-aleksandrov.github.io/true-spotify-shuffle/
   ```
3. Ajoute ton email Spotify dans **User Management** (mode développement = max 25 utilisateurs)
4. Copie ton **Client ID** et colle-le dans l'application

## 🔒 Prérequis

- Compte **Spotify Premium** (requis par l'API Spotify pour le contrôle de lecture)
- Navigateur moderne (Chrome, Firefox, Edge...)

## 🛠️ Stack technique

- HTML / CSS / JavaScript vanilla — aucune dépendance
- API Web Spotify (OAuth 2.0 + PKCE)
- Hébergé gratuitement sur GitHub Pages

## ⚠️ Limitations connues

- Maximum 750 titres par file de lecture (limite imposée par l'API Spotify)
- Maximum 25 utilisateurs autorisés (mode Development de l'app Spotify)
- Nécessite un appareil Spotify actif pour contrôler la lecture
