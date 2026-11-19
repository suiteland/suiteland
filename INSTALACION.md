# Instalación paso a paso — SuiteLand

## Paso 0 — Antes de instalar nada (en Discord)

El acceso al server se controla por vinculación Discord ↔ Minecraft.

1. Reacciona en el panel de avisos para obtener el rol de jugador
2. Ejecuta `/vincular TuNombreExacto` con tu nombre de Minecraft tal cual
   (3-16 caracteres, sin espacios, mayúsculas respetadas)
3. ✅ listo — ya puedes entrar al server en cuanto lo tengas instalado

> Si el nombre ya está vinculado a otra cuenta de Discord, el bot te lo
> dice — habla con un admin.

## Paso 1 — Instalar el pack

### CurseForge

1. Descarga el `.mrpack` de [Releases](../../releases/latest)
2. CurseForge → **Minecraft** → **Crear perfil personalizado** → **Importar**
   → selecciona el `.mrpack` (o arrastra el archivo sobre la ventana)
3. **Ajusta la RAM** (importante — el pack necesita ~10 GB):
   - Perfil → menú ⋮ → **Opciones de perfil**
   - Desmarca "usar memoria del sistema" → sube a **10240 MB** o más
4. Jugar → el launcher instala Java 21 y NeoForge solo

### Prism Launcher

1. **Añadir instancia** → **Importar** → **Modrinth** → el `.mrpack`
2. Editar instancia → Ajustes → Java → memoria: **10240 MB** min
3. Jugar

### Launcher oficial

1. Instala NeoForge 21.1.267 para Minecraft 1.21.1
2. Pon `automodpack.jar` (de Releases) en `%appdata%\.minecraft\mods\`
3. Perfil NeoForge → en Opciones de lanzamiento sube `-Xmx10G`
4. Jugar

## Paso 2 — Primera conexión

1. Multijugador → añadir server con la IP del Discord
2. Al conectar, AutoModpack descarga el pack completo (~2 GB — solo esta vez)
3. El juego se reinicia solo → conecta de nuevo → dentro

## Paso 3 — Entrar al mundo

| Tu caso | Qué pasa al entrar |
|---|---|
| Cuenta **premium** (Microsoft) | Entras directo — sin contraseñas |
| Cuenta **no premium** | Te pide `/register <contraseña> <contraseña>` la primera vez, `/login <contraseña>` después |

## Qué verás si algo falta

| Situación | Mensaje |
|---|---|
| Sin vincular (no estás en whitelist) | *"You are not white-listed on this server!"* → ve al Discord y `/vincular` |
| `/vincular` sin rol de jugador | El bot responde: necesitas el rol — reacciona en el panel |
| Nombre ya vinculado a otro Discord | El bot lo bloquea — habla con un admin |
| Vinculado pero sin /register | SimpleLogin te pide la contraseña en pantalla al entrar |

## Después — actualizaciones

Nada. Al conectar, los cambios del pack se descargan solos y reinicia.
Sin cambios → entras directo.

## Problemas

| Síntoma | Solución |
|---|---|
| El pack no descarga | Espera a que AutoModpack termine y reinicia el juego |
| Pantalla roja / kick al conectar | Server actualizando — reintenta en 2 min |
| Crash al arrancar el juego | Sube la RAM a 10-12 GB (causa #1) |
| Sigue crasheando | Borra `.minecraft/mods/` menos `automodpack.jar` y reintenta |
