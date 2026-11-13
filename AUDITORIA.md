# Auditoría de selección

Revisión realizada el 13/11/2026. Se abrió cada repositorio, se leyó entero cada SKILL.md y se consultó el último commit que modificó ese archivo mediante la API de GitHub. Las fechas siguientes son del archivo, no una estimación de actividad del repo.

## frontend-design

- Fuente: https://github.com/anthropics/skills/blob/41bbe19d1a1a7eaab5e7bb9050a417e5c6cffc8f/skills/frontend-design/SKILL.md
- Último cambio del SKILL.md: 2026-09-03T16:37:13Z (UTC).
- Lectura completa: realizada. No se encontraron pedidos de claves, credenciales, envío de información privada ni órdenes destructivas en ese archivo.
- Alcance: instrucciones de diseño y código de ejemplo; no se instalaron plugins ni se ejecutaron scripts del repositorio.

## better-typography

- Fuente: https://github.com/jakubkrehel/skills/blob/1eb03d2b145df1c6cd84ab54a337600a2a379017/skills/better-typography/SKILL.md
- Último cambio del SKILL.md: 2026-10-24T04:16:14Z (UTC).
- Lectura completa: realizada. No se encontraron pedidos de claves, credenciales, envío de información privada ni órdenes destructivas en ese archivo.
- Alcance: instrucciones de diseño y código de ejemplo; no se instalaron plugins ni se ejecutaron scripts del repositorio.

## better-colors

- Fuente: https://github.com/jakubkrehel/skills/blob/1eb03d2b145df1c6cd84ab54a337600a2a379017/skills/better-colors/SKILL.md
- Último cambio del SKILL.md: 2026-10-24T04:16:14Z (UTC).
- Lectura completa: realizada. No se encontraron pedidos de claves, credenciales, envío de información privada ni órdenes destructivas en ese archivo.
- Alcance: instrucciones de diseño y código de ejemplo; no se instalaron plugins ni se ejecutaron scripts del repositorio.

## animate

- Fuente: https://github.com/emilkowalski/skills/blob/f1090bec277140d02ed202440185ad9d02ac1490/skills/animate/SKILL.md
- Último cambio del SKILL.md: 2026-11-02T09:21:52Z (UTC).
- Lectura completa: realizada. No se encontraron pedidos de claves, credenciales, envío de información privada ni órdenes destructivas en ese archivo.
- Alcance: instrucciones de diseño y código de ejemplo; no se instalaron plugins ni se ejecutaron scripts del repositorio.

## visualization

- Fuente: https://github.com/atlassian-labs/data-visualization-skill/blob/2846a93e47356ce7415626d867d59a2fa567cbf5/skills/visualization/SKILL.md
- Último cambio del SKILL.md: 2026-10-26T23:45:30Z (UTC).
- Lectura completa: realizada. No se encontraron pedidos de claves, credenciales, envío de información privada ni órdenes destructivas en ese archivo.
- Alcance: instrucciones de diseño y código de ejemplo; no se instalaron plugins ni se ejecutaron scripts del repositorio.

## Alcance y decisiones

La revisión cubre los cinco SKILL.md enlazados y la receta de pulsación de animate. No es una auditoría de todos los archivos, dependencias ni futuras actualizaciones. Los enlaces fijados a commits permiten repetir la lectura de la versión revisada.

Se descartó claude-d3js-skill de la selección final porque su actividad consultada era de octubre de 2025. También se reemplazaron theme-factory y web-artifacts-builder por opciones con cambios más recientes en sus SKILL.md. No se detectó por ello que fueran maliciosos.

## Cómo se hicieron los ejemplos

- frontend-design: composición de una biblioteca de semillas ficticia. Paleta verde, tipografía editorial y una sola forma vegetal protagonista; sin datos reales inventados.
- better-typography: escala 48/28/18, texto de lectura limitado a 65ch, interlineado 1,6 y cifras tabulares. Fuentes del sistema.
- better-colors: tokens por función, una acción principal, estado escrito y contraste blanco/azul calculado en el navegador.
- animate: adaptación de la receta Button press (160 ms, escala 0,97); menos movimiento según la preferencia del sistema y sin movimiento al usar teclado. Receta: https://github.com/emilkowalski/skills/blob/main/skills/animate/RECIPES.md
- visualization: adaptación web con Plotly.js de los criterios Plotly del skill (paleta Lupi, fondo blanco, grilla ligera, etiquetas y fecha). No se ejecutó su implementación Python. Datos ficticios: A=12, B=18, C=9.

Las capturas se tomaron de las páginas locales renderizadas en Edge. Una captura estática no muestra el movimiento: abrir el ejemplo de animate y pulsar el botón.

IA utilizada: OpenAI Codex, basado en GPT-6. No se afirma que los estudiantes hayan usado Claude en esta entrega. Plotly.js se distribuye con su aviso de licencia dentro del archivo minificado. Los SKILL.md ajenos se enlazan, no se redistribuyen.
