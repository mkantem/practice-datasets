# Réseaux de Chaînes YouTube

Ce dossier contient plusieurs réseaux de chaînes YouTube.

## Description des Données
- **Réseaux multiples :** chaque fichier `.gdf` représente un réseau distinct de chaînes YouTube connectées via les sections "chaînes recommandées" et "abonnements".
- **Sources des données :**
  - Les "chaînes recommandées" sont récupérées via `channels/list#brandingSettings`.
  - Les "abonnements" sont récupérés via `subscriptions/list`.

## Contenu
- **Fichiers `.gdf` :** 
  - Chaque fichier correspond à un réseau de chaînes spécifique.
  - Les noms des fichiers reflètent généralement les chaînes de départ ("seed channels") ou des configurations spécifiques.
- **Fichier `links.txt` :**
  - Contient une liste des chaînes initiales utilisées comme points de départ pour l'extraction.
  - Inclut les paramètres de configuration appliqués lors de l'extraction.

## Outil Utilisé
- [YouTube Data Tool](https://ytdt.digitalmethods.net/mod_channels_net.php) : Module "Channel Network".

## Comment Utiliser
1. Importez les fichiers `.gdf` dans Gephi pour visualiser et analyser chaque réseau de chaînes individuellement.
2. Consultez le fichier `links.txt` pour identifier les chaînes initiales utilisées et mieux comprendre la méthode d'extraction.

## Applications
Ces données peuvent être utilisées pour :
- Explorer les relations entre chaînes dans différents réseaux YouTube.
- Identifier des clusters ou des communautés.
- Analyser les interactions entre chaînes à travers les abonnements et les recommandations.
- Influence
---

_**Note :** Chaque réseau dépend des chaînes de départ et des configurations définies lors de l'extraction._
