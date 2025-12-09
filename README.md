# Final de Ingenieria de Software

## Clonar el repositorio
git clone https://github.com/Nicodici/final-IngDeSoftware-NicolasDiCiuccio.git
cd final-IngDeSoftware-NicolasDiCiuccio

## Construir la imagen Docker
docker build -t final-ingenieria .


## Ejecutar el contenedor
docker run -d -p 8080:80 --name final-ingenieria-web final-ingenieria

## Abrir en el navegador
http://localhost:8080