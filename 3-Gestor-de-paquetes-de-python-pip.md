**Qué es pip?**

pip es un sistema de gestión de paquetes utilizado para instalar y administrar paquetes de software escritos en Python.

**Como instalar?** 

*Instalar pip en Ubuntu ó Debian*

`sudo apt-get install python-pip `


*¿Instalar pip en Fedora?*

`sudo yum install python-pip `

*¿Instalar pip en Archlinux*

`sudo pacman -S python-pip`


***Principales comandos.***

 
*  ***Instalar***

Permite instalar y desinstalar paquetes de software de Python.

`pip install {nombre}`

*  ***Remover***

`pip uninstall {nombre}`

*  ***Search***

Para buscar un paquete en el repositorio. puede hacer algo relacionado para buscarlo.

pip nombre

*  ***Freeze***

Freeze funciona para consultar los paquetes instalados. Así permitiendo gestionar los paquetes instalados y sus números de versiones. Permitiendonos replicar en otro entorno o sistema con los mismos requerimientos.

`sudo pip freeze`

Para obtener los requerimientos instalados.

`pip freeze -r requirements.txt`

Para instalar los requerimientos.

`pip install -r requirements.txt`




