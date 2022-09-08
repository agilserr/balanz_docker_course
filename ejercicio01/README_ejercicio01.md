# Comandos usados
docker run -it --rm -d -p 8080:80 --name ejercicio01 nginx
docker run -it --rm -d -p 8080:80 --name ejercicio01 -v ~/site-content:/usr/share/nginx/html nginx
