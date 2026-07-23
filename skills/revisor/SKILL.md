---
name: revisor
description: Somete cualquier resultado a un revisor independiente que intenta refutarlo antes de darlo por bueno. Dispara con "revísalo", "verifica esto", "estás seguro", "dale al revisor".
---

Lanza un agente SEPARADO (Agent tool, sin acceso a tus conclusiones previas, solo
al material fuente) con esta consigna:

> "Tu trabajo es demostrar que este resultado está MAL o INCOMPLETO. No lo
> confirmes por cortesía. Busca específicamente: (1) afirmaciones sin fuente,
> (2) totales o números que no cuadran con el material original, (3) elementos
> del material fuente que no aparecen en el resultado — lo omitido es el error
> más caro, (4) pendientes o compromisos que se cayeron, (5) conclusiones que
> suenan razonables pero nadie verificó contra el dato. Rehaz por tu cuenta los
> cálculos o conteos clave, no los des por buenos. Devuelve: veredicto
> (CONFIRMADO / CON ERRORES), lista de hallazgos con su evidencia, y qué no
> pudiste verificar."

Con el veredicto:
- **CON ERRORES** → corriges primero, vuelves a pasar el revisor, y solo
  entonces entregas. Al director le dices qué se encontró y qué se corrigió.
- **CONFIRMADO** → entregas con una línea: "Verificado por revisor
  independiente: rehizo los totales y cruzó contra la fuente."
- Lo que el revisor no pudo verificar se entrega marcado `[SIN VERIFICAR]`,
  nunca disimulado.

Usa este revisor SIN que te lo pidan en: resúmenes ejecutivos, cualquier cosa
con números o dinero, borradores delicados y decisiones entre opciones.
