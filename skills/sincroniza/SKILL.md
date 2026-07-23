---
name: sincroniza
description: Revisa esta máquina, clona o actualiza la copia PERSONAL del director en GitHub y la deja igual que las demás - no asume nada, lo verifica en archivos. Dispara con "sincroniza mi oficina", "ponme al día", "es la primera vez en esta máquina", "configúrame igual que en la otra compu".
---

**No reconstruyas de memoria: todo el estado sale de archivos.** Que ya lo
hayas hecho en otra computadora no significa nada aquí. Y esta NO es la
plantilla pública de Rafael — es la copia PERSONAL del director en su propia
cuenta de GitHub, con el nombre que él le haya puesto.

**Paso 1 — Encuentra la dirección de SU copia (nunca la des por sabida).**
Búscala en este orden, parando en la primera que encuentres:
1. Tus reglas de la casa (`~/.claude/CLAUDE.md`, "Datos de esta instalación").
2. Si no está ahí: el archivo `CONFIG.md` dentro de su Despacho (en su Google
   Drive) — ya deberías poder verlo por el conector de Drive de su cuenta,
   aunque esta máquina sea nueva.
3. Si tampoco aparece ahí: pregúntale UNA vez "¿cuál es la dirección de tu
   copia en GitHub?", y en cuanto la tengas, guárdala en AMBOS lugares (tus
   reglas de la casa Y `Despacho/CONFIG.md`) para que ninguna otra máquina
   tenga que volver a preguntarla.

**Paso 2 — Detecta el estado real de ESTA máquina.**
- Revisa si la carpeta de su copia ya existe aquí (ruta anotada en tus reglas
  de la casa). Si no hay nada anotado, trátalo como primera vez en esta
  máquina — no preguntes, verifícalo tú mismo revisando la carpeta.

**Paso 3A — Si NO existe aquí (máquina nueva):**
- Clona SU copia (la dirección del Paso 1 — nunca la plantilla de Rafael).
- Sigue el flujo completo de `EMPEZAR_AQUI.md`, empezando por la PARTE 1 (la
  PARTE 0 de crear la copia ya no aplica: la copia ya existe, solo hace falta
  bajarla aquí).
- Al terminar, avisa: "Esta es una máquina nueva, quedó instalada la versión
  [X] de tu copia."

**Paso 3B — Si SÍ existe (máquina ya configurada antes):**
- `git pull` en esa carpeta.
- Lee `ACTUALIZACIONES.md` completo y compara la versión más reciente ahí
  contra la que tienes anotada en "Datos de esta instalación".
- Si hay diferencia, RE-APLICA lo que cambió (vuelve a copiar `CLAUDE.md` y
  `skills/` integrando sin perder "Preferencias del director" ni el resto de
  "Datos de esta instalación"). "Ya lo leí" no cuenta como actualizado.
- Si ya estaba al día, dilo igual — no lo des por sobreentendido.

**Paso 4 — Verifica que esta máquina vea lo mismo que las demás (el espejo).**
- Confirma que el Despacho responde: si vive en Google Drive, que la carpeta
  esté sincronizando en esta máquina (o que al menos la app de Claude la vea
  por conector); si es local, que exista y tenga los 4 archivos + `cierres`.
- Confirma qué conectores están activos (Gmail, Calendar, Drive) — se heredan
  de la cuenta de Claude, pero verifícalo, no lo asumas.
- Si algo del espejo no cuadra (Despacho no visible, conector caído, `CONFIG.md`
  con una dirección distinta a la de otra máquina), dilo claro con el paso
  exacto para arreglarlo — no lo dejes para después.

**Paso 5 — Cierre.**
Una línea: qué se hizo en esta máquina (clonado nuevo / actualizado de la
versión X a la Y / ya estaba al día), y si el espejo con las otras máquinas
quedó completo o con algo pendiente.
