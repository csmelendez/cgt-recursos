# Calendario de plazos MDR/IVDR

Recurso docente en abierto sobre los plazos de la regulación de productos sanitarios. Separa tres «relojes» que suelen confundirse:

1. **Transición**: hasta cuándo puede introducirse en el mercado un producto heredado (Reglamentos (UE) 2023/607 y 2024/1860).
2. **EUDAMED**: qué tiene que constar en la base de datos y desde cuándo (Reglamento (UE) 2024/1860 y Decisión (UE) 2025/2371).
3. **Revisión**: la propuesta COM(2025) 1023, en tramitación.

Asignatura: Calidad y Gestión en Tecnología Sanitaria (59718), Tema 1.

Autor: César Sánchez Meléndez · Escuela Politécnica de Cuenca, Universidad de Castilla-La Mancha.

## Escenas

Sigue el formato de las presentaciones de la colección de Evaluación de Tecnología Sanitaria: nueve escenas, algunas con varios pasos.

| # | Escena | Qué hay |
|---|--------|---------|
| 1 | Tres relojes | Las tres preguntas y la confusión más habitual |
| 2 | Introducir no es comercializar | Definiciones del art. 2 del MDR y supresión del *sell-off* |
| 3 | Reloj 1 · Transición MDR | Línea temporal, grupos de clases y condiciones |
| 4 | Reloj 1 · Transición IVDR | Tabla de hitos por grupo |
| 5 | Reloj 2 · EUDAMED | Línea temporal, módulos obligatorios y quién registra qué |
| 6 | Reloj 3 · Revisión | Estado del procedimiento 2025/0404(COD) |
| 7 | ¿Qué plazos afectan a mi producto? | Comprobador con seis casos y solución comentada |
| 8 | Errores frecuentes | Siete afirmaciones de verdadero o falso |
| 9 | Antes de dar por buena una fecha | Lista de comprobación, colaboraciones, licencia y uso de IA |

## Uso

Es una sola página (`index.html`) sin dependencias, salvo las fuentes de Google Fonts. Forma parte del repositorio `cgt-recursos` y se sirve en `www.cesarsanchezmelendez.es/cgt-recursos/tema1/plazos-mdr-ivdr/`.

Se navega con las flechas del teclado, con los botones «Anterior» y «Siguiente» o pulsando en el escenario. La tecla F activa la pantalla completa. En las escenas 7 y 8 las flechas no avanzan mientras se usan los controles.

## Actualizar los plazos

Los datos están en el primer script de `index.html`:

- `REVISADO`: fecha de la última revisión de la normativa.
- `F`: enlaces a EUR-Lex y a los documentos de la Comisión que aparecen como fuente.
- `ESCENAS`: título, pregunta, texto, fuente y número de pasos de cada escena.
- `PREG` y `evaluar()`: preguntas y reglas del comprobador.
- `CASOS`: casos para practicar, con las respuestas que cargan en el comprobador y su solución.
- `MITOS`: afirmaciones del bloque de errores frecuentes.
- Las llamadas a `lineaTemporal()` al final del script: fechas de las líneas temporales de las escenas 3 y 5.

Las fechas que aparecen como texto en las escenas 3 a 6 están en el HTML de cada escena. Si cambia un plazo, hay que cambiarlo en los dos sitios.

## Propuestas y errores

Las mejoras, los casos para practicar y los errores se recogen en las *issues* del repositorio o por correo a cesar.sanchez@uclm.es.

## Licencia

© 2026 César Sánchez Meléndez.

Este material se publica con licencia Creative Commons Atribución-CompartirIgual 4.0 Internacional (CC BY-SA 4.0). Puedes copiarlo, adaptarlo y redistribuirlo citando la autoría y compartiendo tus versiones con la misma licencia. La licencia cubre también el código. El texto completo está en el archivo `LICENSE` de la raíz del repositorio.

El logotipo de la UCLM queda excluido.

## Uso de inteligencia artificial

Un asistente de IA ha ayudado a redactar el código, la interfaz y los textos. El autor ha revisado los plazos y las explicaciones. La página no usa IA: todo se calcula en el navegador con reglas fijas.

El resultado es orientativo y no sustituye la lectura de los reglamentos ni el criterio del organismo notificado.
