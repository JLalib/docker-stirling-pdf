# Stirling PDF
Stirling PDF | PDF Manipulation Tool

Locally hosted web application that allows you to perform various operations on PDF files

![image](https://github.com/user-attachments/assets/e0e64ae2-2574-4599-84c8-bb6c9d4f4cdd)

### OCR
Descargar idiomas desde: https://github.com/Stirling-Tools/Stirling-PDF/blob/main/HowToUseOCR.md#language-packs

Copiarlos al contenedor en la ruta /usr/share/tessdata

  docker cp spa.traineddata stirling-pdf:/usr/share/tessdata/

Acceso al contenedor y ls directorio

docker exec -ti stirling-pdf sh

ls -l /usr/share/tessdata


### Repositorio original
https://github.com/Stirling-Tools/Stirling-PDF/tree/main
