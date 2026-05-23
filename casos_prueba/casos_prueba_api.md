# Casos de prueba - API REST

## CP-009 - Registro de usuario por API

| Campo | Detalle |
|---|---|
| Módulo | API Autenticación |
| Prioridad | Alta |
| Tipo | API Testing |
| Método | POST |
| Endpoint | `/api/register` |
| Precondición | El correo no debe estar registrado |
| Datos de prueba | nombre, correo, contraseña y confirmación |
| Resultado esperado | El sistema debe registrar el usuario y devolver token de autenticación. |
| Estado | Pendiente |

---

## CP-010 - Login por API

| Campo | Detalle |
|---|---|
| Módulo | API Autenticación |
| Prioridad | Alta |
| Tipo | API Testing |
| Método | POST |
| Endpoint | `/api/login` |
| Precondición | Usuario registrado |
| Datos de prueba | correo y contraseña válidos |
| Resultado esperado | El sistema debe devolver usuario autenticado y token. |
| Estado | Pendiente |

---

## CP-011 - Acceso a tareas sin token

| Campo | Detalle |
|---|---|
| Módulo | API Tareas |
| Prioridad | Alta |
| Tipo | Seguridad / API |
| Método | GET |
| Endpoint | `/api/tasks` |
| Precondición | No enviar token |
| Datos de prueba | Sin header Authorization |
| Resultado esperado | El sistema debe denegar acceso con código 401. |
| Estado | Pendiente |

---

## CP-012 - Listar tareas con token válido

| Campo | Detalle |
|---|---|
| Módulo | API Tareas |
| Prioridad | Alta |
| Tipo | API Testing |
| Método | GET |
| Endpoint | `/api/tasks` |
| Precondición | Usuario autenticado |
| Datos de prueba | Header Authorization Bearer Token |
| Resultado esperado | El sistema debe devolver listado de tareas del usuario autenticado. |
| Estado | Pendiente |

---

## CP-013 - Crear tarea por API

| Campo | Detalle |
|---|---|
| Módulo | API Tareas |
| Prioridad | Alta |
| Tipo | API Testing |
| Método | POST |
| Endpoint | `/api/tasks` |
| Precondición | Usuario autenticado |
| Datos de prueba | título, descripción, prioridad, estado |
| Resultado esperado | El sistema debe crear la tarea y devolver respuesta exitosa. |
| Estado | Pendiente |

---

## CP-014 - Validación al crear tarea sin título

| Campo | Detalle |
|---|---|
| Módulo | API Tareas |
| Prioridad | Media |
| Tipo | Validación API |
| Método | POST |
| Endpoint | `/api/tasks` |
| Precondición | Usuario autenticado |
| Datos de prueba | request sin título |
| Resultado esperado | El sistema debe devolver error de validación 422. |
| Estado | Pendiente |