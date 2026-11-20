# SuiteLand — Novedades

> Qué ha cambiado en el servidor — para jugadores.
> Versión técnica detallada en [docs privados](https://github.com/suiteland/docs).

**Versión actual:** `v1.0.1` · FTB Direwolf20 1.21.1

---

## v1.0.1 — 20 nov 2026 — Fix y polish

- `/map` `/mapa` — link al mapa web ahora **clicable** (abre en el navegador)
- `/tag` — toggle simple: muestra/oculta tu tag sin argumentos (`/tag on|off` también funciona)
- `/help` — paginación arreglada: `/help 2` funciona, los botones de página responden, y los clicks en comandos sugieren solo lo editable (sin `<nombre>`)
- `/afk` — arreglado el comando duplicado que causaba comportamiento errático
- `/motd show` — el mensaje de bienvenida ahora formatea bien `%player%` `%playtime%` (antes salían literales)
- Skins — añadido **SkinRestorer** en el server: las cabezas en el mapa web (BlueMap) ahora cargan skins de cuentas no-premium
- Mod `suiteland` bump a `1.0.1` — AutoModpack lo distribuye al conectar

## v1.0.0 — 20 nov 2026 — Lanzamiento

- Mapa web: http://37.230.138.123:8145 — `/mapa`
- Marcadores en el mapa con `/marker` — puntos, zonas, extrusiones
- `/afk` — nombre gris + tiempo AFK sobre la cabeza
- `/perfil`, `/playtime`, `/top` — ficha y ranking de tiempo jugado
- `/help` — comandos con hover + click para ejecutar
- `/settings` — ajustes personales que persisten
- `/motd` — mensaje de bienvenida personalizable
- AutoModpack — actualizaciones automáticas al conectar