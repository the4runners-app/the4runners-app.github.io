# Audio2Text — site officiel

**Site web : https://the4runners.fr/**  
**Application Android : [Audio2Text sur Google Play](https://play.google.com/store/apps/details?id=com.the4runners.audio2text)**  
**Code source Android et backend : [the4runners-app/Audio2Text](https://github.com/the4runners-app/Audio2Text)**

Ce dépôt contient le **site public d'Audio2Text**, publié via GitHub Pages sous le domaine personnalisé `the4runners.fr` (fichier `CNAME`).

## Pages

- [Accueil](https://the4runners.fr/) — fonctionnalités Whisper et Qwen3, transcription, recherche, exports TXT/SRT, lecteur et sauvegarde
- [Politique de confidentialité](https://the4runners.fr/privacy.html) — données personnelles, conservation, transferts, droits et évolutions prévues
- [Suppression de compte et des données](https://the4runners.fr/delete-account.html) — procédure et catégories de données concernées

## Sauvegardes

- **Sauvegarde personnelle** : fichier exporté dans un emplacement choisi par l'utilisateur, y compris un fournisseur de documents tel que Google Drive lorsqu'il est disponible sur Android ; cette option ne consomme pas de stockage cloud Audio2Text.
- **Sauvegarde cloud Premium** : option facultative **en cours de déploiement** et réservée aux abonnés actifs Starter, Plus ou Pro. Le service prévu conserve l'audio dans un bucket privé européen (Paris) jusqu'à 30 jours, dans la limite de 100 Mio par compte. **Ne pas annoncer la fonctionnalité comme disponible avant configuration et publication Android.**

La sauvegarde d'un fichier d'origine permet de reconstituer une version de lecture locale. La seule transcription texte ne permet pas de restituer fidèlement le son.

## Publication

Le site est statique : HTML et CSS, sans dépendance de build. Les modifications destinées au public sont publiées en fusionnant les changements validés dans `master` (branche GitHub Pages).

Vérifier les pages en mobile et ordinateur, les liens légaux, l'accessibilité, les balises SEO et le rendu sur le domaine personnalisé avant publication. Le dépôt de l'application est distinct de celui du site.

## Informations du dépôt GitHub

Dans la section **About** du dépôt, renseigner :

- **Description** : `Site officiel d'Audio2Text — Transcription audio et vidéo par IA sur Android (Whisper, Qwen3, recherche et export)`
- **Website** : `https://the4runners.fr/`
- **Topics** : `audio2text`, `android`, `speech-to-text`, `whisper`, `qwen3`, `github-pages`

Ces métadonnées de dépôt se modifient dans l'interface GitHub ; ce README contient les liens officiels dans le dépôt même.
