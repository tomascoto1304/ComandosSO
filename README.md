# ComandosSO
Comandos vistos y utilizados en el curso de Sistemas Operativos 

## ipaddr
- Para saber nuestra dirección IP.

## ifconfig
- Este comando nos enseña la información de la red que seleccionemos.

## ping
- Con este comando probamos que nuestra internet esté corriendo.

## sudo apt install
- Este comando es utilizado para instalar aplicaciones en nuestra máquina con permisos de administrador.

## clear
- Como lo dice su numbre, _limpia_ la terminal.

## shutdown
- Con este comando podemos apagar nuestro sistema

## reboot
- Este comando reinicia nuestro sistema

## cat
- Este comando nos permite imprimir un archivo de nuestra elección

## nano
- Con este comando podemos abrir un archivo en la terminal de nuestro sistema

## whoami
- Este comando nos indica cual usuario actual.

## sudo dpkg -i
- Este comando lo utlizamos para instalar paquetes.

`E.j: sudo dpkg -i google-chrome-stable_current_amd64.deb`

## man + _(otro comando)_
- Con este comando se nos desplegará el manual de el comando que digitemos.

## cd 
- Con este comando entramos a los archivos de nuestra máquina.

`Si queremos entrar a descargas utilizamos "cd Do" `

## sudo apt update
- Este comando nos permite buscar actualizaciones, tanto de aplicaciones como de la máquina.

## sudo apt upgrade
- Este comando va de la mano con _sudo apt update_, ya que este se encarga de ejecutar las actualizaciones. 

## uname -a 
- Este comando nos deja imprimir la información del kernel.

## sudo su
- Con este comando entramos en modo root, que es el súper usuario.
- `exit / su root:`estos se utlizan para salir de el modo root.

## chmod 
- Nos ayuda a modificar los permisos de los archivos que queramos.

## pwd 
- Localiza dentro de nuestro sistema en donde está el usuario.

## touch
- Este comando modifica la hora de el último cambio que hayamos realizado en nuestra máquina.

`Nota: si este comando lo usamos en un archivo que no tenemos en nuestro dispositivo, este se crea automaticamente`

## ls -l
- Este comando cambia la vista de del directorio acual en una lista.

## stat
- Con este comando podemos obtener la información completa de un archivo.

## chown
- Este cambia el dueño de un archivo en la máquina que estemos utlizando.

## du -h
- Este comando nos permite obtener el peso de los arcihvos que tengamos.

## file
- Este comando nos da el formato para un archivo específico.

## find + _(nombre de un archivo)_
- Con este comando podemos buscar un archivo en específico en nuestro sistema.

## pdfunite
- Como lo dice su nombre, este comando une PDFs.

## pdfseparate
- A diferencia del anterior, este separa los PDFs.

## mkdir
- Con eate comando podemos crear un directorio.
`rm -R:`Remueve un directorio
`rm -Rf:`Hace lo mismo que el acomando anterior, solo que con este se remueve de manera forzada.

## history
- Este comando nos permite ver los comandos que hemos utilizado en la termninal que estemos usando.

## scp
- Con este comando podemos trasnferir archivos mediante ssh.

## df -h
- Con este comando podemos observar los sistemas de archivos que están en uso.
`-h`: Se usa solo para formato.

## sudo apt cmatrix
- Este comando nos transforma la terminal a una matrix (como la película).

## sudo apt neofetch 
- Este comando nos muestra en la terminal de nuestro sistema características de nuestra computadora como el cpu, gpu, memoria, entre otros.

## mount 
- Este comando nos permite montar un archivo en cualquier dirección que queramos dentro de nuestro sistema.

## wc
- Con esye comando podemos contar la cantidad de lineas
`wc -w:`Este comando cuenta la cantidad de palabras.
`wc -m:`Este cuenta la cantidad de caracteres.

## head
- Con este comando le ordenamos a nuestro sistema imprimir solo las primeras lineas de el archivo que seleccionemos.

## tail
- Este comando es igual al anterior, solo que con este indicamos que imprima las últimas líneas.

## kill 
- Este es un comando que envía una señal de terminación.
`kill -9 -1:`Mata todos los procesos posibles y cierra todo.

## ps -aux
- Con este comando podemos ver todos los procesos que hemos realizado o se han realizado en nuestro sistema.

_## git clone
_- Este comando clona un repositorio de GitHub.

# Comandos de Docker:
Docker es una plataforma creada con el fin de desarrollar, implementar y ejecutar aplicaciones dentro de contenedores.

## docker run
- ESte comando abre una imagen como si fuera un contenedor.
`docker run -ti:`Este comando crea una terminal interactiva.
`docker run --rm:`Como lo indica el rm _(rm = remove)_ remueve un contenedor.

## docker ps
- Este comando muestra los contenedores que hayamos creado.

## docker info
- Este comando enseña la información de nuestro sistema

## docker images
- Este comando nos muestra imagenes.

## docker history
- En el caso de este comando, nos da el historial de la imagen que seleccionemos.

## docker network ls
- Este comando nos permite imprimir una lista de redes disponibles.

## docker network create --driver
- Este comando nos permite crear una nueva red.

## docker find
- Este comando nos muestra los ficheros existentes.

## docker push
- Este comando nos permite subir una imagen a _Docker Hub._

## docker pull 
- Este comando nos permite descargar imagenes desde _Docker Hub._







