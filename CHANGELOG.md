# SuiteLand — Novedades

> Qué ha cambiado en el servidor, explicado para jugadores.
> Versión técnica detallada en [CHANGELOG-TECH.md](CHANGELOG-TECH.md).

**Versión actual:** `suiteland-1.0.0` — FTB Direwolf20 1.21.1

---

## v1.0.0 — 20 nov 2026 — Lanzamiento

### 🗺️ Mapa web
El servidor tiene mapa online: **http://37.230.138.123:8145**
- Mundo, Nether y End en tiempo real
- `/mapa` en el chat te da el link

### 📌 Marcadores en el mapa
Crea puntos y zonas visibles en el mapa web:
- `/marker add <nombre>` — marca tu posición
- `/marker shape` — marca un área de tu base o terreno
- `/marker extrude` — área con altura
- `/marker list` — tus marcadores
- Se guardan y sobreviven a reinicios

### 😴 AFK
- `/afk` — te pones en ausente
- Tu nombre pasa a gris con `[AFK]` delante y el tiempo aparece sobre tu cabeza
- Sales del AFK al moverte, hablar o atacar

### 📊 Perfil y tiempo jugado
- `/perfil` — tu ficha de jugador
- `/perfil <jugador>` — la de otro
- `/playtime` — cuánto llevas jugado
- `/top` — ranking de tiempo jugado

### 💬 Chat
- Formato limpio: `Nombre: mensaje`
- Pasa el ratón sobre un nombre → mini-perfil del jugador

### 🎨 Bienvenida
- Mensaje de bienvenida al entrar
- `/motd` — lo activas/desactivas
- `/motd show` — lo vuelves a ver sin salir del server

### ❓ Ayuda
- `/help` — lista de comandos disponibles para ti
- Hover → descripción; click → lo ejecuta

### ⚙️ Ajustes
- `/settings` — tus ajustes: bienvenida, ayuda compacta…
- Se guardan entre sesiones

### 📦 Sin instalación
- El mod se descarga solo al entrar — no instalas nada a mano
- Cada actualización te llega automáticamente

---

## Cambios respecto al modpack original

Resumen rápido — lista completa en [EXTRAS.md](EXTRAS.md):

**Añadido:** el mod `suiteland` (comandos del server), BlueMap (mapa web),
AutoModpack (descarga automática), EMI (más visor de recetas), skins sin
cuenta premium, y varios mods de optimización y estabilidad.

**Quitado:** ~25 mods puramente visuales de cliente (Embeddium, Iris,
FancyMenu, MouseTweaks…) y unos pocos de contenido (justdirethings,
retrofactorymanager, simple_weather).