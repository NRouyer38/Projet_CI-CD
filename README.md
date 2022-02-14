# Projet CICD

## Installation
Get main branch
jar --create --manifest=MANIFEST.mf --file menuController.jar src/main/java/controller/menuController.java

On est en retard dans le projet on arrive pas à trouver ou est le picocli.jar pour le java -cp.. avec gitpod.

## add menu
dans l'application menu server :

curl -H "Content-Type: application/json" --data-raw '{"name": "Menu spécial du chef", "dishes": [{"name": "Bananes aux fraises"},{"name": "Bananes flambées"}]}"
