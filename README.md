# docker-stirling-pdf
docker-compose Stirling PDF | PDF Manipulation Tool


### OCR
Descargar idiomas desde: https://github.com/Stirling-Tools/Stirling-PDF/blob/main/HowToUseOCR.md#language-packs

Copiarlos al contenedor en la ruta /usr/share/tessdata

  docker cp spa.traineddata stirling-pdf:/usr/share/tessdata/

Acceso al contenedor y ls directorio

docker exec -ti stirling-pdf sh

ls -l /usr/share/tessdata


### Repositorio original
https://github.com/Stirling-Tools/Stirling-PDF/tree/main
