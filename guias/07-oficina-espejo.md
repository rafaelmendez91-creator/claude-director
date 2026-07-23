# Guía 7 — Su oficina espejo: todos sus aparatos, un solo asistente

## La idea

Su asistente no vive en una computadora. Vive en dos lugares que TODOS sus
aparatos ven por igual:

1. **Su cuenta de Google** — correo, calendario y archivos (incluido su
   Despacho, que va dentro de Drive).
2. **Su cuenta de Claude** — las conexiones autorizadas y las rutinas
   programadas.

Por eso da lo mismo desde dónde pregunte: el todo-en-uno de la oficina, la
laptop de la casa, la tablet o el teléfono. Es el mismo asistente, con la misma
memoria, viendo los mismos archivos.

## Conectar su cuenta de Google (una sola vez, vale para todo)

1. Entre a **claude.ai** con su cuenta de Claude, vaya a **Configuración →
   Conectores**.
2. Active **Gmail**, **Google Calendar** y **Google Drive**. Cada uno le abre
   la página oficial de Google donde usted pone "Permitir" — con SU sesión de
   Google, sin darle nunca la contraseña a Claude.
3. Listo: esa autorización queda en su cuenta de Claude, así que aplica en el
   teléfono, la tablet, la web y sus computadoras a la vez. Se revoca cuando
   quiera desde su cuenta de Google (Seguridad → Accesos de terceros).

Con esto su asistente puede leer el correo, ver la agenda y trabajar los
archivos **para planificar y ordenar** — y el kit le impone las dos reglas de
oro: nada se envía sin usted, y nada se borra jamás (solo se archiva o se
reubica; el detalle está abajo).

## Qué va en cada aparato

| Aparato | Qué instalar | Qué hace ahí |
|---|---|---|
| Todo-en-uno laboral | Claude Code + este kit (EMPEZAR_AQUI) | La estación principal: tablero, delegaciones, trabajo de fondo |
| Laptop personal | Lo mismo, con el mismo EMPEZAR_AQUI | Estación gemela: como el Despacho está en Drive, ya está espejada |
| Teléfono | La app de Claude (App Store / Play Store) | Hablarle en la calle: "tablero", "anota: …", "busca…", "prepárame la reunión" |
| Tablet | La app de Claude o claude.ai en el navegador | Igual que el teléfono, con más pantalla para leer cierres y briefs |

En el teléfono y la tablet no se instala nada más: la app usa los conectores de
su cuenta y lee el Despacho por Drive. Un "anota: llamar al banco" dicho desde
el carro queda en la misma lista maestra que ve la oficina.

## Rutinas que corren solas (aunque todo esté apagado)

Las tareas programadas de claude.ai corren en la nube, no en sus máquinas.
Recomendadas para arrancar:

- **7:00 am** — armar el tablero del día y dejarlo listo (Despacho + resumen).
- **Mediodía** — triage del correo nuevo con borradores preparados.
- **Viernes 4 pm** — cierre semanal en `cierres`.

Se piden en español: *"todos los días a las 7 arma mi tablero"*. Cada rutina
queda anotada en `AUTOMATIZACIONES.md` — pida *"lista mis automatizaciones
activas"* cuando quiera auditar qué corre solo.

## La regla que protege todo: reubicar sí, borrar jamás

Su asistente tiene prohibido borrar:

- **Correo**: ordena archivando y con etiquetas (Pendiente respuesta,
  Facturas, por empresa…). La bandeja queda limpia y TODO sigue existiendo —
  buscable — en Archivados. La papelera no se toca.
- **Archivos**: ordena moviendo. Lo dudoso va a una carpeta `_Archivo`, nunca
  a eliminar. Cada sesión de orden termina con el cuadre: "procesé X, reubiqué
  Y, borré 0".
- **Doble red**: Google Drive guarda versiones de cada archivo. Si algo quedó
  distinto a como usted lo quería, pida *"restaura la versión de ayer de este
  archivo"* y vuelve.

## Si dos aparatos tocan lo mismo a la vez

Drive lo concilia solo casi siempre. Si alguna vez genera un archivo "en
conflicto", su asistente tiene la instrucción de no resolver borrando: junta
los dos contenidos, le avisa, y el duplicado queda en `_Archivo` por si acaso.
