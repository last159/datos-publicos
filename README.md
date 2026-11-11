# Datos de DIRPOL

Los datos que descarga la app **DIRPOL · Directorio Policial de Colombia**
para ponerse al día sin publicar una versión nueva. GitHub Pages sirve esta
carpeta en <https://last159.github.io/dirpol-datos/>.

DIRPOL es una app independiente de difusión. No es de la Policía Nacional ni
de ninguna entidad del Estado.

| Archivo | Qué trae | De dónde sale |
| --- | --- | --- |
| `lineas.json` | Líneas de atención y entidades | Verificado a mano contra la fuente oficial de cada una |
| `tramites.json` | Trámites, con sus pasos y avisos | Verificado a mano contra la fuente oficial de cada uno |
| `guias.json` | Guías propias, con las fuentes que citan | Redactadas para la app |
| `noticias.json` | Titulares, con enlace a la nota completa | Listado público de policia.gov.co/noticias |
| `directorio_policia.json` | Sedes y dependencias de la Policía | policia.gov.co/directorio |
| `manifiesto.json` | Huella y fecha de cada archivo | Se genera al publicar |

Nada de esta carpeta se edita a mano: la escribe un flujo automático desde el
repositorio de la app, tres veces al día y cada vez que cambian los datos.
