# Anotación del prompt que generó el código

Se diseñó una interfaz deliberadamente incómoda para registrar fecha de nacimiento, cumpliendo con que toda la implementación viva en un único archivo con HTML, CSS y JavaScript embebidos.

## Objetivo del prompt
- Crear una UX intencionalmente mala, pero utilizable.
- Mantener toda la lógica dinámica en `<script>`.
- Evitar dependencias externas.

## Decisiones tomadas
1. **Día difícil**: contador automático que el usuario debe detener en el momento exacto.
2. **Mes confuso**: selector invertido y poco descriptivo.
3. **Año hostil**: input que reordena los dígitos, más un botón para empeorar el desorden.
4. **Feedback frustrante**: mensajes de error severos y microinteracciones de “shake”.
5. **Validación final**: a pesar de la fricción, permite completar exitosamente una fecha válida.

## Resultado esperado
Una experiencia frustrante de forma intencional, aunque técnicamente funcional para terminar ingresando una fecha de nacimiento real.
