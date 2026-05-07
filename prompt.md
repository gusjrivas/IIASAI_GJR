# Anotación del prompt que generó el código

Se rediseñó la UI para mantener una experiencia deliberadamente mala, incorporando nuevas reglas de interacción solicitadas y conservando toda la implementación en un único `index.html` con HTML/CSS/JS embebidos.

## Objetivo del prompt
- Mantener una UX anti-usuario pero alcanzable.
- Día mediante barra de volumen y comportamiento punitivo de reinicio.
- Mes mediante juego de memoria con grilla desordenada y ocultamiento de etiquetas.
- Mantener el año con lógica de desorden y agregar reinicio específico.

## Decisiones tomadas
1. **Día con globo**: slider de 1 a 31 que infla un globo visualmente.
2. **Castigo por bajar**: si el usuario intenta disminuir el día, el sistema reinicia a 1 (desinflado total).
3. **Mes por memoria**: grilla aleatoria de meses; se muestran nombres por pocos segundos y luego se ocultan.
4. **Fallo en mes**: si no acierta en el primer intento, se reinicia la ronda y se vuelven a mostrar los meses desordenados.
5. **Año hostil + reset**: continúa el mezclado automático de dígitos y se agrega botón para reiniciar el ingreso del año.

## Resultado esperado
Una interfaz más frustrante que la versión anterior, pero funcional para completar finalmente una fecha de nacimiento válida.
