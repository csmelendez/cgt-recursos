# Calendario de plazos MDR/IVDR

Recurso docente en abierto sobre los plazos de la regulación de productos sanitarios. Separa tres «relojes» que suelen confundirse:

1. **Transición**: hasta cuándo puede introducirse en el mercado un producto heredado (Reglamentos (UE) 2023/607 y 2024/1860).
2. **EUDAMED**: qué tiene que constar en la base de datos y desde cuándo (Reglamento (UE) 2024/1860 y Decisión (UE) 2025/2371).
3. **Revisión**: la propuesta COM(2025) 1023, en tramitación.

Incluye una línea temporal interactiva, un comprobador de plazos por producto, casos para practicar que se cargan en el comprobador y un bloque de errores frecuentes.

Asignatura: Calidad y Gestión en Tecnología Sanitaria (59718).

Autor: César Sánchez Meléndez · Escuela Politécnica de Cuenca, Universidad de Castilla-La Mancha.

## Uso

Es una sola página (`index.html`) sin dependencias ni servidor. Forma parte del repositorio `cgt-recursos` y se sirve en `www.cesarsanchezmelendez.es/cgt-recursos/tema1/plazos-mdr-ivdr/`.

Usa el logotipo de la raíz del repositorio (`../../logo-uclm.png`).

## Actualizar los plazos

Todos los datos están al principio del script de `index.html`:

- `REVISADO`: fecha de la última revisión de la normativa (aparece en la cabecera).
- `HITOS`: cada fecha de la línea temporal, con su explicación, base legal y fuente.
- `FUENTES`: enlaces a EUR-Lex y a los documentos de la Comisión.
- `CASOS`: casos para practicar, con las respuestas que cargan en el comprobador y su solución comentada.
- `MITOS`: afirmaciones de verdadero o falso del bloque de errores frecuentes.
- `REPO` y `CARPETA`: repositorio y carpeta del recurso, para los enlaces de «Proponer una mejora» y «Ver el código».

La página también muestra los hitos como JSON, para revisarlos sin leer el código.

## Propuestas y errores

Las mejoras, los casos para practicar y los errores se recogen en las *issues* del repositorio o por correo a cesar.sanchez@uclm.es.

## Licencia

© 2026 César Sánchez Meléndez.

Este material se publica con licencia Creative Commons Atribución-CompartirIgual 4.0 Internacional (CC BY-SA 4.0). Puedes copiarlo, adaptarlo y redistribuirlo citando la autoría y compartiendo tus versiones con la misma licencia. La licencia cubre también el código. El texto completo está en el archivo `LICENSE` de la raíz del repositorio.

El logotipo de la UCLM queda excluido.

## Uso de inteligencia artificial

Un asistente de IA ha ayudado a redactar el código, la interfaz y los textos. El autor ha revisado los plazos y las explicaciones. La página no usa IA: todo se calcula en el navegador con reglas fijas.

El resultado es orientativo y no sustituye la lectura de los reglamentos ni el criterio del organismo notificado.
