# Actualizaciones del paquete

**Para el director:** cuando Rafael avise que hay versión nueva, dígale a su
asistente: *"actualiza el paquete claude-director"*. Él descarga lo nuevo, lee
este archivo y aplica los cambios.

**Para Claude (instrucción obligatoria):** al pedirte actualizar: (1) haz
`git pull` en la carpeta del paquete, (2) lee este archivo completo, (3)
**RE-APLICA los archivos cambiados** — vuelve a copiar `CLAUDE.md` y `skills/`
a tu configuración (`~/.claude/`) integrando sin perder las "Preferencias del
director" ni los "Datos de esta instalación" — y (4) confirma al director en 3
líneas qué cambió. "Ya lo leí antes" NO es válido: leído no es instalado. La
versión instalada se anota en tus reglas de la casa, sección "Datos de esta
instalación"; si es menor que la de aquí, aplica todo lo que falte.

---

## v1.4 — 2026-07-23 · Su propia copia, no la de Rafael

- **EMPEZAR_AQUI (nueva PARTE 0)**: lo primero que hace la instalación es
  crear la copia PERSONAL del director en SU cuenta de GitHub, con el nombre
  que él elija — deja de depender de la cuenta de Rafael y de llamarse
  "claude-director".
- **`Despacho/CONFIG.md`**: guarda la dirección de esa copia personal dentro
  del Despacho (en Drive), para que cualquier máquina la encuentre sola.
- **Skill `sincroniza` actualizada**: ahora busca la dirección en las reglas de
  la casa y, si no está, en `Despacho/CONFIG.md` — nunca asume un nombre fijo.
- **La frase única cambia** a: "Sincroniza mi oficina con mi repositorio
  personal de GitHub" (ya no menciona "claude-director").
- **Corrección de revisor**: la copia personal se crea como repositorio NUEVO
  y separado (nunca un "fork" visible que quede ligado a la cuenta de
  Rafael) — con nombre y visibilidad (recomendado privada) elegidos por el
  director. PARTE 0 ahora también revisa primero si ya existe una copia antes
  de crear otra, y avisa que en ese paso aparecerán ventanas de aprobación de
  terminal (no solo de navegador). Guía 02 actualizada para reflejar el
  Despacho real (4 archivos + `cierres`, en Drive).

## v1.3 — 2026-07-23 · Una frase para todas las máquinas

- **Skill `sincroniza`**: detecta el estado real de CADA máquina desde sus
  archivos (no de memoria) — clona el paquete si es la primera vez ahí,
  actualiza si ya existía, y verifica que el espejo (Despacho + conectores)
  quede igual que en las demás.
- **Guía 08**: la frase única — "Sincroniza mi oficina con mi repositorio
  claude-director" — sirve igual en una máquina nueva que en una ya montada.

## v1.2 — 2026-07-23 · Colaboración sin frenos

- **CLAUDE.md**: nueva sección "Colabora, no frenes" — decir exactamente qué
  aprobar en vez de detenerse; la defensa anti-inyección no es excusa para no
  trabajar; ámbito de UNA carpeta en operaciones masivas; chequeo de trabajo a
  medias antes de "ejecuta/continúa"; revisar lo ya conectado antes de cambiar.
- **Guía 01**: qué hacer cuando Claude pide permiso, y qué es (y cuándo usar)
  el modo "omitir permisos".
- **Skill `ordenar`**: limpieza por antigüedad ("archivos de más de un año")
  moviendo a `_Archivo`, nunca eliminando.

## v1.1 — 2026-07-23 · Oficina espejo

- Despacho en Google Drive (visible desde todos los aparatos), guía 07 de
  multi-dispositivo, skill `ordenar`, regla "reubicar sí, borrar jamás".

## v1.0 — 2026-07-23 · Kit inicial

- Método completo, 8 skills, 6 guías, permisos de solo-lectura pre-aprobados.
