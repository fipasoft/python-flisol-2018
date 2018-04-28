
**Instalación del entorno virtual**

**Que es un entorno virtual?**

Básicamente un entorno virtual de Python es un ambiente con la finalidad de aislar dependencias del sistema.

Lo primero es instalar Virtualenvwrapper.

***Ubuntu ó debian.***

`sudo apt-get install virtualenvwrapper`

***Arch Linux.***

`sudo pacman -S python-virtualenvwrapper`

***Fedora.***

`sudo dnf install python-virtualenvwrapper`


Debemos poner en nuestro .bashrc lo siguiente:

```
export WORKON_HOME=$HOME/.virtualenvs
source `which virtualenvwrapper.sh`
```

Ahora debemos cargar nuestra terminal.

```
source ~/.bashrc
mktmpenv
```
