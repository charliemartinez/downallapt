
# downallapt

EN: Download all .deb packages from an apt repository.<br>
ES: Descarga todos los ficheros de los repositorios.

## Author / Autor: Charlie Martínez <cmartinez@quirinux.org>
GPLv2 License - https://www.gnu.org/licenses/old-licenses/gpl-2.0.html

ENGLISH:

### How it works:

Download all the files .deb from the repositories
that are enabled in /etc/apt/sources.list and /etc/apt/sources.list.d
and save them in a new /packages folder

### Instructions:

Comment those repositories in /etc/apt/sources.list and /etc/apt/sources.list.d that we do not want to download.

Run as root:

chmod 755 downallapt <br>
mv downallapt /usr/local/bin/downallapt <br>
downallapt <br>

CASTELLANO:

### Cómo funciona:

Descarga todos los ficheros .deb de los repositorios
que estén habilitados en /etc/apt/sources.list y /etc/apt/sources.list.d
y los guarda en una nueva carpeta /packages

### Instrucciones:

Comentar todos los repositorios en /etc/apt/sources.list y /etc/apt/sources.list.d que no queremos que se descargen. 

Ejecutar como root:

chmod 755 downallapt <br>
mv downallapt /usr/local/bin/downallapt <br>
downallapt <br>
