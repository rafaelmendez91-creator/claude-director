---
name: pendientes
description: Administra la lista maestra de pendientes del director - agregar, cerrar, reclamar vencidos. Dispara con "pendientes", "anota", "qué está vencido", "cierra el pendiente de".
---

La lista maestra vive en `PENDIENTES.md` del Despacho (la ruta exacta está en
tus reglas de la casa). Es UNA sola lista
para todas las empresas. Formato de cada línea:

`- [ ] (Empresa) Qué hay que hacer — Responsable — vence AAAA-MM-DD — fuente`

Operaciones:
- **"anota …"** → agrega la línea completa. Si falta responsable o fecha,
  pregunta UNA vez; si el director no la da, pon `[FALTA: fecha]` y agrégala igual.
- **"pendientes"** → muestra la lista agrupada: 🔴 vencidos, 🟡 esta semana,
  ⚪ después. Nunca muestres más de 15 líneas; el resto resúmelo por grupo.
- **"cierra …"** → marca `[x]`, anota la fecha de cierre y muévela a la sección
  `## Cerrados` del mismo archivo. Nada se borra: el historial es la memoria.
- **"qué está vencido"** → los vencidos con responsable, y para cada uno propone
  el borrador del mensaje de reclamo (que el director aprueba antes de enviar).

Regla de oro: un pendiente sin responsable y sin fecha no es un pendiente, es un
deseo. Ayuda al director a convertir deseos en pendientes.
