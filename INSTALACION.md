# Instalación — SuiteLand

Entrar al server son 2 pasos: que un admin te meta en la whitelist →
instancia limpia + AutoModpack → conectar.

---

## 1. Whitelist

Pide a un admin que añada tu nombre de Minecraft **exacto**
(mayúsculas incluidas) a la whitelist del server. Es manual — tarda
segundos.

Sin whitelist no entras: el server dirá *"not white-listed"*.

---

## 2. Instancia limpia + AutoModpack

El pack se descarga **del server** cuando conectas — tú solo instalas
el mod que lo descarga.

### Versión exacta

Minecraft **1.21.1** · NeoForge **21.1.267** — no otra. Si tu
launcher te deja elegir, esas son. Si sale una lista larga de
NeoForge, coge la que empiece por `21.1.267`.

### AutoModpack — el único mod que instalas tú

| Launcher | Cómo lo instalas |
|---|---|
| **CurseForge** | Crea instancia 1.21.1 NeoForge → pestaña **Mods** → busca "AutoModpack" → **Instalar** |
| **Prism** | Instancia 1.21.1 NeoForge → **Edit** → **Mods** → Download → busca "AutoModpack" |
| **TLauncher** | Crea instancia 1.21.1 NeoForge → **TLMods** → busca "AutoModpack" → instala |

Si tu launcher no tiene buscador, bájalo suelto:
**https://www.curseforge.com/minecraft/mc-mods/automodpack**
y suéltalo en la carpeta `mods` de la instancia.

Un solo mod — el resto del pack se baja solo la primera vez.

### RAM

| Tu PC | Ponle al juego | Cómo irá |
|---|---|---|
| 8 GB | **6 GB** | Justito — cierra Chrome, render bajo |
| 16 GB | **10 GB** ✅ | Fluido |
| 32 GB+ | **12-16 GB** | Sobrado |

> No más de la mitad de tu RAM. Y más RAM no da más FPS — pasados
> ~10 GB solo empeora.

---

## 3. Conectar

1. Multijugador → **Añadir servidor** → la IP que te dieron
2. AutoModpack descarga el pack (pesa — paciencia la primera vez)
   - Si sale una pantalla con mods que **no están en las tiendas**
     (el nuestro `suiteland.jar`, CustomSkinLoader…) marca
     **"I understand the risk and trust this server"** → **Download**
   - Si pide verificar certificado → `Skip`
3. El juego se reinicia solo → conecta de nuevo → dentro

### Mods opcionales (grupo OPTIONAL)

Al conectar, AutoModpack te deja elegir mods opt-in. El que te interesa
si tu cuenta no es premium:

- **CustomSkinLoader** — para ver skins (tuya y de otros) sin cuenta
  premium. Márcalo y se instala solo.

---

## Si algo falla

| Mensaje | Qué hacer |
|---|---|
| *"not white-listed"* | Pide al admin que añada tu nombre exacto |
| El pack no baja | Espera y reinicia el juego |
| Crash al arrancar | RAM baja — mínimo 6 GB |
| Se congela | Demasiada RAM — baja a 8-10 GB |
| Sigue crasheando | Borra `mods/` menos `automodpack.jar` y reentra |
| No ves tu skin | Activa CustomSkinLoader (grupo OPTIONAL) |

---

## Resumen

```
Admin añade tu nombre a la whitelist
        ↓
Instancia 1.21.1 + NeoForge 21.1.267 + AutoModpack
        ↓
Conecta a la IP → el pack se baja solo → reinicio → dentro
        ↓
(Opcional) marca CustomSkinLoader si no eres premium
```
