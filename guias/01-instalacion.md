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

## Si algo falla

Dígale a Claude: *"algo falló en la instalación, diagnostícalo y dime en
lenguaje simple qué pasa"*. Él revisa solo. Si no lo resuelve, el contacto
técnico es Rafael.
