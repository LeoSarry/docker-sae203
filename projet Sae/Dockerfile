# Utiliser l'image http# Utiliser l'image httpd officielle commd officielle comme image parent
FROM debian:latest

# Copier le répertoire html du répertoire courant vers le répertoire de l'image /usr/.../htdocs
COPY . /usr/local/apache2/htdocs/

RUN  apt-get update && \
    apt-get -y install  \
    apache2 \
    mariadb-server \
    mariadb-client \
    php \
    php-mysql \
    libapache2-mod-php


# Exécuter la commande echo sur le conteneur 
# (il peut s'agir de n'importe quelle autre commande)
RUN echo index.html


# Rendre le port 80 accessible au monde en dehors de ce conteneur
EXPOSE 80       
