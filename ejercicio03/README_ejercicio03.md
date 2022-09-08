# Comandos usados
docker pull wagoodman/dive # download dive tool
docker pull nicopaez/passwordapi-java:java8-alpine #download image
docker pull nicopaez/passwordapi-java:java8-fabric

**Se ejecuta el comando dive desde la carpeta que tiene dive.exe**
dive nicopaez/passwordapi-java:java8-alpine
dive nicopaez/passwordapi-java:java8-fabric

## Repuesta
La única layer en comun entre las dos imagenes es: FROM 8f52818...
Este comando es el que inicializa la construcción de la imagen
