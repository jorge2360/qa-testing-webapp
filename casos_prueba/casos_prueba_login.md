# Casos de prueba - Login

## CP-001 - Inicio de sesión exitoso

| Campo | Detalle |
|---|---|
| Módulo | Login |
| Prioridad | Alta |
| Tipo | Funcional |
| Precondición | Usuario registrado previamente |
| Datos de prueba | correo válido y contraseña válida |
| Pasos | 1. Ingresar al login. 2. Escribir correo. 3. Escribir contraseña. 4. Presionar ingresar. |
| Resultado esperado | El sistema debe permitir el acceso y redirigir al dashboard. |
| Resultado obtenido | Pendiente |
| Estado | Pendiente |

---

## CP-002 - Login con credenciales incorrectas

| Campo | Detalle |
|---|---|
| Módulo | Login |
| Prioridad | Alta |
| Tipo | Validación |
| Precondición | Usuario registrado |
| Datos de prueba | correo válido y contraseña incorrecta |
| Pasos | 1. Ingresar al login. 2. Escribir credenciales incorrectas. 3. Presionar ingresar. |
| Resultado esperado | El sistema debe mostrar mensaje de error y no permitir acceso. |
| Resultado obtenido | Pendiente |
| Estado | Pendiente |

---

## CP-003 - Login con campos vacíos

| Campo | Detalle |
|---|---|
| Módulo | Login |
| Prioridad | Media |
| Tipo | Validación |
| Precondición | Ninguna |
| Datos de prueba | campos vacíos |
| Pasos | 1. Ingresar al login. 2. Presionar ingresar sin completar campos. |
| Resultado esperado | El sistema debe solicitar completar los campos obligatorios. |
| Resultado obtenido | Pendiente |
| Estado | Pendiente |