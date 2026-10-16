# Piano a dos manos

Generador interactivo de piano en el navegador: una mano izquierda que marca un bucle fijo y una mano derecha que improvisa con un pequeño conjunto de notas. Todo corre en una sola página HTML, sin dependencias ni backend.

### [▶ Probar](https://luissalazarvaca1986.github.io/jazz-generator/)

## Cómo funciona

- **Mano izquierda** — bucle fijo `A → G → F → E`, una nota por segundo.
- **Mano derecha** — notas al azar entre `A, C, D, D#, E, G, A`, con duración entre 0.25 s y 0.75 s. Cada 3 notas puede insertar un silencio de 0.75 s (50% de probabilidad).
- **Teclado visual** — rango E2–A4. Las teclas usadas por cada mano se marcan con el color correspondiente y se iluminan al sonar.
- **Panel de estado** — muestra la nota actual de cada mano (notación inglesa y española) y su duración.

## Uso

1. Abrir [la demo](https://luissalazarvaca1986.github.io/jazz-generator/) o `Jazz_gen.html` localmente en un navegador moderno.
2. Pulsar el botón de play (▶) para iniciar.
3. Ajustar el volumen con el deslizador vertical.
4. Pulsar stop (■) para detener.

El audio se pausa automáticamente si la pestaña queda oculta.

## Tecnología

- HTML + CSS + JavaScript vanilla.
- **Web Audio API** para síntesis: osciladores (triangle + 3 armónicos sinusoidales), filtro pasa-bajos dinámico, envolvente ADSR y compresor en el master.
- Tipografía Bricolage Grotesque (Google Fonts).
- Tema claro/oscuro automático según preferencia del sistema.
- Responsive, con soporte para safe-area en móviles.

## Archivos

- `Jazz_gen.html` — aplicación completa (single-file).
- `index.html` — redirección para GitHub Pages.
- `especificaciones.md` — notas de diseño.
