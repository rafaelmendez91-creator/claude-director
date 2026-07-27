---
name: sincroniza
description: Revisa esta máquina, clona o actualiza la copia PERSONAL del director en GitHub y la deja igual que las demás - no asume nada, lo verifica en archivos. Dispara con "sincroniza mi oficina", "ponme al día", "es la primera vez en esta máquina", "configúrame igual que en la otra compu".
---

**No reconstruyas de memoria: todo el estado sale de archivos.** Que ya lo
hayas hecho en otra computadora no significa nada aquí. Y esta NO es la
plantilla pública de Rafael — es la copia PERSONAL del director en su propia
cuenta de GitHub, con el nombre que él le haya puesto.

**Paso 1 — Encuentra la dirección de SU copia (nunca la des por sabida).**
Búscala en este orden, **cada uno con UN SOLO intento dirigido — nunca un
barrido completo de nada** — parando en el primero que dé resultado:
1. Tus reglas de la casa (`~/.claude/CLAUDE.md`, "Datos de esta instalación").
2. El Despacho SIEMPRE está en la RAÍZ de "Mi unidad" (nunca dentro de otra
   carpeta) — búscalo por ese nombre exacto y en esa ubicación exacta, con UNA
   sola búsqueda dirigida por el conector de Drive (búsqueda por nombre, no
   listar ni recorrer todo el Drive). Si esa única búsqueda no lo encuentra al
   primer intento, NO sigas buscando de otras formas: pasa directo al punto 3.
3. Pregúntale al director, UNA vez: "¿cuál es la dirección de tu copia en
   GitHub?" — y en cuanto la tengas, guárdala en AMBOS lugares (tus reglas de
   la casa Y `Despacho/CONFIG.md`) para que ninguna otra máquina tenga que
   volver a preguntarla ni buscarla.

**Regla dura: nunca te quedes "revisando" indefinidamente.** Si en cualquier
paso de este skill una búsqueda no da resultado en el primer intento dirigido,
NO la repitas de otra manera ni amplíes el alcance por tu cuenta — pasa
directo a preguntarle al director. Quedarte buscando en silencio es peor que
preguntar una vez.

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
