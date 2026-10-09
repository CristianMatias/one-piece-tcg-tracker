# One Piece TCG Tracker

Aplicación web de una sola página (HTML + CSS + JS, sin dependencias ni build)
para llevar el registro de partidas, mazos, líderes y torneos de One Piece
Card Game.

## Características

- **Registro de partidas**: líder propio, líder rival, turno, mano, resultado
  y tipo de partida (Casual, Ranked, Torneo, Entrenamiento).
- **Estadísticas por líder**: winrate, racha actual, racha más larga,
  desglose por color rival y mejor/peor rival. Las partidas de tipo
  *Entrenamiento* cuentan para los enfrentamientos por líder/color pero no
  afectan al winrate, las rachas ni el histórico de victorias/derrotas.
- **Constructor de mazos**: lista de cartas con límites de copias (4 por
  defecto, con excepciones documentadas), foto del líder y contador de
  51 cartas.
- **Modo torneo**: formulario flotante con rondas dinámicas, resultados por
  ronda y posición final, guardado en el historial de partidas.
- **Datos locales**: todo se guarda en `localStorage` del navegador — no hay
  backend ni servidor.
- **Modo claro/oscuro** automático según las preferencias del sistema.

## Uso

Abre `index.html` directamente en el navegador. No requiere instalación,
servidor ni dependencias externas.

## Stack

HTML, CSS y JavaScript vanilla en un único fichero autocontenido.

## Licencia

Este proyecto es software libre, publicado bajo la [GNU General Public
License v3.0](LICENSE). Cualquiera puede usarlo, copiarlo, modificarlo y
distribuirlo, siempre que las versiones derivadas se publiquen también
como código abierto bajo la misma licencia.
