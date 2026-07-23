---
name: sincroniza
description: Revisa esta máquina, clona o actualiza el paquete claude-director y la deja igual que las demás - no asume nada, lo verifica en archivos. Dispara con "sincroniza mi oficina", "ponme al día", "es la primera vez en esta máquina", "configúrame igual que en la otra compu".
---

**No reconstruyas de memoria: todo el estado sale de archivos de ESTA máquina.**
Que ya lo hayas hecho en otra computadora no significa nada aquí.

**Paso 1 — Detecta el estado real de esta máquina.**
- Busca la carpeta del paquete: revisa la ruta anotada en tus reglas de la casa
  (`~/.claude/CLAUDE.md`, sección "Datos de esta instalación"); si no hay nada
  anotado ahí, es la primera vez en esta máquina — no preguntes, verifícalo tú.

**Paso 2A — Si NO existe el paquete aquí (máquina nueva):**
- Clónalo: `https://github.com/rafaelmendez91-creator/claude-director`
- Sigue el flujo completo de `EMPEZAR_AQUI.md` de punta a punta (reglas,
  skills, permisos, conectores, Despacho).
- Al terminar, avisa: "Esta es una máquina nueva, quedó instalada la versión
  [X]."

**Paso 2B — Si SÍ existe (máquina ya configurada antes):**
- `git pull` en esa carpeta.
- Lee `ACTUALIZACIONES.md` completo y compara la versión más reciente ahí
  contra la que tienes anotada en "Datos de esta instalación".
- Si hay diferencia, RE-APLICA lo que cambió (vuelve a copiar `CLAUDE.md` y
  `skills/` integrando sin perder "Preferencias del director" ni el resto de
  "Datos de esta instalación"). "Ya lo leí" no cuenta como actualizado.
- Si ya estaba al día, dilo igual — no lo des por sobreentendido.

**Paso 3 — Verifica que esta máquina vea lo mismo que las demás (el espejo).**
- Confirma que el Despacho responde: si vive en Google Drive, que la carpeta
  esté sincronizando en esta máquina (o que al menos la app de Claude la vea
  por conector); si es local, que exista y tenga los 3 archivos + `cierres`.
- Confirma qué conectores están activos (Gmail, Calendar, Drive) — se heredan
  de la cuenta de Claude, pero verifícalo, no lo asumas.
- Si algo del espejo no cuadra (Despacho no visible, conector caído), dilo
  claro con el paso exacto para arreglarlo — no lo dejes para después.

**Paso 4 — Cierre.**
Una línea: qué se hizo en esta máquina (clonado nuevo / actualizado de la
versión X a la Y / ya estaba al día), y si el espejo con las otras máquinas
quedó completo o con algo pendiente.
