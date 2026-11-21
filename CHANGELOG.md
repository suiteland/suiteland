# SuiteLand — Novedades

> Qué ha cambiado en el servidor — para jugadores.
> Versión técnica detallada en [docs privados](https://github.com/suiteland/docs).

**Versión actual:** `v1.3.0` · SuiteLand Pack 1.0.0

---

## v1.3.0 — 21 nov 2026 — Vínculo Discord↔Minecraft

**Vincula tu cuenta de Discord con la de Minecraft** — escribe en
`#💬chat` del Discord y aparece in-game con tu rango y perfil:

- **`/vincular`** en el juego → te da un código de 6 letras
- **`/vincular <código>`** en Discord → cuenta vinculada
- Escribes en `#💬chat` → sale `[Discord] [Admin] TuNombre » msg`
  con tu rango real y el hover de perfil (juegues o no — funciona
  offline)
- **`/desvincular`** — quita el vínculo desde el juego o Discord

**Chat bidireccional** — Discord y Minecraft comparten el mismo
chat: joins, leaves, muertes y logros de Minecraft aparecen en
`#💬chat`, y lo que escribas ahí aparece en el juego.

`/vhelp` — el `/help` vanilla para ops (el normal es el nuestro,
paginado y clickable).

## v1.2.0 — 20 nov 2026 — Perfil y estado

- `/perfil` — tu ficha: tiempo jugado, primera/última conexión,
  si estás AFK, en qué mundo estás. Click para mandar /msg.
- `/playtime [jugador]` — cuánto llevas jugado tú o cualquiera online
- `/seen <jugador>` — cuándo entró alguien por última vez

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