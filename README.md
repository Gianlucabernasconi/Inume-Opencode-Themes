# Inume Opencode Themes

Colección de 14 temas personalizados para [OpenCode](https://opencode.ai/), inspirados en tecnología vintage, ciencia y equipos retro.

## Instalación

Copia el archivo `.json` del tema que quieras usar a tu directorio de temas de OpenCode:

```bash
mkdir -p ~/.config/opencode/themes
cp themes/nombre-del-tema.json ~/.config/opencode/themes/
```

Luego actívalo con el comando:

```
/theme nombre-del-tema
```

O configúralo en tu `tui.json`:

```json
{
  "$schema": "https://opencode.ai/tui.json",
  "theme": "nombre-del-tema"
}
```

## Temas disponibles

| Tema | Acento | Descripción |
|------|--------|-------------|
| `obsidian-red` | 🔴 Rojo | Negro puro con acentos rojos intensos |
| `w95-classic` | 🟦 Azul marino + 🟩 Teal | Escritorio teal y grises industriales inspirados en Windows 95 |
| `cryogenic-stack` | 🔵 Azul brillante | Display de alta energía, terminal clásico |
| `crimson-reactor` | 🔴 Granate | Reactor científico, único rojo puro |
| `green-radar` | 🟢 Verde + 🟡 Ámbar | Señal táctica, warning nativo |
| `cyan-cga` | 🔵 Cian + 🟡 Ámbar | Terminal retro, más azulado que scope |
| `spectrum-8bits` | 🔵 Azul tinta | Spectrum contenido, lavanda gris |
| `lavender-quantum` | 🟣 Lila científico | Laboratorio avanzado, humo lila fino |
| `biofeedback-signal` | 🟢 Verde clínico | Monitor médico, menos saturado |
| `cathode-drift` | 🟢 Verde + 🔴 Rojo apagado | Electrónica audio 80s, error = warm nativo |
| `kernel-moss` | 🟢 Verde-gris | Oficina retro, materialidad administrativa |
| `faded-neon` | 🟢 Menta + 🩷 Rosa | Luz gastada, artística pero contenida |
| `old-code` | 🟢 Verde + 🟡 Ámbar | Negro ultra-profundo, warning nativo |
| `commodore-dust` | 🟤 Beige vintage | Hardware beige refinado con contraste disciplinado |

## Estructura del repo

```
themes/         → Archivos JSON de cada tema
scripts/        → Utilidades de validación y test
.github/        → Workflows de CI
```

## Crear un nuevo tema

1. Copia `themes/obsidian-red.json` como base
2. Modifica los colores en `defs` y `theme`
3. Valida el JSON: `node scripts/validate.js`
4. Agrega una fila en la tabla del README

## Licencia

MIT
