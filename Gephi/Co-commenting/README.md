# Réseaux de Co-Commentaire YouTube

Ce dossier contient plusieurs réseaux de vidéos YouTube créés à partir du concept de co-commentaire.

## Description des données
- **Réseaux de co-commentaire :**
  - Les liens entre vidéos sont établis lorsque des utilisateurs commentent sur plusieurs vidéos.
  - Plus il y a d'utilisateurs co-commentant entre deux vidéos, plus le lien entre ces vidéos est fort.
  - Jusqu'à 1000 commentaires de premier niveau (classés par pertinence) sont pris en compte.
  - Les commentaires du propriétaire de la chaîne **ne sont pas pris en compte** pour établir les connexions.

- **Sélection des vidéos :**
  - Les vidéos sont sélectionnées soit par recherche via une requête, soit en fournissant une liste d'identifiants de vidéos.

## Contenu
- **Fichiers `.gdf` :**
  - Chaque fichier représente un réseau de co-commentaire spécifique.
  - Les noms des fichiers reflètent souvent la requête ou la liste d'ID utilisée pour générer le réseau.
- **Fichier `text query.txt` :**
  - Contient les requêtes de recherche utilisées pour sélectionner les vidéos dans chaque réseau.
  - Permet de comprendre le contexte de l'extraction.

## Outil utilisé
- [YouTube Data Tool](https://ytdt.digitalmethods.net/mod_videos_comments_net.php) : Module "Videos Co-Commenting Network".

## Comment utiliser
1. Importez les fichiers `.gdf` dans Gephi pour visualiser et analyser les réseaux de vidéos.
2. Consultez le fichier `text query.txt` pour connaître les requêtes de recherche ou les ID utilisés comme base pour construire les réseaux.

## Applications
Ces données peuvent être utilisées pour :
- Identifier des groupes de vidéos fortement connectées par co-commentaire.
- Étudier les communautés et les interactions entre les vidéos YouTube.
- Analyser les habitudes d'engagement des utilisateurs sur une thématique ou un sujet spécifique.

---

_**Note :** Les données extraites dépendent de la requête de recherche ou des ID fournis, ainsi que des commentaires disponibles au moment de l'extraction (Dec 2024)._
