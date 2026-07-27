---
name: sincroniza
description: Revisa esta máquina, clona o actualiza la copia PERSONAL del director en GitHub y la deja igual que las demás - no asume nada, lo verifica en archivos. Dispara con "sincroniza mi oficina", "ponme al día", "es la primera vez en esta máquina", "configúrame igual que en la otra compu".
---

**Sigue primero la "Secuencia de arranque" de tus reglas de la casa (CLAUDE.md)
— pasos 1 y 2 de esa sección son exactamente cómo encontrar la dirección de SU
copia aquí.** Esta no es la plantilla pública de Rafael — es la copia PERSONAL
del director en su propia cuenta de GitHub, con el nombre que él le haya
puesto. Recordatorio corto de esos dos pasos:
1. `~/.claude/CLAUDE.md` local, "Datos de esta instalación" — si ya está, listo.
2. Si no: UN solo intento dirigido buscando el Despacho en la raíz de "Mi
   unidad" de Drive, y lee `CONFIG.md` ahí. Si esa única búsqueda no da
   resultado, NO la repitas de otra forma: pregúntale al director directamente
   y guarda la respuesta en ambos lugares para la próxima vez.

**Regla dura: nunca te quedes "revisando" indefinidamente.** Si un intento
dirigido no da resultado, no lo repitas ni amplíes el alcance por tu cuenta —
pasa directo a preguntar. Quedarte buscando en silencio es peor que preguntar
una vez.

**Paso 2 — Detecta el estado real de ESTA máquina (no de otra).**
- Revisa si la carpeta de su copia ya existe AQUÍ, en ESTE disco (ruta anotada
  en las reglas de la casa de ESTA máquina). Si no hay nada anotado ahí,
  trátalo como primera vez en esta máquina — no preguntes, verifícalo tú mismo
  revisando la carpeta local.
- **Una entrada de `BITACORA.md` que diga que el paquete ya se instaló NUNCA
  es prueba de que está instalado aquí** — esa línea puede describir otra
  máquina (revisa la etiqueta `[Nombre de máquina]` al inicio de cada línea).
  Solo cuenta lo que encuentres físicamente en ESTE disco.

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
