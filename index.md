# Sae2.03

# Qu'est-ce qu'un conteneur ?

Avant de commencer avec Docker il faut d'abord définir ce qu’est un conteneur. Il s’agit d’un environnement d’exécution léger, et d’une alternative aux méthodes de virtualisation traditionnelles basées sur les machines virtuelles.

L’une des pratiques clés du développement de logiciel moderne est d’isoler les applications déployées sur un même hôte. Ceci permet d’éviter qu’elles interfèrent.

Le conteneur partage le noyau de son système d'exploitation avec d’autres conteneurs. C’est une différence avec une machine virtuelle, utilisant un hyperviseur pour distribuer les ressources hardware.

Cette méthode permet de réduire l’empreinte des applications sur l’infrastructure. Le conteneur regroupe tous les composants système nécessaires à l’exécution du code, sans pour autant peser aussi lourd qu'un OS complet.

De même, un conteneur est plus léger et plus simple qu’une machine virtuelle et peut donc démarrer et s’arrêter plus rapidement. à un hyperviseur, un moteur de conteneur n’a pas besoin d’émuler un système d’exploitation complet. Le conteneur offre donc de meilleures performances qu’un déploiement sur machine virtuelle traditionnelle.

# Qu'est-ce que c’est Docker ?

Docker est une plateforme de conteneurs lancée en 2013. Elle permet de créer facilement des conteneurs et des applications basées sur les conteneurs. C’est une solution open source, sécurisée et économique.

# Choix du groupe
-Nous avons décidé de faire un site de vidéo à la demande pusique c'est ce qui nous parlait le plus à tous. Rien qu'au titre, nous avions déjà des idées pour le créer.  
-Nous avons pris le support nginx car il proposait davantages de difficulté qu'apache, ainsi que mr Jimenez l'avait dit. De plus, il est open source et propose de grande performance ce qui est utile pour un site de video à la demande.   

# Repartition des taches dans le groupe
Léo Sarry : hébergement du github + logique des commandes du docker + dockerfile  
Hugo Legrand : docker + dockerfile  
Driss Lahbib El Bour Fournier : recherche d'informations sur nginx + conception du site en relation avec son projet personnel + commandes docker  
Lucien Le Roux : recherche docker + github




