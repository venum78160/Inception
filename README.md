# Inception


Installer Docker sur votre machine.
Créer un répertoire pour votre projet.
Créer un fichier Dockerfile pour chaque conteneur que vous devez créer. Un Dockerfile est un fichier texte qui décrit les étapes nécessaires pour créer une image Docker.
Construire les images Docker à partir de ces fichiers en utilisant la commande docker build.
Créer un réseau Docker pour que les conteneurs puissent communiquer entre eux.
Créer les conteneurs Docker en utilisant les images que vous avez construites.
Configurer les volumes pour stocker les données de votre base de données et les fichiers de votre site WordPress.
Configurer les conteneurs pour utiliser les volumes et le réseau que vous avez créés.
Lancer les conteneurs en utilisant la commande docker run.
Accéder à votre site WordPress en utilisant l'adresse IP du conteneur NGINX.

## Env:
- **DOMAIN_NAME** : Cette variable stocke le nom de domaine pour le projet. Dans cet exemple, elle est définie en fonction de votre nom d'utilisateur pour l'infrastructure de l'école 42 (42.fr).

- **CERT_** : Cette variable stocke le chemin du certificat SSL pour le projet. Le certificat SSL permet d'établir une connexion sécurisée entre le serveur et le client.

- **KEY_** : Cette variable stocke le chemin de la clé privée pour le certificat SSL. La clé privée permet de déchiffrer les données cryptées échangées entre le serveur et le client.

- **DB_NAME** : Cette variable stocke le nom de la base de données utilisée par WordPress.

- **DB_ROOT** : Cette variable stocke le mot de passe pour le compte root de la base de données.

- **DB_USER** : Cette variable stocke le nom d'utilisateur pour la base de données.

- **DB_PASS** : Cette variable stocke le mot de passe pour l'utilisateur de la base de données.

## Glossaire:
- **Docker** : Docker est une plateforme de virtualisation légère qui permet d'exécuter des applications dans des conteneurs isolés. Les conteneurs permettent d'encapsuler une application avec toutes ses dépendances dans un environnement isolé et portable.

- **Docker-compose** : Docker-compose est un outil qui permet de définir et de lancer des applications multi-conteneurs. Il permet de définir les services, les réseaux et les volumes de l'application dans un fichier YAML et de les lancer avec une seule commande.

- **Alpine Linux** : Alpine Linux est une distribution Linux minimaliste conçue pour être utilisée dans des conteneurs Docker. Elle est très légère et rapide, ce qui la rend idéale pour les applications qui nécessitent des temps de démarrage rapides.

- **Debian Buster** : Debian Buster est la dernière version stable de la distribution Linux Debian. Elle est utilisée dans de nombreuses applications et est connue pour sa stabilité et sa fiabilité.

- **NGINX** : NGINX est un serveur web open-source utilisé pour la gestion de serveurs web et de proxy inverse. Il est connu pour sa légèreté, sa rapidité et sa capacité à gérer de grandes quantités de trafic.

- **TLSv1.2** et **TLSv1.3** : TLS (Transport Layer Security) est un protocole de sécurité utilisé pour protéger les communications sur Internet. TLSv1.2 et TLSv1.3 sont les versions les plus récentes de ce protocole.

- **WordPress** : WordPress est un système de gestion de contenu open-source largement utilisé pour la création de sites web. Il est écrit en PHP et utilise une base de données pour stocker les données du site.

- **php-fpm** : php-fpm (FastCGI Process Manager) est un gestionnaire de processus FastCGI pour PHP. Il permet d'améliorer les performances des applications PHP en les exécutant dans des processus séparés.

- **MariaDB** : MariaDB est un système de gestion de base de données open-source qui est utilisé comme alternative à MySQL.

- **Volume** : Un volume Docker est un espace de stockage qui peut être partagé entre les conteneurs et la machine hôte. Les volumes sont utilisés pour stocker des données persistantes et pour faciliter la communication entre les conteneurs.

- **Docker-network** : Un réseau Docker est un réseau isolé qui permet aux conteneurs de communiquer entre eux. Les réseaux sont utilisés pour séparer les différents services de l'application et pour assurer leur isolation.

- **PID 1** : Le PID 1 est le processus qui est exécuté en premier dans un conteneur Docker. Il est responsable du démarrage et de la gestion des autres processus dans le conteneur.

- **.env** : Un fichier .env est un fichier qui contient des variables d'environnement. Les variables d'environnement sont utilisées pour stocker des informations sensibles telles que des noms d'utilisateur et des mots de passe.
