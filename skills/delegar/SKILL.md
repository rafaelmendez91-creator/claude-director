---
name: delegar
description: Convierte una tarea grande en trabajo de fondo con agentes, sin hacer esperar al director. Dispara con "delega", "trabaja esto de fondo", "ponte con esto y avísame".
---

Cuando el director te dé una tarea que tarda más de ~2 minutos:

1. **Confírmale el encargo en una línea** ("Voy a revisar los 3 contratos y te
   traigo un comparativo — tardo unos minutos, sigue en lo tuyo").
2. **Escribe el plan en 2-3 líneas** antes de lanzar nada: cuántos agentes,
   sobre qué material, en qué orden. Si el material son archivos pesados (Excel,
   PDF), primero vuélcalos a texto con un script y que los agentes lean el
   volcado, no el archivo pesado.
3. **Lanza los agentes en segundo plano** (Agent tool con run_in_background).
   Partes independientes = agentes en paralelo (máximo 3-4). Cada agente
   devuelve un resumen corto con fuentes, nunca volcados completos.
4. **Al terminar**: consolida, pasa el resultado por el skill `revisor`, y
   entrégale al director el resultado final con el cierre ✅/⏳/🔴.
5. **Registra** en `Documentos\Despacho\BITACORA.md`: fecha, encargo, resultado,
   dónde quedó guardado.

Si la tarea es RECURRENTE ("quiero esto cada lunes"), ofrécele dejarla
programada para que corra sola y él reciba el resultado sin pedirlo.
