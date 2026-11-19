# Instalación paso a paso — SuiteLand

## La primera vez (una sola)

### Si usas CurseForge

1. Abre CurseForge → **Minecraft** → **Crear perfil personalizado**
2. **Importar** → selecciona el `.mrpack` descargado
3. Juega — el launcher ya tiene todo

### Si usas Prism Launcher

1. **Añadir instancia** → **Importar** → **Modrinth** → pega el `.mrpack`
2. Juega

### Si usas el launcher oficial

1. Descarga [NeoForge Installer](https://neoforged.net/) → instala para MC 1.21.1
2. Descarga `automodpack.jar` de las releases
3. Ponlo en `.minecraft/mods/` (Windows: `%appdata%\.minecraft\mods\`)
4. En el launcher: elige el perfil **NeoForge 21.1.267** → Jugar

## Después

Nada. Cuando conectas al server, AutoModpack descarga los cambios que
haya y reinicia solo. Si no hay cambios, entras directo.

## Problemas

| Síntoma | Solución |
|---|---|
| "Modpack mismatch" | Espera a que AutoModpack termine y reinicia |
| Pantalla roja al conectar | El server está actualizando — reintenta en 2 min |
| Crash al arrancar | Borra `.minecraft/mods/` menos `automodpack.jar` y vuelve a entrar |
