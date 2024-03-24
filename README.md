# Discord Music and League of Legends Bot

Ce bot Discord offre plusieurs fonctionnalités pour améliorer l'expérience sur vos serveurs Discord. Il permet de jouer de la musique, de diviser les utilisateurs en équipes pour des jeux, d'afficher des informations sur les matchs de League of Legends, et plus encore.

## Fonctionnalités

- **Musique :** Jouez de la musique dans les canaux vocaux à partir de liens YouTube.
- **Division en équipes :** Répartissez automatiquement les membres du canal vocal en deux équipes.
- **Informations sur League of Legends :** Affichez le statut du match actuel des joueurs spécifiés.
- **Interactions Fun :** Répondez à des commandes spécifiques avec des réponses prédéfinies.

## Installation

Pour utiliser ce bot, vous aurez besoin de Python 3.6 ou supérieur et de quelques dépendances.

1. Clonez ce dépôt sur votre machine locale.
2. Installez les dépendances nécessaires en exécutant :

pip install -r requirements.txt


3. Créez un fichier `.env` à la racine de votre projet et ajoutez votre token de bot Discord ainsi que d'autres variables d'environnement nécessaires :

discord_token=VOTRE_TOKEN_ICI


4. Assurez-vous d'avoir ffmpeg installé sur votre machine pour la lecture de musique.

## Utilisation

Pour démarrer le bot, exécutez le script dans votre terminal :

python nom_du_script.py


Utilisez les commandes définies dans le script (par exemple, `!play`, `!pause`, `!join`) dans votre serveur Discord pour interagir avec le bot.

## Contribution

Les contributions à ce projet sont les bienvenues. N'hésitez pas à soumettre des Pull Requests ou à ouvrir des Issues pour toute suggestion ou problème rencontré.

## Licence

Ce projet est distribué sous la Licence MIT. Voir le fichier `LICENSE` pour plus d'informations.

