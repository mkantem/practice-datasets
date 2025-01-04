# Réseaux d'Interactions dans les commentaires YouTube

Ce dossier contient des réseaux basés sur les interactions dans les sections de commentaires YouTube.

## Description des données
- **Réseaux d'interactions dans les commentaires :**
  - Les données sont issues des commentaires d'une vidéo spécifique.
  - Les interactions sont mappées entre les utilisateurs basées sur leurs commentaires et leurs réponses.
  - Les commentaires sont récupérés via l'API `commentThreads/list`.

- **Données supplémentaires :**
  - Informations de base et statistiques sur chaque vidéo.
  - Liste de tous les commentaires récupérés (y compris les réponses).
  - Comptes des auteurs de commentaires et leur nombre de contributions.

## Contenu
- **Fichiers `.gdf` :**
  - Chaque fichier représente un réseau d'interactions entre utilisateurs dans les commentaires d'une vidéo.
  - Peut être importé dans Gephi pour visualisation et analyse.
- **Fichier csv avec statistiques vidéo :**
  - Fournit des informations de base sur la vidéo, comme le nombre de vues, de likes, et de commentaires.
- **Fichier csv des commentaires :**
  - Contient tous les commentaires récupérés, incluant :
    - Les commentaires de premier niveau.
    - Les réponses aux commentaires.
  - Inclut des métadonnées comme l’auteur, la date, et le contenu du commentaire.
- **Fichier csv des auteurs de commentaires :**
  - Liste tous les auteurs ayant contribué à la section commentaires.
  - Indique leur nombre total de commentaires.
- **Fichier `link.txt` :**
  - Contient :
    - La description de chaque vidéo utilisée.
    - Le lien vers la vidéo.
    - Le nombre total de commentaires récupérés (total et premier niveau (top level comment)).
## Outil utilisé
- [YouTube Data Tool](https://ytdt.digitalmethods.net/mod_video_comments.php) : Module "Video Comments".

## Comment utiliser
1. **Fichiers réseau :**
   - Importez les fichiers `.gdf` dans Gephi pour visualiser et analyser les interactions entre les utilisateurs dans les sections de commentaires.
2. **Fichier `link.txt` :**
   - Consultez ce fichier pour obtenir des informations sur la vidéo utilisée comme point de départ, notamment son lien et les statistiques des commentaires.
3. **Autres fichiers tabulaires :**
   - Analysez les fichiers CSV pour explorer les commentaires individuels, les auteurs, et les statistiques associées.

## Applications
Ces données peuvent être utilisées pour :
- Étudier les dynamiques d'interaction entre utilisateurs dans une section de commentaires.
- Identifier les utilisateurs les plus actifs et leurs contributions.
- Analyser les thèmes et sujets prédominants dans les discussions.

---

_**Note :** Les données extraites dépendent de la vidéo sélectionnée et des commentaires disponibles au moment de l'extraction (Dec 2024)._
