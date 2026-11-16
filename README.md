# Recursos interactivos de Calidad y Gestión en Tecnología Sanitaria

Colección de recursos docentes en abierto de la asignatura Calidad y Gestión en Tecnología Sanitaria (59718), Grado en Ingeniería Biomédica, Escuela Politécnica de Cuenca, Universidad de Castilla-La Mancha.

Autor: César Sánchez Meléndez · cesar.sanchez@uclm.es

Se publica con GitHub Pages en `www.cesarsanchezmelendez.es/cgt-recursos/`.

## Estructura

```
cgt-recursos/
├── index.html                  Página de entrada con todos los recursos
├── logo-uclm.png               Logotipo compartido por todas las páginas
└── tema1/
    └── plazos-mdr-ivdr/        Calendario de plazos MDR/IVDR
        ├── index.html
        └── README.md
```

Cada recurso va en su propia carpeta, dentro del tema al que pertenece (`tema1/`, `tema2/`, `tema3/`), y tiene su propio README. Las páginas de las subcarpetas cargan el logotipo de la raíz (`../../logo-uclm.png`).

Para añadir un recurso nuevo:

1. Crea su carpeta en el tema que corresponda, por ejemplo `tema3/nombre-del-recurso/`, con su `index.html` y su `README.md`.
2. Añade una tarjeta en `index.html` de la raíz, dentro de la sección del tema, con un enlace relativo (`tema3/nombre-del-recurso/index.html`).
3. Si la sección del tema todavía no existe, créala y añádela al índice de la cabecera.

El Clasificador de productos sanitarios MDR/IVDR tiene su propio repositorio (`csmelendez/clasificaMD`). La página de entrada lo enlaza.

## Propuestas y errores

Las mejoras, los casos para practicar y los errores se recogen en las *issues* de este repositorio o por correo a cesar.sanchez@uclm.es.

## Licencias

- Página de entrada (`index.html` de la raíz): CC BY-SA 4.0.
- Cada recurso indica su licencia en su README. El Calendario de plazos usa EUPL-1.2 para el código y CC BY 4.0 para los textos y los datos.
- El logotipo de la UCLM queda excluido de todas ellas.
