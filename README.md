# UI de Fecha de Nacimiento con Mala UX (intencional)

Este repositorio contiene una implementación single-file (en `index.htl`) que combina HTML + CSS + JavaScript para una interfaz dinámica orientada a una **mala experiencia de usuario** a propósito.

## Qué funcionó
- Se construyó una interfaz totalmente autocontenida en un solo archivo.
- La interacción es dinámica mediante JavaScript dentro de `<script>`.
- El flujo permite capturar día, mes y año de nacimiento.
- Existe validación de fecha real (incluyendo consistencia de día/mes/año).
- La experiencia es difícil, pero completables: el usuario puede llegar a una fecha válida.

## Qué no funcionó (o limitaciones)
- La UX es deliberadamente mala, por lo que puede ser molesta para pruebas repetidas.
- El campo de año puede requerir varios intentos por el desorden automático.
- El mecanismo aleatorio de bloqueo de día puede fallar varias veces antes de dejar continuar.
- No hay persistencia de datos ni accesibilidad avanzada (porque el objetivo fue “anti-UX”).

## Archivos
- `index.htl`: implementación completa de la UI (HTML/CSS/JS).
- `prompt.md`: anotación del prompt y decisiones de diseño.
- `README.md`: resumen de funcionamiento y limitaciones.
