echo "# SRI" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/CarlosAlvarezDiaz/SRI.git
git push -u origin main

1 Descarga la imagen 'httpd' y comprueba que está en tu equipo.
   
      $ docker pull httpd
        Using default tag: latest
        latest: Pulling from library/httpd
        Digest: sha256:5123fb6e039b83a4319b668b4fe1ee04c4fbd7c4c8d1d6ef843e8a943a9aed3f
        Status: Image is up to date for httpd:latest
        docker.io/library/httpd:latest
  
3. Crea un contenedor sin ponerle nombre. ¿está arrancado? Obtén el nombre
4. Crea un contenedor con el nombre 'ubu1'. ¿Como puedes acceder a él?
5. Comprueba que ip tiene y si puedes hacer un ping a google.com
6. Crea un contenedor con el nombre 'ubu2'. ¿Puedes hacer ping entre los contenedores?
7. Sal del terminal, ¿que ocurrió con el contenedor?
8. ¿Cuanta memoria en el disco duro ocupaste? ¿Hay alguna herramienta de docker para calcularlo?
9. ¿Cuanta RAM ocupan los contenedores? Crea cuantos contenedores necesites para calcularlo.
