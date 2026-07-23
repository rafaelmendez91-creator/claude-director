# Claude Director — su copiloto ejecutivo

Este paquete convierte a Claude en un **jefe de gabinete digital**: un asistente que
revisa su correo, arma su tablero del día, no deja caer ningún pendiente, verifica
su propio trabajo antes de entregárselo, y le habla siempre en lenguaje simple.

No necesita saber de computación. Todo se instala pegando **un solo texto** en Claude.

## Cómo empezar (3 pasos, ~15 minutos)

1. **Instale Claude Code** en su computadora (si aún no está).
   Abra el programa "PowerShell" (está en el menú de inicio de Windows), pegue esta
   línea y presione Enter:

   ```
   irm https://claude.ai/install.ps1 | iex
   ```

   Cuando termine, escriba `claude` y presione Enter. La primera vez le pedirá
   iniciar sesión con su cuenta de Claude (necesita un plan Pro o superior).

2. **Pegue el texto de arranque.** Abra el archivo [EMPEZAR_AQUI.md](EMPEZAR_AQUI.md)
   de esta carpeta, copie TODO el bloque marcado y péguelo en el chat de Claude.
   Claude se configura solo: le crea SU PROPIA copia en SU cuenta de GitHub (con
   el nombre que usted elija), instala sus herramientas, conecta su correo y le
   explica qué quedó listo.

3. **Pruébelo.** Escríbale a Claude: **"tablero"**. Le dará su día en una página:
   correos importantes, pendientes y qué decidir hoy.

## Cuando esté en OTRA de sus máquinas

No memorice pasos distintos por aparato, ni el nombre de su repositorio. Una
sola frase le sirve siempre, sea la primera vez ahí o ya la haya usado antes —
Claude decide solo qué hace falta mirando esta misma máquina, no su recuerdo
de otra, y casi siempre encuentra la dirección de su copia solo (queda
anotada en su Despacho de Drive). Si en una máquina muy nueva su Drive todavía
no está a la vista, se lo pregunta una sola vez y ya no vuelve a hacerlo:

> **"Sincroniza mi oficina con mi repositorio personal de GitHub."**

Si la máquina es nueva, la deja instalada de cero. Si ya la había configurado,
la actualiza a la última versión. Detalle en [guía 08](guias/08-sincronizar-mis-maquinas.md).

## Qué hay en esta carpeta

| Carpeta / archivo | Qué es |
|---|---|
| [EMPEZAR_AQUI.md](EMPEZAR_AQUI.md) | El texto que se pega una sola vez para configurar todo |
| [CLAUDE.md](CLAUDE.md) | Las "reglas de la casa" de su asistente: cómo piensa, verifica y le habla |
| [skills/](skills/) | Las órdenes que su Claude entiende: "tablero", "revisa mi correo", "revísalo", etc. |
| [guias/](guias/) | Explicaciones cortas en lenguaje simple (correo, agentes, GitHub, pendientes) |
| [RECOMENDACIONES.md](RECOMENDACIONES.md) | Consejos de operación y cómo delegar el mantenimiento técnico |
| [ACTUALIZACIONES.md](ACTUALIZACIONES.md) | Qué trae cada versión. Para actualizar: dígale a Claude *"sincroniza mi oficina"* |
| `skills/sincroniza` | La frase única para cualquier máquina: clona si es nueva, actualiza si no |

## Las 5 promesas de este sistema

1. **Nada se pierde.** Todo pendiente queda escrito con responsable y fecha. Lo que
   falta se marca `[FALTA]`, nunca se inventa.
2. **Nada se envía solo y nada se borra.** Correos y mensajes quedan como
   borradores; usted aprueba. Al ordenar, todo se archiva o se reubica — la
   papelera no se toca.
3. **Todo se verifica.** Antes de entregarle un resultado importante, un "revisor"
   independiente intenta encontrarle errores.
4. **Lenguaje simple.** Su asistente le habla como a un director, no como a un ingeniero.
5. **Sus claves son suyas.** Claude nunca le pedirá contraseñas por el chat.

---
*Preparado por el equipo de Rafael para la dirección. Dudas: Rafael.*
