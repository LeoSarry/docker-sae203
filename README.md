# docker-sae203

-Pour lancer le serveur : il faut vous connecter à docker :
ssh di-docker

-entrez votre mot de passe 
-une fois connecté a docker : clonez notre dépot git hub grace à la commande suivante :
git clone 

-entrez cette commande pour créer l'image :
docker build -t videostream_grp11-img .  

-entreé cette commande pour créer le conteneur :
docker run --name videostream_grp11-docker -d -p 3476:80 videostream_grp11-img

- ouvrez votre navigateur web : tapez di-docker:3476 dans votre bar d'adresse

