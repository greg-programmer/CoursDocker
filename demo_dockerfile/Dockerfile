# --- Image Source
FROM ubuntu:latest

# -- Information sur l'image
LABEL version "1.0.0" maintainer="Nom prenom <prenom@nom.com>"

# Commande effectuées au demarrage de la création de l'image
RUN apt update && apt install git -y

# se positionner à l'interieur du dossier /root
WORKDIR /root

# Copier le contenu du dossier ou se trouve le dockerfile à l'interieur de la cible
COPY . .

# Exposer un port 
EXPOSE 8080

CMD ["/bin/bash"]