# Asistencia ISU

Control de asistencia a entrenamientos para Inter Soccer USA Academy.

## Funciones

- **Marcar asistencia**: registra presentes/ausentes por fecha, con exportación a Excel (CSV) y PDF del día.
- **Resumen semanal**: asistencia por jugador en la semana seleccionada, con exportación a Excel y PDF.
- **Resumen mensual**: asistencia por jugador en el mes seleccionado, con score promedio y jugadores bajo 70% de asistencia.
- **Plantilla**: administración del roster de jugadores (nombre, categoría, posición).

Los datos se guardan localmente en el navegador (`localStorage`), sin necesidad de backend.

## Uso

Abre `index.html` en un navegador, o visita la versión publicada en GitHub Pages.

## Desarrollo

Es una app estática: no requiere build ni dependencias instaladas. Los archivos `support.js` y `_ds/**` son el runtime y el sistema de diseño que interpretan `index.html`.
