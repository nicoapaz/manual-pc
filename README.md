# Manual de uso · Mi Computadora Gamer

Un manual **interactivo** de mi PC: qué componentes tiene, cómo le instalé un SSD nuevo, cómo lo configuré en la BIOS, cómo lo formateé y cómo migro los datos. Está pensado para recorrerlo capítulo por capítulo, con un checklist al final que guarda el progreso en el navegador.

**Edición actual:** julio 2026 · Documento personal de Nicolás.

## Qué hay adentro

| Capítulo | De qué trata |
|---|---|
| 00 · Portada | Resumen del equipo y de los discos activos |
| 01 · Ficha técnica | Componentes, modelos y precios de referencia (tocás una fila y ves el detalle) |
| 02 · Almacenamiento | Los tres discos: arranque NVMe, SSD SATA y HDD de datos |
| 03 · Instalación del SSD | Montaje físico paso a paso: bahía, cable de datos, cable de alimentación, verificación |
| 04 · Configuración en BIOS | Cómo entrar, revisar que detecte los discos y leer el menú de arranque |
| 05 · Formateo y puesta en marcha | Inicializar el disco y crear el volumen en Windows, en cinco pasos |
| 06 · Migración de datos | Del HDD al SSD: archivos con Robocopy, juegos de Steam, launchers y programas |
| 07 · Estado y pendientes | Checklist interactivo de lo que falta |

## Cómo se ve

Abrilo en: **https://nicoapaz.github.io/manual-pc/** *(se activa con GitHub Pages, ver abajo)*.

También funciona descargando `index.html` y abriéndolo con doble clic. Necesita internet solo para cargar React; las tipografías van incluidas en el archivo.

Navegación: el índice o las flechas del teclado.

## Cómo lo hicimos

Este manual lo armamos conversando con una IA (Claude): le fuimos contando lo que hacíamos con la PC (instalar el disco, entrar a la BIOS, formatear) y a partir de eso salió una guía ordenada, con diseño propio y partes interactivas. Nos gusta **documentar todo lo que hacemos** y **experimentar con IA** para ver hasta dónde llega; este repo es parte de ese experimento.

La idea es mantenerlo vivo: cada vez que cambiemos algo en la PC (otro disco, otra pieza, una reinstalación), se actualiza el manual y queda la historia en los commits.

## Estado

- ✅ SSD MSI Spatium S270 de 480 GB instalado, detectado en BIOS y formateado como unidad `N:` (NTFS).
- ⬜ Pendiente: migrar los datos desde el disco WD Blue.

*(Estado a julio 2026. Se actualiza en cada edición.)*

## Cómo mantenerlo actualizado

1. Editar el manual (o generar una nueva edición) y reemplazar `index.html`.
2. Actualizar la sección **Estado** de este README y la fecha de edición.
3. Hacer un commit con un mensaje claro, por ejemplo: `Manual: actualiza estado, completa migración de datos`.

## Publicarlo como página web (GitHub Pages)

1. En el repo: **Settings → Pages**.
2. En *Build and deployment*, elegí **Deploy from a branch**, rama **main** y carpeta **/ (root)**.
3. **Save**. En un par de minutos queda en `https://nicoapaz.github.io/manual-pc/`.
