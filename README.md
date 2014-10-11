railsgirls-2014
===============

Pequeño paso para obtener rails corriendo en nuestra máquina (Mac).

A continuación les presento mi lighting talk para Rails Girls en Santiago de Chile 2014.

Comenzamos todos los pasos abriendo una consola/terminal en Mac:

###Paso 0

En primer lugar necesitaremos instalar un manejador de versiones de ruby (rvm, rbenv), en este caso utilizaremos [rvm][1]

Comenzamos la instalación de rvm y un intérprete de ruby:

```bash
$ curl -sSL https://get.rvm.io | bash -s stable --ruby
```

Una vez que se haya compilado todo, habilitamos la nueva versión de ruby

```bash
$ source /Users/$USER/.rvm/scripts/rvm
```

###Paso 1

Finalmente instalamos rails

```bash
$ gem install rails
```
Listo, ahora tienes rails en tu entorno listo para comenzar a hacer aplicaciones, ganar mucho dinero y comprar un par de aviones :)

**Peace out!**

[1]: http://rvm.io/
