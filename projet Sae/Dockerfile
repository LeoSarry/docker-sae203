# Utiliser l'image http# Utiliser l'image httpd officielle commd officielle comme image parent
FROM httpd

# Copier le répertoire html du répertoire courant vers le répertoire de l'image /usr/.../htdocs
COPY ./index.html /usr/local/apache2/htdocs/
COPY ./css/styleIndex.css /usr/local/apache2/htdocs/
COPY ./images/img.jpg /usr/local/apache2/htdocs/
COPY ./images/logoUniv.gif /usr/local/apache2/htdocs/
COPY ./videos/video.mp4 /usr/local/apache2/htdocs/

# Exécuter la commande echo sur le conteneur 
# (il peut s'agir de n'importe quelle autre commande)
RUN echo index.html


# Rendre le port 80 accessible au monde en dehors de ce conteneur
EXPOSE 80       