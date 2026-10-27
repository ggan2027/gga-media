# gga-media

Alojamiento público de medios para publicar en Instagram por API.

## Para qué existe

La API de Instagram (Graph) **no acepta archivos**: solo acepta una URL pública
desde la que descargar el medio. Este repositorio es esa URL.

## Qué entra aquí

**Solo material que ya está destinado a ser público** — las mismas imágenes y
vídeos que van a salir publicados en la cuenta de Instagram de GGA · BioAncestral.

## Qué NO entra aquí, nunca

- Claves, tokens ni credenciales de ningún tipo
- Documentos personales, identificaciones, datos de pago
- Fotos que permitan identificar dónde vive o se encuentra la autora
- Material de terceros sin su permiso
- Borradores, material de trabajo o cualquier cosa del repo privado

Si tienes dudas sobre si un archivo entra aquí, no entra.

## Estructura

```
prueba/              archivos de prueba de la cadena de publicación
YYYY-MM-DD/          medios del lote de esa semana
```

Los archivos llegan ya normalizados a la especificación de la API
(`normalizar.py`, en el repo privado): JPEG para feed, MP4 h264/aac 1080×1920
para reels.

## Licencia

Todos los derechos reservados. El material es de Gabriela Gonzalo
(GGA · BioAncestral) y está aquí únicamente por un requisito técnico de la API.
