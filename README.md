railsgirls-2014
===============

A continuación les presento mi lighting talk para Rails Girls en Santiago de Chile 2014.

Pequeño paso para obtener rails corriendo en nuestra máquina (Mac)

###Paso -1

En primer lugar necesitaremos instalar un manejador de versiones de ruby (rvm, rbenv), yo recomiendo rbenv, porque me gusta :)

Comenzamos la instalación de [rbenv][1]:

```bash
$ brew install rbenv
```

Una vez instalado rbenv podemos habilitar el auto-completado de versiones de ruby (esto es opcional)

```bash
$ echo 'eval "$(rbenv init -)"' >> ~/bash_profile
```

###Paso 0

Ahora necesitamos instalar ruby, el cual es el lenguaje de programación que rails entiende, y nos permitirá hacerno millonarios :)

```bash
$ rbenv install 1.9.3-p547
```

###Paso 1

Finalmente instalamos rails

```bash
$ gem install rails
```
Listo, ahora tienes rails en tu entorno listo para comenzar a hacer aplicaciones y ganar mucho dinero y comprar un par de aviones :)

**Pace out!**

[1]: https://github.com/sstephenson/rbenv
