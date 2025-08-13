---
layout: single
title: "Cómo pasar de un script a un comando para la terminal"
excerpt: "¿Querés pasar de solo ejecutar scripts a poder usarlos como comandos en tu terminal?"
date: 2025-08-04
classes: wide
header:
  teaser: 
  teaser_home_page: false
  icon: 
categories:
  - Script
  - Bash
  - Linux
tags:
  - Bash
  - TOOLS
---


![](/assets/images/2025-08-04-script-comando/2025-08-04-(terminal-script-1).png)

¿Querés dejar de usar esas formas de ejecutar tus scripts cómo ahí arriba?

Te dejo una solución muy fácil de usar.

No es recomendable si no querés o no podes usar `sudo`. 


### Advertencias:

Lo primero es siempre saber que hace el script.

   > ⚠️ **Advertencia**: Nunca uses un script de esta forma que haya sido modificado o creado por otra persona que no seas tú 

> ⚠️ **Advertencia**: Tampoco ejecutes ningún script si no sabés exactamente que hace el código de entro

 
 
#### ¿Cómo saber si vale la pena hacer esto?

Hay que saber si vale la pena utilizar este script como comando o simplemente no cambiaría nada.

Es simple. Si un comando es para ser usado rápidamente y se debe de usar una manera rápida entonces merece la pena

------

**Vamos a comenzar**


------

## Primer Paso

Debemos volver el archivo ejecutable.

Para volver a nuestro archivo ejecutable debemos darle a nuestro usuario la posbilidad de ejecutarlo así:

```
chmod +x tu_script.sh
```


## Segundo Paso

Ahora debemos usar `sudo` para copiar nuestro script hasta una dirección dentro de nuestra computadora.

La dirección es `/usr/local/bin/`.

La carpeta `bin` hace referencia a los binarios de Linux.

Esta carpeta es importante, ya que dentro tiene todos nuestros comandos locales para poder ejecutarlos.

```
sudo cp tu_script.sh /usr/local/bin
```


## Pasos Finales

Desde ahora ya podemos utilizar el script desde cualquier terminal que pueda leer nuestros binarios.

Si teníamos iniciada una terminal, para poder usar el comando debemos reiniciarla o cerrarla y volverla a abrir.

Ahora, para poder ejecutar nuestro script sólo debemos hacer lo siguiente:


![](/assets/images/2025-08-04-script-comando/2025-08-04-(terminal-script-2).png)

Para finalizar deberíamos cambiarle el nombre al comando, ya que no se usa ni es necesario el `.sh` al final, ya no vamos a ejecutarlo más.

Para modificar el nombre y quitarle el `.sh` podemos hacerlo así:

```
sudo mv tu_script.sh tu_script
```

-----