# SuiteLand — Novedades

> Qué ha cambiado en el servidor — para jugadores.
> Versión técnica detallada en [docs privados](https://github.com/suiteland/docs).

**Versión actual:** `v1.2.0` · FTB Direwolf20 1.21.1

---

## v1.2.0 — 20 nov 2026 — Perfil + tags + chat

- `/perfil` — tu ficha: estado, tiempo jugado, primera/última conexión, AFK, mundo. Click para mandar /msg.
- `/seen <jugador>` — cuándo entró alguien por última vez
- `/playtime` — cuánto llevas jugado (lo lee de las stats del juego)
- `/tag` — oculta o muestra tu tag (si tienes permiso)
- Tags visibles: en el tab, encima de la cabeza, y en el chat
- El chat usa `»` en vez de `<>`
- Mensaje de bienvenida renovado — más limpio, con mapa clicable
- Los admins ven el árbol de permisos con `/sl perms`

## v1.1.0 — 20 nov 2026 — Permisos + mejoras

- Sistema de permisos jerárquico — los admins gestionan quién
  puede usar cada comando sin tocar configs
- `/player` — fake players estilo Carpet (spawn, kill, tp, afk)
- Chat sin `<>` — formato `nombre » mensaje` nativo
- `/sl tag set|clear` — gestionar tags de cualquier jugador

## v1.0.1 — 20 nov 2026 — Fix y polish

- `/map` `/mapa` — link al mapa web ahora **clicable** (abre en el navegador)
- `/help` — paginación arreglada: `/help 2` funciona, los botones de página responden, y los clicks en comandos sugieren solo lo editable
- `/afk` — arreglado el comando duplicado que causaba comportamiento errático
- `/motd show` — el mensaje de bienvenida ahora formatea bien tu nombre y tiempo jugado
- Skins — añadido **SkinRestorer**: las cabezas en el mapa web ahora cargan skins de cuentas no-premium

## v1.0.0 — 20 nov 2026 — Lanzamiento

- Mapa web: http://37.230.138.123:8145 — `/mapa`
- Marcadores en el mapa con `/marker` — puntos, zonas, extrusiones
- `/afk` — nombre gris + tiempo AFK sobre la cabeza
- `/perfil`, `/playtime`, `/top` — ficha y ranking de tiempo jugado
- `/help` — comandos con hover + click para ejecutar
- `/settings` — ajustes personales que persisten
- `/motd` — mensaje de bienvenida personalizable
- AutoModpack — actualizaciones automáticas al conectar