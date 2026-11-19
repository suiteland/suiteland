# Instalación paso a paso — SuiteLand

Guía completa para entrar al server. Necesitas Discord + Minecraft con
cualquier launcher moderno.

---

## Paso 0 — Vincular tu cuenta (en Discord)

El acceso lo controla el bot — vinculas tu nombre de Minecraft a tu
Discord. Sin esto, no entras.

### 0.1 — Consigue el rol

Pide a un admin el rol **`SuiteLand - Jugador`**. Es manual — no se
consigue solo. Cuando lo tengas:

### 0.2 — `/mc link TuNombre`

En cualquier canal del Discord escribe:

```
/mc link TuNombreDeMinecraft
```

- Nombre **exacto** del juego (3-16 caracteres, sin espacios, con las
  mayúsculas/minúsculas que vayas a usar al entrar).
- El bot responde en privado (solo lo ves tú).

### 0.3 — ¿Premium o no?

| Tu cuenta | Qué pasa |
|---|---|
| **Premium** (Microsoft oficial) | ✅ Vinculado al instante — ya puedes entrar. Ve al Paso 1. |
| **No premium** (cracked, TLauncher, etc.) | El bot te da un **código de 6 dígitos** — sigue leyendo ↓ |

### 0.4 — Verificación con código (solo no premium)

El código demuestra que eres tú el que entró con ese nombre:

1. Copia el código que te dio el bot (ej: `482917`)
2. Entra al server con **ese nombre** — ya estás en la whitelist temporal
3. Al entrar estarás **congelado en un limbo** — no te muevas, es normal
4. Escribe en el chat del juego: `/link 482917`
   (o el código a pelo si el mod aún no está activo)
5. ✅ `§a✔ Cuenta verificada` — te descongela y quedas vinculado

**Si no lo haces en 15 minutos** el código muere, sales de la whitelist
y el bot te avisa por DM — vuelve a `/mc link`.

> 💡 El limbo existe para que nadie robe tu nombre: solo sale de él
> quien demuestra tener el código Y haber entrado con esa cuenta.

---

## Paso 1 — Instalar el pack

Descarga el `.mrpack` de [Releases](../../releases/latest) — es la
instancia completa.

### RAM — el ajuste más importante

El pack pide bastante, pero se ajusta al PC que tengas:

| Tu PC total | Ponle al juego | Cómo irá |
|---|---|---|
| 8 GB | **6 GB** | Justito — cierra Chrome y lo demás, render bajo (8-10 chunks) |
| 16 GB | **10 GB** ✅ | Recomendado — va fluido, settings normales |
| 32 GB+ | **12-16 GB** | Sobrado — máximo render, shaders si quieres |

> ⚠️ **No pongas más de la mitad de tu RAM total** — el SO y Java
> necesitan aire. Con 8GB de PC, 6 al juego es el límite sano.
>
> 💡 En Java, **más RAM no es más FPS** — pasados ~10-12 GB solo empeora
> la recolección de basura. El sweet spot es 8-10 GB para este pack.

### CurseForge

1. **Minecraft** → **Crear perfil personalizado** → **Importar**
   → el `.mrpack` (o arrastra el archivo)
2. Perfil → ⋮ → Opciones → memoria → según tu PC (tabla ↑)
3. Jugar

### Prism Launcher

1. **Añadir instancia** → **Importar** → **Modrinth** → el `.mrpack`
2. Editar → Java → memoria: según tu PC (tabla ↑)
3. Jugar

### Launcher oficial

1. Instala NeoForge 21.1.267 para MC 1.21.1
2. `automodpack.jar` en `%appdata%\.minecraft\mods\`
3. Opciones de lanzamiento → `-Xmx8G` (o lo que aguante tu PC)

---

## Paso 2 — Primera conexión

1. Multijugador → **Añadir servidor** → la IP que te dieron
2. Al conectar, **AutoModpack descarga el pack** (~2 GB — solo esta vez)
   - Si te pide verificación del certificado → `Skip` (opcional) o pega el
     fingerprint que aparece fijado en `ℹ️-info` del Discord → `Verify`
3. El juego se reinicia solo → conecta de nuevo → dentro

> El fingerprint lo publica el bot en `ℹ️-info` — se actualiza solo si el
> server regenera el certificado.

---

## Paso 3 — Registro en el juego (SimpleLogin)

El server no usa cuentas de Microsoft — lleva su propio sistema:

| Es tu primera vez | Qué escribes en el chat |
|---|---|
| Sí, primera entrada | `/register TuContraseña TuContraseña` |
| Ya te registraste antes | `/login TuContraseña` |

> 🔐 Tu contraseña ancla tu nombre: nadie puede ser "tú" sin ella.
> Elige una que recuerdes — no hay recuperación automática.

### Si eres no premium y usaste código

El orden dentro del juego es: `/register` (o `/login`) → `/link 482917`.
SimpleLogin bloquea `/link` hasta que estés autenticado — así solo tú
puedes confirmar tu propio nombre.

---

## Después — actualizaciones

Nada. Al conectar, los cambios del pack se descargan solos y el juego
reinicia. Sin cambios → entras directo.

---

## Qué verás si algo falta

| Mensaje | Significado |
|---|---|
| *"You are not white-listed"* | No hiciste `/mc link` o el código caducó |
| El bot: "necesitas el rol Jugador" | Pide el rol a un admin primero |
| *"ya está vinculado"* | Otro Discord ya usó ese nombre — habla con admin |
| *"Código no válido o caducado"* | Pasaron 15 min — `/mc link` de nuevo |
| Te quedas quieto al entrar | Limbo de verificación — `/link CODIGO` |

## Problemas

| Síntoma | Solución |
|---|---|
| El pack no descarga | Espera a AutoModpack y reinicia el juego |
| Pantalla roja al conectar | Server actualizando — reintenta en 2 min |
| Crash al arrancar | RAM baja — mínimo 6 GB al juego (mira la tabla) |
| Se congela / GC cada pocos segundos | Demasiada RAM — baja a 8-10 GB |
| Sigue crasheando | Borra `.minecraft/mods/` menos `automodpack.jar` |
| Lag bajo | Render a 8-10 chunks, desactiva shaders |

---

## Resumen — el camino feliz

```
Discord          Juego
───────────────────────────────────────────
admin te da rol
  Jugador
    │
/mc link Nombre ──→ premium: vinculado ya
                └──→ no premium: código 482917
                     │
                     ├── instala .mrpack
                     ├── conecta a la IP
                     ├── /register clave clave   (1ª vez)
                     └── /link 482917            (con código)
                          │
                     ¡a jugar! 🏝️
```
