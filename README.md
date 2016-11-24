Aplicacion simple para roku.
Este es el codigo utilizado en la video leccion mostrada en fororoku.com.
En esta aplicacion se demuestra como descargar informacion (metadata) del video
desde un servidor web usando el formato json.
Para descargarla desde linux es recomendable tener git instalado.
La descarga se realiza con el siguiente comando:
git clone https://github.com/rokudevfororoku/json.git

Tambien puede descargarse el archivo zip desde el navegador.

Nota para usuarios Windows:
Si se va a construir este aplicacion con el programa 7zip, sera necesario
eliminar los siguientes archivos: Makefile, README.md, manifest.template y
.gitignore antes de comprimir.

Nota para usuarios OS/X y Linux:
Es necesario modificar app.mk con la direccion ip y el password del roku antes de correr
make install.
