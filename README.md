# Zero_modiGuía de instalación:
1-Descargar el archivo Bisiteboard-1.0.0.zip y package_bisiteboard1_index.json.

2- Guardar en una carpeta facilmente accesible.

3- En arduino, en el menú archivo->preferencias, en el apartaado "Gestor de URLs Adicionales de tarjetas" incluir la URL de la carpeta en la que se encuentran los archivos y llevando al archivo package_bisiteboard1_index.json como destino . EJ.:"file:\\C:\Users\m\Documents\folder\package_bisiteboard1_index.json"

4-Si todo está correcto debería aparecer en el gestor de tarjetas "Bisite development board", en caso contrario comprobar el error, podría ser por haber introducido de forma errónea la URL.

5- Si al instalar la tarjeta da un error y en la ubicacion de los archivos que se encontraran en la carpeta "arduino15/packages/Bisituino" no hay nada, descomprimir el zip e introducir los archivos manualmente, ahora debería permitir programar los microcontroladores sin problema, en la selección de tarjetas aparecerá con el nobre de "Bisite LoRa"
