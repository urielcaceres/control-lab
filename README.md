# Sistema de Control de Acceso al Laboratorio Informático

Programa de consola desarrollado en Python que automatiza la verificación de acceso de estudiantes a un laboratorio informático. El sistema evalúa varios requisitos, decide si el acceso es permitido o denegado y genera un resumen estadístico al finalizar.

## Características

- Registro de múltiples solicitudes en una sola ejecución mediante un bucle controlado por el usuario.
- Validación de tres requisitos: matrícula vigente, credencial válida y mayoría de edad (18 años o más).
- Mensajes específicos que indican qué requisito no se cumple.
- Validación de entradas: solo se aceptan respuestas "si" o "no", sin importar mayúsculas o minúsculas.
- Resumen final con solicitudes procesadas, accesos permitidos, accesos denegados y porcentaje de aprobación.

## Requisitos de acceso

Un estudiante puede ingresar únicamente si cumple **las tres condiciones**:

| Requisito | Condición |
|-----------|-----------|
| Matrícula | El estudiante está matriculado |
| Credencial | Posee una credencial válida |
| Edad | Tiene 18 años o más |
