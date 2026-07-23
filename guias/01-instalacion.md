# Guía 1 — Instalación y conexiones (una sola vez)

## Instalar Claude en su computadora (Windows)

1. Abra **PowerShell**: presione la tecla Windows, escriba "PowerShell", Enter.
   (PowerShell es la ventana de comandos de Windows; su asistente la usará mucho,
   usted casi nunca.)
2. Pegue esta línea y presione Enter:
   ```
   irm https://claude.ai/install.ps1 | iex
   ```
3. Cuando termine, escriba `claude` y Enter. Le pedirá iniciar sesión con su
   cuenta de Claude en el navegador (una sola vez). Necesita plan Pro o superior:
   sin él, el uso se corta a mitad del día.

## Conectar su correo, calendario y Drive

Su asistente NO necesita su contraseña, y nunca debe pedírsela. La conexión
funciona con **conectores**: usted autoriza una vez en la página oficial de
Google (igual que cuando una app le pide "permitir acceso"), y Claude recibe un
permiso limitado que usted puede revocar cuando quiera desde su cuenta de Google.

Para conectarlos, simplemente dígale a Claude: *"conecta mi Gmail y mi
calendario"*. Él le abre la página de autorización y le dice dónde hacer clic.

**Regla que su asistente ya trae de fábrica:** puede LEER su correo y preparar
BORRADORES, pero enviar, borrar o mover algo importante siempre se lo consulta.

## Por qué casi no le pedirá permisos

Claude pide permiso antes de ejecutar acciones en su computadora. Este paquete
trae una lista pre-aprobada: todo lo que es MIRAR (leer carpetas, buscar
archivos, consultar estado) pasa sin interrumpirlo; todo lo que CAMBIA algo
(borrar, enviar, instalar, publicar) sigue requiriendo su "sí". Así usted no
vive aprobando ventanitas, pero nada delicado ocurre sin usted.

Si aun así le pregunta demasiado por cosas de solo mirar, dígale: *"estas
consultas de solo lectura apruébalas solas de ahora en adelante"* — él ajusta la
lista y le confirma qué agregó.

## Cuando Claude le pida permiso

Su asistente tiene la instrucción de no frenarse con explicaciones largas:
debe decirle en una línea **qué va a hacer y qué botón aprobar**. Si alguna vez
se pone excesivamente precavido (se niega a leer un documento "por seguridad",
o le da un discurso en vez de una instrucción), recuérdeselo: *"dime qué
aprobar y sigue"*. Está entrenado para aceptar ese reclamo.

## El modo "omitir permisos" (úselo con criterio)

Existe una forma de arrancar Claude en la que **no pregunta nada**: ejecuta
todo de corrido. Es cómodo para tareas largas y mecánicas, pero quita el
cinturón de seguridad. Recomendación:

- **No lo use como modo diario.** Para el día a día, la lista pre-aprobada ya
  evita las ventanitas de "solo mirar".
- **Sí puede valer la pena** para una tarea puntual y acotada — por ejemplo,
  ordenar una carpeta con miles de archivos sin aprobar movimiento por
  movimiento. En ese caso, tres condiciones: (1) una sesión dedicada SOLO a esa
  tarea, (2) el trabajo limitado a UNA carpeta declarada de antemano, nunca el
  Escritorio o el disco entero, y (3) recordar que las reglas de la casa siguen
  vigentes — sin permisos que aprobar, lo que lo protege son las reglas: nada
  se borra, nada se envía.
- Para activarlo, pídaselo a su asistente: *"dame el comando para arrancar sin
  permisos para esta tarea"* — él se lo da y le repite las condiciones. Al
  terminar la tarea, vuelva a abrir Claude de la forma normal.

## Si algo falla

Dígale a Claude: *"algo falló en la instalación, diagnostícalo y dime en
lenguaje simple qué pasa"*. Él revisa solo. Si no lo resuelve, el contacto
técnico es Rafael.
