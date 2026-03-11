Módulo-6-SO3-CLI Comandos utilizados en Laboratorio Módulo 6 - Sistemas Operativos III

Este repositorio contiene los comandos prácticos con los cuales se desarrollaron las prácticas de el sexto laboratorio de la asignatura Sistemas Operativos III, impartida por el profesor Adrian Alcantara.

En el mismo se desarrollaron los siguientes temas:

Practica 1: Cifrado
• Descargue la herramiente gpg2, instalarla y configurarla.
• Cree un directorio, y dentro un archivo y cifrelo utilizando gpg2.
• Intente acceder al archivo cifrado.
• uego decifre el archivo y muestre el contenido del mismo.

Practica 2: IP tables - UFW/Firewall-cmd
• Habilite los servicios de http, ftp y ssh en el servidor, muentre ambos servicios funcionando de manera correcta.
• Utilizando IP tables bloquee el trafico del puerto 80, 21 y 22 para bloquear las conexiones hacia ambos servicios muestre los resultados.
• Utilizando IP tables habilite nuevamente el trafico del puerto 80, 21 y 22 para permitir las conexiones hacia ambos servicios.
• Utilizando ufw (si su distro es basada en debian) o firewall-cmd (si su distro esta basada en Red Hat) bloquee el trafico del puerto 80,21 y 22 para bloquear las conexiones hacia ambos servicios.
• Habilite nuevamente el trafico del puerto 80, 21 y 22 para permitir las conexiones hacia ambos servicios.

Practica 3: Instalación de IDS snort
• Descargue e instale el IDS snort.
• luego de instalado, cree las siguientes reglas de deteccion de trafico:

1) Detectar todo el trafico ICMP (Ping) hacia el host.                                                                                                                                                      
2) Detectar todo el trafico hacia el puerto 21/tcp de ese host.                                                                                                                                              
3) Detectar todo el trafico hacia el puerto 22/tcp de ese host.                                                                                                                                               
4) Detectar todo el trafico hacia el puerto 80/tcp de ese host.                                                                                                                                                
• Ejecute el IDS, Realize las pruebas desde su maquina host, y muestre como son detectadas por el IDS.

Este es el enlace a la lista de reproduccion en youtube: ↓
https://www.youtube.com/playlist?list=PLpcZGYtY2vZYQRoQoTPB71w1_1pp35Ewa
