# Utiliser l'image http# Utiliser l'image httpd officielle commd officielle comme image parent
FROM debian:latest

RUN  apt-get update && \
    apt-get -y install  \
    nginx 

# Copier le répertoire html du répertoire courant vers le répertoire de l'image /usr/.../htdocs
COPY . /usr/share/nginx/html
COPY ./index.html /usr/share/nginx/html/index.html


# Exécuter la commande echo sur le conteneur 
# (il peut s'agir de n'importe quelle autre commande)
RUN echo index.html


# Rendre le port 80 accessible au monde en dehors de ce conteneur
EXPOSE 80  

CMD ["nginx","daemon off;"]
