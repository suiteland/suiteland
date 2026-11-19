# Instalación — SuiteLand

Entrar al server son 4 pasos: rol en Discord → `/mc link` → instancia
limpia + AutoModpack → conectar.

---

## 1. Rol en Discord

Pide a un admin el rol **`SuiteLand - Jugador`**. Es manual — no se da
solo. Sin rol no entras.

**¿Ya lo tienes?** Si ves los canales del Discord — `ℹ️-info`,
`💬-chat`, `🔔-notificaciones` — ya lo tienes. Si no los ves, pide el
rol a un admin.

---

## 2. Vincular tu cuenta

En cualquier canal:

```
/mc link TuNombreDeMinecraft
```

El nombre **exacto** que uses al entrar (mayúsculas y todo).

| Tu cuenta | Qué pasa |
|---|---|
| **Premium** | Vinculado ya — ve al paso 3 |
| **No premium** | Te da un código de 6 dígitos — lo usas al entrar |

**Con código:** entras al server, te quedas congelado (es normal),
escribes `/register TuClave TuClave` y luego `/link 482917` (tu código).
Si pasan 15 min sin hacerlo, el código muere — repite `/mc link`.

---

## 3. Instancia limpia + AutoModpack

El pack se descarga **del server** cuando conectas — tú solo instalas
el mod que lo descarga.

### AutoModpack — el único mod que instalas tú

En **CurseForge** o **TLauncher** lo instalas desde el propio launcher:

| Launcher | Cómo lo instalas |
|---|---|
| **CurseForge** | Crea instancia 1.21.1 NeoForge → pestaña **Mods** → busca "AutoModpack" → **Instalar** |
| **TLauncher** | Crea instancia 1.21.1 NeoForge → **TLMods** → busca "AutoModpack" → instala |

Si tu launcher no tiene buscador de mods, bájalo suelto:
**https://www.curseforge.com/minecraft/mc-mods/automodpack**
y suéltalo en la carpeta `mods` de la instancia.

Un solo mod — el resto del pack (~2 GB) se baja solo la primera vez.

### RAM

| Tu PC | Ponle al juego | Cómo irá |
|---|---|---|
| 8 GB | **6 GB** | Justito — cierra Chrome, render bajo |
| 16 GB | **10 GB** ✅ | Fluido |
| 32 GB+ | **12-16 GB** | Sobrado |

> No más de la mitad de tu RAM. Y más RAM no da más FPS — pasados
> ~10 GB solo empeora.

---

## 4. Conectar

1. Multijugador → **Añadir servidor** → la IP que te dieron
2. AutoModpack descarga el pack (~2 GB, una vez)
   - Si pide verificar certificado → `Skip` o pega el fingerprint
     fijado en `ℹ️-info` del Discord
3. El juego se reinicia solo → conecta de nuevo → dentro

### En el juego

| Tu caso | Escribes |
|---|---|
| Primera vez | `/register TuClave TuClave` |
| Ya registrado | `/login TuClave` |
| Con código pendiente | `/register` → `/link CODIGO` |

Sin código → vinculado ya, solo `/register`.

---

## Si algo falla

| Mensaje | Qué hacer |
|---|---|
| *"not white-listed"* | No hiciste `/mc link` o el código caducó |
| El bot dice "falta el rol" | Pide `SuiteLand - Jugador` a un admin |
| *"ya está vinculado"* | Otro usó ese nombre — habla con admin |
| *"Código no válido"* | Pasaron 15 min — `/mc link` de nuevo |
| Te quedas quieto al entrar | Es el limbo — `/link CODIGO` |
| El pack no baja | Espera y reinicia el juego |
| Crash al arrancar | RAM baja — mínimo 6 GB |
| Se congela | Demasiada RAM — baja a 8-10 GB |
| Sigue crasheando | Borra `mods/` menos `automodpack.jar` |

---

## Resumen

```
Admin te da el rol "SuiteLand - Jugador"
        ↓
/mc link TuNombre    →  premium: listo / no premium: código
        ↓
Instancia limpia + AutoModpack + conectar a la IP
        ↓
/register clave clave  +  /link CODIGO (si lo tienes)
        ↓
    dentro
```
