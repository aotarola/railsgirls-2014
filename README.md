railsgirls-2014
===============

A continuación les presento mi lighting talk para Rails Girls en Santiago de Chile 2014.

Pequeño paso para obtener rails corriendo en nuestra máquina (Mac)

###Paso 0

En primer lugar necesitaremos instalar un manejador de versiones de ruby (rvm, rbenv), en este caso utilizaremos [rvm][1]

Comenzamos la instalación de rvm:

```bash
$ curl -sSL https://get.rvm.io | bash -s stable --ruby
```

Una vez instalado rbenv podemos habilitar el auto-completado de versiones de ruby (esto es opcional)

```bash
$ echo 'eval "$(rbenv init -)"' >> ~/bash_profile
```

###Paso 1

Finalmente instalamos rails

```bash
$ gem install rails
```
Listo, ahora tienes rails en tu entorno listo para comenzar a hacer aplicaciones, ganar mucho dinero y comprar un par de aviones :)

**Peace out!**

[1]: http://rvm.io/
