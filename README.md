# UI de Fecha de Nacimiento con Mala UX (intencional)

Este repositorio contiene una implementación single-file en `index.html` con HTML, CSS y JavaScript embebidos para crear una experiencia de ingreso de fecha de nacimiento deliberadamente incómoda.

## Qué funcionó
- Se mantuvo el requisito de un único archivo para la UI dinámica.
- El **día** se ingresa con una barra (1-31) que infla un globo visual.
- Si el usuario intenta bajar el día, el globo se desinfla completamente y el valor vuelve a 1.
- El **mes** se elige desde una grilla desordenada con nombres que se ocultan, forzando memoria visual.
- Si el mes se falla, la ronda se reinicia mostrando otra vez los meses desordenados.
- El **año** conserva la lógica de mezcla de dígitos y ahora incluye botón para reiniciar su ingreso.
- La validación final comprueba consistencia real de fecha.

## Qué no funcionó (o limitaciones)
- La interacción del mes es muy frustrante y depende de memoria a corto plazo.
- El castigo del día puede hacer tedioso alcanzar valores altos.
- La introducción del año sigue siendo inestable por el desorden automático.
- No se incorporó persistencia ni mejoras de accesibilidad (por diseño anti-UX).

## Archivos
- `index.html`: implementación completa (HTML/CSS/JS).
- `prompt.md`: anotación del prompt y decisiones de diseño.
- `README.md`: explicación de funcionamiento y limitaciones.
