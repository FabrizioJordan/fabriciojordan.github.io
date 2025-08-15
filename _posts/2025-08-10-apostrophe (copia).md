---
layout: single
title: "Apostrophe, un editor y visor de markdown open source"
excerpt: "Si necesitas un editor de archivos markdown de código abierto, te presento Apostrophe"
date: 2025-08-10
classes: wide
header:
  teaser: 
  teaser_home_page: false
  icon: 
categories:
  - Linux
  - Open Source
  - TOOLS
tags:
  - Linux
  - Markdown
  - Editores
  - Open Source
  - Office
---  

Te presento Apostrophe, un editor y lector de archivos Markdown bastante elegante.

Apostrophe es un editor de Markdown muy bueno para aquellos que quieran un editor con 0 distracciones y variadas formas de exportar.

Otro agregado muy bueno y que sube el nivel es la ayuda con botones para la escritura estilo Markdown.

![Línea de botones](/assets/images/2025-08-10-apostrophe/2025-08-05(apostrophe-botones).png)

Además contiene revisión de ortografía y vista previa en tiempo real.

### Temas 

Este editor tiene un diseño bastante atractivo, con los temas oscuro, claro y con sepia.

Apostrophe en modo oscuro:

![Apostrophe Modo Oscuro](/assets/images/2025-08-10-apostrophe/2025-08-05(apostrophe-dark).png)

Apostrophe en modo claro:

![Apostrophe Modo Oscuro](/assets/images/2025-08-10-apostrophe/2025-08-05(apostrophe-light).png)

### Vista previa

Apostrophe tiene varias opciones para vistas previas.

Tiene dos formas de verlo en anchura compartida.

La siguiente imágen es con la anchura partida en vertical, pero también existe la anchura partida en horizontal.

![Preview Partido](/assets/images/2025-08-10-apostrophe/2025-08-06(apostrophe-preview-1).png)

Otras opciones que pueden gustar más son en anchura completa o verlo en una ventana aparte.

La siguiente imágen es con la anchura completa.

![Preview Completo](/assets/images/2025-08-10-apostrophe/2025-08-06(apostrophe-preview-2).png)

### Formatos para exportar

Todos los posibles formatos para exportar:
- PDF
- Word (.docx)
- Libreoffice (.odt)
- LaTeX
- o diapositivas en HTML

Y algunos formatos más.

## Instalación

Únicamente existe una forma de instalar Apostrophe. 

Y es vía paquete Flatpak.

La web oficial de Flathub:

[Flathub Apostrophe Apps](https://flathub.org/apps/org.gnome.gitlab.somas.Apostrophe)

Si deseas, te dejo el comando para instalarlo aquí mismo:

```
flatpak install flathub org.gnome.gitlab.somas.Apostrophe
```

------

También existen formas no oficiales, pero no es esperable que se mantengan actualizadas estas vías.

Formas no oficiales:

[Fedora](https://src.fedoraproject.org/rpms/apostrophe): con el comando `sudo dnf install apostrophe`

Otra posibilidad es directamente _buildear_ manualmente la app, pero no es recomendable si no sabes lo que haces.

------

Aunque si lo deseas en su Repositorio Oficial hay una guía de como hacerlo.

Código fuente de Apostrophe en GitLab (con guías de instalación): 

[GitLab Repositorio Oficial Apostrophe](https://gitlab.gnome.org/World/apostrophe)

## Uso

Para ejucutar esta app instalada vía Flatpak es con el comando:

```
flatpak run org.gnome.gitlab.somas.Apostrophe
```


## Consideraciones y resumen

La app está completamente en español, y contiene muchos otros idiomas ya traducidos.

Apostrophe contiene hasta el momento 3 temas, Sepia, Modo Oscuro y Modo Claro.

Para ver más fotos sobre Apostrophe en la web de Gnome Apps:

[Apostrophe GNOME Apps](https://apps.gnome.org/es/Apostrophe/)

------

Apostrophe tiene bastantes atajos de teclado para mejorar la productividad del usuario.

Grupo de atajos 1:

![Vista Shortcuts 1](/assets/images/2025-08-10-apostrophe/2025-08-06(apostrophe-shortcuts-1).png)

Grupo de atajos 2:

![Vista Shortcut 2](/assets/images/2025-08-10-apostrophe/2025-08-06(apostrophe-shortcuts-2).png)

## Otras opciones a Apostrophe

Existen diversas opciones para ver o editar ficheros Markdown.

### Frogmouth:

[Frogmouth](https://github.com/Textualize/frogmouth) es un visor y buscador de Markdown en la terminal. 
No lo recomiendo por las formas de instalación (pipx, pip y brew).

![Vista Frogmouth](/assets/images/2025-08-10-apostrophe/2025-08-06(apostrophe-frogmouth).png)

<hr>

### Typora:

[Typora](https://typora.io/) es un editor simple muy recomendable.

Es un editor y visor de archivos markdown mucho más recomendable que cualquier otro, pero sobre todo por su uso mínimo de memoria RAM.

![Vista Typora](/assets/images/2025-08-10-apostrophe/2025-08-06(apostrophe-typora).png)

<hr>

### Remarkable

[Remarkable](https://remarkableapp.github.io/) es un editor estilo vieja escuela muy horrible pero también muy completo.

![Vista Typora](/assets/images/2025-08-10-apostrophe/2025-08-05(apostrophe-remarkable).png)




