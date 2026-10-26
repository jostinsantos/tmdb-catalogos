# Catálogos Latino + Streams

## Todo dentro de plugin.js (sin instalar nada más)

- **Logo** en la ficha para el player.
- **Series / TV**: cada temporada trae episodios con:
  - `still` / `backdrop` del capítulo
  - `title` (título del episodio)
  - `overview` (sinopsis del episodio)
- **Streams**: lógica de extracción **embebida** de solo 5 fuentes prioritarias:
  - Embed69
  - Vimeus
  - LaMovie
  - EliFilms
  - HomeCine  
  (misma forma de búsqueda + parse de embeds que los originales, sin depender de archivos externos ni de instalar latinuvio-v2).

## Configuración del repo (Ajustes)

- **Secciones visibles**
- **Catálogos a ocultar**
- **Idioma TMDB**
- **Fuentes activas** (default: `embed69,vimeus,lamovie,elifilms,homecine`)
- **Fuentes simultáneas (máx)** → cuántas se prueban a la vez (1-5, default 3). Evita saturar.

## Instalación

Solo este repo. Sube la carpeta a GitHub e instálalo en la app. No hace falta ningún paquete adicional.
